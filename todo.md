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
