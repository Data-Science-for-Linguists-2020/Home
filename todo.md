# Daily To-do Assignments


<a name="todo1"/></a>
## To-do #1
Due 1/9 (Th), 12:30pm

The Internet is full of published linguistic data sets. Let's data-surf! Instructions:

1. Go out and find **two linguistic data sets** you like. One should be a corpus, the other should be some other format. They must be free and downloadable in full. Make sure they are _linguistic_ data sets, meaning designed for linguistic inquiries.
1. You might want to start with various bookmark sites listed in the following Learning Resources sections: [Linguistic Data, Open Access, Data Publishing](https://github.com/Data-Science-for-Linguists-2020/Home/blob/master/resources.md#linguistic_data), and [Corpus Linguistics](https://github.com/Data-Science-for-Linguists-2020/Home/blob/master/resources.md#corpus). But don't be constrained by them.
1. Download the data sets and poke around. Open up a file or two to take a peek. (No need to do this in Python.)
1. In a text file (should have the `.txt` extension), make note of:
  - The name of the data resource
  - The author(s)
  - The URL of the download page
  - Its makeup: size, type of language, format, etc.
  - License: whether it comes with one, and if so what kind?
  - Anything else noteworthy about the data. A sentence or two will do.
1. If you are comfortable with [markdown](https://github.com/Data-Science-for-Linguists-2020/Home/blob/master/resources.md#markdown), make an `.md` file instead of a text file.

**SUBMISSION**: Upload your text file to To-do1 submission link, on CourseWeb. If you do not have CourseWeb access, email your submission to Jevon cc Cassie and John.



<a name="todo2"/></a>
## To-do #2
Due 1/16 (Th), 12:30pm

Learn about the `numpy` library: study the _Python Data Science Handbook_ and/or the NumPy documentation [here](https://numpy.org/doc/).
While doing so, create your own study notes, as a Jupyter Notebook file entitled `numpy_notes_yourname.ipynb`.
Include examples, explanations, etc. Replicating DataCamp's examples is also something you could do.
You are essentially creating your own reference material.

**SUBMISSION**: Your file should be in the `todo2/` directory of the `Class-Exercise-Repo`.
Make sure it's configured for the "upstream" remote and your fork is up-to-date. Push to your GitHub fork, and create a pull request for me.



<a name="todo3"/></a>
## To-do #3
Due 1/21 (Tue)

Study the `pandas` library (through the [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/index.html) and/or the [documentation](https://pandas.pydata.org/pandas-docs/stable/user_guide/index.html). `pandas` is a big topic with lots to learn: aim for about 1/2. While doing so, try it out on TWO spreadsheet (.csv, .tsv, etc.) files:

1. The first file should be your choice. You can get one from [this CSV Files archive](https://corgis-edu.github.io/corgis/csv/), or make up your own.
Keep it super simple! It's supposed to be a toy dataset.
1. The second one should be `billboard_lyrics_1964-2015.csv` by Kaylin Pavlik, from her project '[50 Years of Pop Music](https://www.kaylinpavlik.com/50-years-of-pop-music/)'.
(Note: you might need to specify ISO8859 encoding.)

Name your Jupyter Notebook file `pandas_notes_yourname.ipynb`. Don't change the filename of any downloaded CSV files or edit them in any way.  

**SUBMISSION**:  Your files should be in the `todo3/` directory of `Class-Exercise-Repo`.
Commit and push all three files to your GitHub fork, and create a pull request for me.  



<a name="todo4"/></a>
## To-do #4
Due 1/23 (Thu)

This one is a continuation of To-do #3: work further on your `pandas` study notes. You may create a new JNB file, or you can expand the existing one. Also: try out a spreadsheet submitted by a classmate. You are welcome to view the classmate's notebook to see what they did with it. (How to find out who submitted what? Git/GitHub history of course.) Give them a shout-out.

**SUBMISSION**: We'll stick to the `todo3/` directory in `Class-Exercise-Repo`. Push to your GitHub fork, and create a pull request for me.



<a name="todo5"/></a>
## To-do #5
Due 1/30 (Thu)

For this To-do, refer back to the edited version of `english.csv` from class Activity 3. Add a markdown cell block to your Jupyter Notebook file for activity3 clearly labeling the beginning of To-do #5.

This time we'll look at the response times for the naming task (`RTnaming`). The equipment that Balota et al. used to gather this naming data was voice-activated. As such, the acoustic properties of a word's initial segment may have affected the time it took to register a response. Let's figure out whether it did.

1. Inspect the distribution of naming latencies.
  - Plot two histograms for the naming latencies, with different bin sizes.
  - Plot the density of the naming latencies. Is this a normal distribution?
1. The column `Voice` specifies whether a word's initial phoneme was voiced or voiceless. Make a boxplot for the distribution of reaction times across voiced and voiceless phonemes, grouped by subject age.

**SUBMISSION**: Submit a pull request including your updated JNB file.




<a name="todo6"/></a>
## To-do #6
Due 2/11 (Tue)

The [Gries &amp; Newman article](resources.md#corpus) cites many famous corpora and corpus resources. Let's round them all up in a single spot, complete with web links. We will collaborate on a shared document called [`'corpora_tools_list.md'`](https://github.com/Data-Science-for-Linguists-2020/Class-Plaza/blob/master/corpora_tools_list.md).

- The [`Class-Plaza` repo](https://github.com/Data-Science-for-Linguists-2020/Class-Plaza) belongs to all of us: we are all listed as a collaborator.
- That means all of us has full read and write access: in GitHub's lingo, we have 'push access'.
- Which means no need to fork; you should directly clone. After that, push and pull directly.

Your job is to fill out the three tables: add at least one entry to each table. Make sure you are not duplicating someone else's entry.
Because everyone is editing the same document, you may run into a conflict while trying to push.
Make sure you have read and understood this [tutorial on Git conflicts](https://github.com/mcdonn/LSA2019-Reproducible-Research/blob/master/linking_git_and_github.md#conflicts) and resolve accordingly.

**SUBMISSION**: There is no formal submission process, because this one does not involve you issuing a pull request or anything like that. I will check on the repo later to see you have indeed made your contribution.  




<a name="todo7"/></a>
## To-do #7
Due 2/13 (Thu)

Let's pool our questions together for [Dr. Lauren Collister](https://openaccess.pitt.edu/node/33) and [Dominic Bordelon](http://dominicbordelon.com/), who will be our guest speakers on Thursday.
Review the topics of [linguistic data, open access, and data publishing](https://github.com/Data-Science-for-Linguists-2020/resources.md#linguistic_data), focusing in particular on these three resources: _Data Management Plans for Linguistic Research_, Kitzes (2018), and the Copyright and Intellectual Property Toolkit.
Think of a question for Lauren, and add yours along with your name to the `questions_coll_bord.md` file in our [`Class-Plaza` repo](https://github.com/Data-Science-for-Linguists-2020/Class-Plaza).

**SUBMISSION**: Push your commit directly to the `Class-Plaza` repo. Make sure you don't trample on someone else's contribution. If there is a conflict, it is your job to resolve it.




<a name="todo8"/></a>
## To-do #8
Due 2/18 (Tue)

Let's try Twitter mining! On a tiny scale that is. This blog post [Data Analysis using Twitter](http://blog.impiyush.com/2015/03/data-analysis-using-twitter-api-and.html) presents an easy-to-follow, step-by-step tutorial, so you should follow it along.

First, you will need to install the `tweepy` library:

- Option 1: Install through Anaconda Navigator. See [this screenshot](https://github.com/Data-Science-for-Linguists-2020/Home/blob/master/etc/todo8_tweepyinstall1.png).
   - See if Tweepy is installed. It likely isn't -- download and install it.
- Option 2: Manual installation through pip. See [these](https://github.com/Data-Science-for-Linguists-2020/Home/blob/master/etc/todo8_tweepyinstall2.png) [screenshots](https://github.com/Data-Science-for-Linguists-2020/Home/blob/master/etc/todo8_tweepyinstall3.png).
   - If `which pip` does not show your Anaconda version of pip, it means you cannot simply go `pip install tweepy`. You will instead have to specify the complete path for Anaconda's pip. So, find your Anaconda installation path, and install Tweepy like so:
`/c/ProgramData/Anaconda3/Scripts/pip install tweepy`
   - Your pip path might be something like `/c/Users/your-user-name/Anaconda3/...`. You should use TAB completion while typing out the path.
   - If you are having trouble finding your Anaconda's path, try `which -a python`. The `-a` flag shows all python executables found in your path.


Notes on using `tweepy`:

- If you don't have a Twitter account, you will have to create one first. And then, you should create an API account.
- This is exciting stuff, but don't go overboard! 100 Tweets are enough for this exercise. Overloading API without taking proper cautionary steps is a sure-fire way to get yourself banned from tech sites.
- You will be using your 'Consumer Key' and 'Consumer Secret' in your code. You should not be sharing them! Right before committing, redact them in your JNB file by changing the string values to 'XXXXXXXXXXXXXX'.  

**SUBMISSION**: We are switching back to [`Class-Exercise-Repo`](https://github.com/Data-Science-for-Linguists-2020/Class-Exercise-Repo); use the `todo8/` folder. Your Jupyter Notebook file should have your name in the file name. Push to your fork and create a pull request. Make sure you have redacted your personal API keys!



<a name="todo9"/></a>
## To-do #9
Due 2/20 (Thu)

What have the [previous students](https://github.com/Data-Science-for-Linguists) [of LING 1340/2340](https://github.com/Data-Science-for-Linguists-2019) accomplished? What do finished projects look like? Let's have you explore their past projects. Details:

- We'll collaborate on a single file: [`todo9_past_project_critiques.md`](https://github.com/Data-Science-for-Linguists-2020/Class-Plaza/blob/master/todo9_past_project_critiques.md) in `Class-Plaza`.
- Pick **two projects**, but you can't pick one that already has three critiques. (If someone gets the last spot while you're working, you'll have to pick a new one. And: declaring "dibs" is allowed, as long as you intend to finish the work within the next hour.)
- Create a section for yourself. Provide a link to the project repo.
- Your critique should consist of: one thing you thought was done well, one avenue for improvement, and one thing you learned.

**SUBMISSION**: Push your commit directly to the `Class-Plaza` repo. Make sure you don't trample on someone else's contribution. If there is a conflict, it is your job to resolve it.



<a name="todo10"/>
## To-do #10
Due 2/27 (Thu)

Let's try sentiment analysis on movie reviews. Follow [this tutorial from PyLing](http://www.pitt.edu/~naraehan/presentation/Movie%20Reviews%20sentiment%20analysis%20with%20Scikit-Learn.html) in your own Jupyter Notebook file.
Feel free to explore and make changes as you see fit. If you haven't already, review the [_Python Data Science Handbook_](https://github.com/Data-Science-for-Linguists-2020/Home/blob/master/resources.md#data-mining--machine-learning) chapters to give yourself a good grounding.
Also: watch these (or equivalent) YouTube tutorials [Scikit-Learn Tutorial | Machine Learning With Scikit-Learn](https://www.youtube.com/watch?v=0Lt9w-BxKFQ), and [NLP Tutorial with Python & NLTK](https://www.youtube.com/watch?v=X2vAabgKiuM).

Students who took LING 1330: compare sklearn's Naive Bayes with [NLTK's treatment](http://www.pitt.edu/~naraehan/ling1330/Lecture11.pdf) and include a blurb on your impression. (You don't have to run NLTK's code, unless you want to!)

**SUBMISSION**: Your jupyter notebook file should be in the `todo10` folder of [`Class-Exercise-Repo`](https://github.com/Data-Science-for-Linguists-2020/Class-Exercise-Repo). As usual, push to your fork and create a pull request.


<a name="todo11"/></a>
## To-do #11
Due 3/3 (Tue)

What has everyone been up to? Let's take a look -- it's a "visit your classmates" day!

- First off, prepare your own "Guestbook" file. It's already been created in the [`Class-Plaza` repo](https://github.com/Data-Science-for-Linguists-2020/Class-Plaza/tree/master/guestbooks), but you should edit it so that:
   - It has your project title and a link to your repo, and your name
   - And a bit of personalization if you want, like a greeting.
- Now visit your classmates' projects! We will go in alphabetical order by first name, [as seen in the directory](https://github.com/Data-Science-for-Linguists-2020/Class-Plaza/tree/master/guestbooks). You should visit two people after you (Anthony: Joey and Jordan; Joey: Jordan and Juan; Natasha: Sean and Anthony; etc.)
- Take a look around, and write on their guestbook. (You don't have to wait until it's prepped.) Like the previous To-do, your entry should consist of: one thing you thought was done well, one avenue for improvement or suggestion, and one thing you learned.

**SUBMISSION**: Since `Class-Plaza` is a fully collaborative repo, there is no formal submission process.



<a name="todo12"/></a>
## To-do #12
Due 3/31 (Tue)

Let's **poke at big data**. Well, big-ish.
[The Yelp Open Dataset](https://www.yelp.com/dataset) is a subset of their review data, available specifically for use in educational and academic contexts. Let's check it out!  Before we begin:

- You will need a fairly stable internet connection and at least 14GB of free hard drive space.
- Provision enough time. Downloading the dataset alone may take 25 minutes or longer.
- If your laptop is fairly old or running out of space, let me know!  

#### Mode of operation
- After downloading the data set, you should operate exclusively in a command-line environment, utilizing unix tools.
- I am supplying general instructions below, but you will have to fill in the blanks between steps, such as cd-ing into the right directory, invoking your Anaconda Python and finding the right file argument.
- You will be submitting a _short_ (paragraph-length -- this is just a To-do!) write-up as a Markdown file named `yelp_tryout_yourname.md` in the `to-do12/` directory of [`Class-Exercise-Repo`](https://github.com/Data-Science-for-Linguists-2020/Class-Exercise-Repo).

#### Step 1: Preparation, exploration

Let's download this beast and poke around.

1. Download the JSON portion of the data. (We don't need the photos.)
1. Move the downloaded archive file into your `Documents/Data_Science` directory. You might want to create a new folder there for the data files.  
1. From this point on, **operate exclusively in command line**.
1. The file is in the `.tar` format. Look it up if you are not familiar. Untar it using `tar -xvf`. It will extract 6 json files along with some PDF documents.
1. Using various unix commands (`ls -lhAF`, `head`, `tail`, `wc -l`, etc.), find out: how big are the json files? What do the contents look like? How many reviews are there?
1. How many reviews use the word 'horrible'? Find out through `grep` and `wc -l`. Take a look at the first few through `head | less`. Do they seem to have high or low stars?
1. How many reviews use the word 'scrumptious'? Do they seem to have high stars this time?

#### Step 2: A stab at processing
How much processing can our own puny personal computer handle? Let's find out.
1. First, take stock of your computer hardware: disk space, memory, processor, and how old it is.
1. Create a Python script file: `process_reviews.py`. Content below. You can use nano, or you could use your favorite editor (atom, notepad++) provided that you launch the application through command line.

```python
import pandas as pd
import sys
from collections import Counter

filename = sys.argv[1]

df = pd.read_json(filename, lines=True, encoding='utf-8')
print(df.head(5))

wtoks = ' '.join(df['text']).split()
wfreq = Counter(wtoks)
print(wfreq.most_common(20))
```

1. We are NOT going to run this on the whole `review.json` file! Start small by creating a tiny version  consisting of the first 10 lines, named `FOO.json`, using `head` and `>`.
1. Then, run `process_reviews.py` on `FOO.json`. Note that the json file should be supplied as command-line argument to the Python script. Confirm it runs successfully.
1. Next, re-create `FOO.json` with incrementally larger total # of lines and re-run the Python script. The point is to find out how much data your system can reasonably handle. Could that be 1,000 lines? 100,000?
1. While running this experiment, closely monitor the process on your machine. Windows users should use [Task Manager](https://www.howtogeek.com/108742/how-to-use-the-new-task-manager-in-windows-8/), and Mac users should use [Activity Monitor](https://support.apple.com/en-us/HT201464).
1. Finally, write up a short reflection summary as `yelp_tryout_yourname.md`. A paragraph will do. How was your laptop's handling of this data set? What sorts of resources would it take to successfully process it in its entirety and through more computationally demanding processes? Any other observations?

**SUBMISSION**: Your markdown file should be in the `todo12` directory in [`Class-Exercise-Repo`](https://github.com/Data-Science-for-Linguists-2020/Class-Exercise-Repo). Make sure you use the naming convention described here! As usual, push to your fork and create a pull request.


<a name="todo13"/></a>
## To-do #13
Due 4/2 (Thu)

It's "visit your classmates" day, round 2!

- First, maintain your own guestbook. Respond to your classmates' visit logs.
   - No need to post a lengthy response -- you are not starting a debate here!  You can think of it as something akin to Facebook's "like", just a small acknowledgment and a thank you.
- Now visit your classmates' projects. Like before we go by the order of first names, which can be [found right in the directory](https://github.com/Data-Science-for-Linguists-2020/Class-Plaza/tree/master/guestbooks). You should visit two people after your previous visits.  
   - Take a look around, and write on their guestbook. Like the previous visit, your entry should consist of: one thing you thought was done well, one avenue for improvement or suggestion, and one thing you learned. 

**SUBMISSION**: Since `Class-Plaza` is a fully collaborative repo, there is no formal submission process.
