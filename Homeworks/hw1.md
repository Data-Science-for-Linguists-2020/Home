# Homework 1: Explore Linguistic Data
This homework carries a total of 50 points.

For this homework, let's have you explore a linguistic data set using the Python skills you already have.

### Data set

1. You can process any publicly available linguistic data set of your choice.
1. You already took a look at two data sets for [To-do 1](https://github.com/Data-Science-for-Linguists-2020/Home/blob/master/todo.md#todo1): you may pick one of them, or you may choose something else entirely.
1. Many of you are familiar with [NLTK's corpora](http://www.nltk.org/nltk_data/). Do NOT use NLTK's pre-loaded corpora such as `nltk.corpus.brown` and `nltk.corpus.inaugural`.
1. You may, however, download a zipped archive through [this page](http://www.nltk.org/nltk_data/) and process the files as you would any other corpora. You might find [1.9 Loading your own Corpus](http://www.nltk.org/book/ch02.html#loading-your-own-corpus) section useful.


### GitHub dry run with To-do 1
1. Let's have you practice forking before getting on with the homework. We demonstrated this in class on Thursday: [link to slides will be here].
1. If you haven't already, fork `Class-Exercise-Repo` on GitHub. Then, clone your fork onto your laptop.
1. Inside, you will find `todo1/` directory.
1. Find the text file you previously submitted for [To-do 1](https://github.com/Data-Science-for-Linguists-2020/Home/blob/master/todo.md#todo1), and copy it into that directory. Make sure it's named something like `todo1_yourname.txt`, so it won't conflict with some other student's.
1. Do the usual local git routine, which ends with committing. Then push to your own GitHub fork.
1. Then, create a pull request for me. I'll respond as soon as I can!



### Repo, files and folders
1. Start by forking [this `HW1-Repo` GitHub repository](https://github.com/Data-Science-for-Linguists-2020/HW1-Repo).
1. Once you have your own fork in your GitHub account, clone it onto your laptop. DO NOT DIRECTLY CLONE MY ORIGINAL REPO WITHOUT FORKING FIRST.
1. In the directory, you will find a folder with your name, say `jevon/`. Your code, as a Jupyter notebook file (`xxx.ipynb`), should go into that directory.
1. There is a file named `your_file_here.txt`. I put it there simply because without it `git` will ignore empty directories. If you know about `git rm`, use the command to delete it; otherwise, leave it there.
1. You can name the notebook file whatever you want, but remember -- no spaces; use underscore `_` instead.
1. In your personal directory, create a new directory called `data`, all in lowercase. All your data files should go into this directory. No need to change data file names to remove spaces; in fact, do NOT modify the downloaded files at all.
1. In your Python code, use relative paths when referencing data files. That is, use something like  `open("data/corpusfile1.txt")` instead of the full path.
1. The repo is already configured, via the `.gitignore` file in the root, to ignore the `data/` directory and its content, meaning, you are excluding your data files from submission. Jupyter's auto-save files are also ignored.
1. While working on your Jupyter Notebook, you should be frequently committing and pushing to your fork.

### Your code
1. Your Python code should be written as a Jupyter Notebook. If you are not familiar with it, watch the [Dataquest tutorial](https://github.com/Data-Science-for-Linguists-2020/Home/blob/master/resources.md#tools).
1. At the top of your Jupyter notebook should be a markdown cell with following information:
  - Your name, email and date
  - Info on your data set. The name, author(s), download URL, etc. Basically what you reported back in To-do 1.
1. The second cell, another markdown cell, should contain a self-assessment:
  - A summary of what your code does and how you addressed your "discovery" question.
  - A future wish: something that you would have liked to be able to do with this data set but do not know how at the moment.
1. Your code should achieve the following:
  - Open the data files and read in the data.
  - Print out some representative snippets of the data. Don't flash the entire thing -- just enough to get a sense of the content.
  - Print out some basic stats, such as the total number of data points. For corpora, this could be the number of text files, sentences, word tokens, etc.
  - Additionally, you should make one discovery. Pick a question you think you can address with reasonable effort, and explore the data for an answer.
1. Try and see if you can find a way to utilize the upcoming [NumPy library](https://github.com/Data-Science-for-Linguists-2020/Home/blob/master/resources.md#data_processing) in your data processing. Aggregation functions such as `numpy.sum()` and `numpy.mean()` are easy choices. This part is optional.
1. Don't forget to make use of markdown cells for organization, explanation and notes. Use comments as you see fit.

### Submission
1. When you think you have the final version of your work, "Restart & Run All" your Jupyter notebook one last time, so the output is all orderly and tidy. Save the notebook.
<!-- 1. You should also save an HTML version of your notebook: "Download as -> HTML (.html)". Place it in the same directory as your `.ipynb` file. -->
1. After your local Git routine, push the HW1 repo to your own GitHub fork one last time. Check your GitHub fork to make sure the notebook file is there and everything looks OK. Your data files shouldn't be there.
1. Finally, create a pull request for me.


This is a form of **rolling submission**.
Firstly, the original repo and everyone's forks are public.
Additionally, I will not wait until the homework deadline before I start processing pull requests and merging in your contributions.
That means you will be able to view other students' submissions before the deadline. You should feel free to do so.
