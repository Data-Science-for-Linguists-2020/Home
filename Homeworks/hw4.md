# Homework 4: Supercomputing the Yelp Dataset
This homework carries a total of 80 points.


In class, we switched to a more proper venue for the Yelp data: the [CRC's h2p supercomputer cluster](https://crc.pitt.edu/). We already gave [To-do #12](todo#todo12) the advanced computing treatment. For this homework, we will take it one step further: machine learning. What does it take to unleash machine learning on "big data"? Let's find out.

For this homework, in your home directory on CRC, create a folder called `hw4_yelp/` and keep all your work in here. This will be your submission.

## Plan of attack

Wrestling with big data can get hairy without some pre-planning.  Separate your work into two stages:

1. **A TRIAL RUN** on a **tiny slice of data: 10,000 reviews**
  - The "FOO" principle still applies: start small. You don't want to discover a bug in your script 30 minutes into a big job!  In your `hw4_yelp/` directory, create a file named `review_10k.json` as a mini version of `review.json`, containing the first 10,000 lines, and work with it.
  - PLATFORM: **Remote Jupyter Notebook through [CRC hub](https://hub.crc.pitt.edu)**.  
  - This is when you explore your data, experiment with your models, visualize: essentially the whole gamut of data-sciencing.
  - The goal here is for you to find a good model and some parameters for a benchmark, and also to develop the code you will use will later use on a lot more data. The miniature data size and the Jupyter Notebook interface make this process far more manageable.
  - To make Part 2 quicker, you should write your code here to make use of GridSearchCV and pipelines.
 - That said, don't go overboard with many different classifier models. You can even focus on a single classifier model with different parameters.

2. **A FULL(ish)-SCALE RUN**
  - This you don't want to do through Jupyter Notebook! You will need a proper slurm job submission.
  - PLATFORM therefore should be: **Command-line python script through slurm job submission**.
  - Your Python script can be exported from your Jupyter Notebook via the command `jupyter nbconvert --to script your_notebook.ipnyb`. This produces `your_notebook.py`.  Streamline it by removing code blocks that are mainly there for exploration. Visualization likewise is not useful here (unless you save out plots into a file).
  - To begin you should train and test ONE classifier, using `GridSearchCV`. Basically this means passing in lists of length 1 for each of the parameters you're trying to tune.
  - Once you've done that, you can try using the same classifier with different parameters, but make sure to take advantage of parallel processing. You should utilize the `n_jobs` parameter in `GridSearchCV`, and the `--ntasks` SBATCH configuration. You'll notice that as you increase `n_jobs`, things will run faster, but you will consume more memory. You can increase runtime and memory limits with `#SBATCH --time` and `--mem`, respectively.
  - Still, the entire set of 6.7 million reviews is a LOT. We recommend you **start with initial 1 or 2 million lines**. Would be nice to successfully train/test with the entire set, but your best try is fine for this homework. You might find your jobs taking a few hours to run...
  - You can print any output and capture it in a file using by specifying the appropriate filename in the job script with `#SBATCH --output=<output filename>`.


## Task: Classifying negative vs. positive reviews

As for the task itself, we'll keep it simple: negative vs. positive review classification. It's essentially a binary classification problem and a type of sentiment analysis.

- **Target labels** should be 'neg' and 'pos'. Details:
  - Count 1- and 2- star reviews as negative. Likewise, treat 4- and 5- star reviews as positive.
  - What about 3 stars? We'll simply ignore them. You can drop these from your data.

- Specifics:    
   - In terms of features, try TF-IDF vectors and any other features you feel could be useful.
   - Choose one kind of model to thoroughly test.
   - You should build a Pipeline model.
   - Use [GridSearchCV](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GridSearchCV.html#sklearn.model_selection.GridSearchCV) and try various combinations of parameters for each model + perform 5-fold CV.
   - Try to tune at least 1 parameter for each component of the pipeline you produce, and try at least 2 different values per parameter. [This link](https://scikit-learn.org/stable/tutorial/statistical_inference/putting_together.html) will show you the syntax to tweak parts of pipelines in the grid search.
   - For each set of parameters tested by your grid search, you should print out the configuration as well as the mean accuracy across all cross validation splits for that configuration.


## Summary report as `README.md`

That's a lot of moving parts and files, so create a summary document that rounds up everything plus a bit of further analysis. In your `README.md` file:

1. List the content of your submission, that is, the files in your `hw4_yelp/` directory. Give a very short description of the content/purpose.
1. Your "full-scale run" produced some numbers which will need interpretation and analysis. Do so here in its own separate section.
1. A section on further analysis.
	Look closely at the [documentation](https://www.yelp.com/dataset/documentation/main) for the dataset. What are some other analysis questions you might be able to investigate with your machine learning skills? What else would you find interesting to predict, and which attributes might serve as useful features?


### Some things to keep in mind:

- Start early! Your slurm jobs will be stuck in a batch queue and and have to wait their turn to run. And when they start running, they'll probably take a while. They might even crash halfway through running if you have mistakes in your code...
- If you need some additional python package, after loading the appropriate python module on CRC, run `pip install <package> --user` to install a copy for yourself. If you need the package on  [https://hub.crc.pitt.edu](https://hub.crc.pitt.edu), in a cell at the top of your notebook, run `!pip install <package> --user`.
- If you choose **Python 3.7**, `nltk` is not installed for this version: you will need to install your own personal copy. Alternatively, you may choose **Python 3.6**, which does come with the `nltk` library.
- The Yelp dataset as well as NLTK's corpus and grammar data are all found in last year's shared data folder: `/zfs2/ling1340-2019s/shared_data/`.
- To run any NLTK function that relies on `nltk_data` (e.g., `word_tokenize`), you should execute `nltk.data.path.append('/zfs2/ling1340-2019s/shared_data/nltk_data')` in your script.
- You will have to mess around with your #SBATCH settings on your job script. Things like runtime, and memory configurations may cause your jobs to fail.
- If you're using the command line to edit things, you'll have to use `nano`, which might be painfully slow. You can do the bulk of the python coding in your CRC Hub notebook, but you'll have to edit slurm job scripts manually. Many text editors have packages you can install that will open up a connection to the server and allow you to edit things from your local editor. For example, in Atom, from Edit > Preferences > Install, you can get the [remote-edit](https://atom.io/packages/remote-edit) package, which well let you input the information you need open up a connection with the CRC server.
- Finally, you can write your scripts locally and SCP them over in the same way we copied over `process_reviews.py` in class.

<!--
- If you have X11 forwarding set up, you can simply add the `-X` flag to your `ssh` command, like `ssh -X <username>@h2p.crc.pitt.edu`, and you should be able to directly use `gedit` to edit files with a user interface with `gedit <filename>`. If this fails, you can google how to set up X11 forwarding on your system (should be simple for Mac users, not so much for Windows).
-->





### Submission

We have read access to your `hw4_yelp/` directory, so that's your submission. It should include:

- README.md
- Slurm job files
- Output files
- `review_10k.json` file
- `review_Xmil.json` file(s), if any
- Python script(s)
- Jupyter notebook(s)
