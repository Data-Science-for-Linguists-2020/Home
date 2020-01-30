# Homework 2: Process the ETS Corpus
This homework carries a total of 80 points.

For this homework, we will explore and process the [ETS Corpus of Non-Native Written English](https://catalog.ldc.upenn.edu/LDC2014T06), using Python's `numpy` and `pandas` libraries we recently learned.

## Data set
- The corpus was published by the LDC ([Linguistic Data Consortium](https://www.ldc.upenn.edu/)). I have acquired license on behalf of all Pitt faculty and students. I am distributing the data through the privately held "Licensed-Data-Sets" repo of our class GitHub organization.
- If you haven't already, clone the repo as your local repository. There's no need to fork.
- You should keep the data files in its original directory location and its original form.

## Repo, files and folders
- Start by forking [this `HW2-Repo` GitHub repository](https://github.com/Data-Science-for-Linguists-2020/HW2-Repo). Your fork will automatically be set to a private repo.
- Clone it onto your laptop. Unlike with the "Licensed-Data-Sets" repo, you SHOULD NOT DIRECTLY CLONE MY ORIGINAL REPO. FORK FIRST, and then CLONE YOUR FORK.
- In the directory, you will find a folder with your name, say `jevon/`. Your code, as a Jupyter Notebook (JNB) file (`xxx.ipynb`), should go into that directory. *After* you have created your JNB file, you can go ahead and delete the dummy file `your_file_here.txt`. (Remember to use `git rm`.)
<input type="button" class="button" onclick="return toggleMe('ts1')" value="Trouble shooting" >
<div class="hint" id="ts1">
Beware: if you git-delete the dummy file through <code>git rm</code> BEFORE creating your notebook file in there, git will see the directory as empty and hide it from your view. (That's the reason I included the dummy file in the first place.) No need to panic. You can undo it by typing in <code>git checkout -- your_script_here.txt</code>. This essentially throws away that last change you made in the repo. After that, <code>git status</code> to confirm you now have a clean slate.
</div>  
- You can name the notebook file whatever you want, but use underscore `_` instead of spaces.
- As noted in the section above, your corpus data files should remain in their original directory location. Do not move or copy them into this repo.
<!-- - The repo is already configured, via the .gitignore file in the root, to ignore your Jupyter checkpoint directory .ipynb_checkpoints. -->
- While working on your code, you should be frequently committing and pushing to your fork. I haven't been enforcing this, but now that we have figured out some issues with git, I will be sure to check it this time.

## Goals
The first goal of this work is **Basic Data Processing**, which involves processing of CSV files and text files. You should build two DataFrame objects: `essay_df` and `prompt_df`.

Building `essay_df` ([see screenshot](https://github.com/Data-Science-for-Linguists-2020/Home/blob/master/etc/hw2_df1.png)):

1. Start with `index.csv` and build a DataFramed named `essay_df`. Specifics:
	- Rename `'Language'` column name to `'L1'`, which is a more specific terminology.
    - Likewise, change `'Score Level'` to `'Proficiency'`. Single-word column names are more handy. (Why?)
1. Augment the `essay_df` DataFrame with an additional column named `'Partition'` with three appropriate values: 'TS' for testing, 'TR' for training, and 'DV' for development.
	- This information you can get from the three additional CSV files, which split the data into thee partitions: training, testing, and development sets.
1. Create a new column called `'Text'`, which stores the string value of each essay content. You will need to find a way to read in each essay text stored as individual files.
1. As you work on EDA and linguistic analysis, you may create additional columns to hold new data points. I'll leave these up to you. Initially, the DataFrame should look like the screenshot above.

Building `prompt_df` ([see screenshot](https://github.com/Data-Science-for-Linguists-2020/Home/blob/master/etc/hw2_df2.png)):

- This is a DataFrame for the prompts. (NOTE: This data is less critical for this homework, so de-prioritize or skip it if you are under time pressure.)
- It should have two columns:
   1. `'Prompt'`, whose values are 'P1', 'P2', ... 'P8'.
   1. `'Text'`, which holds the content of each prompt as a string.
- Additionally, the row index should be set to the `'Prompt'` column. See the screenshot above.

<br>
The second goal is **Exploratory Data Analysis (EDA)**.

1. Read up on documentation in order to gain understanding of the data set. There is a README file, a PDF document, and the [LDC publication page](https://catalog.ldc.upenn.edu/LDC2014T06). What is the purpose of this data, what sort of information is included, and what is the organization?
1. Then, explore the data to confirm the content. For example, the PDF document contains tables illustrating the make-up of the data and various data points. Don't take their word for it! You should find a way to _confirm_ and _demonstrate_ these data points through your code.
1. **Visualization**: Try out at least one plot/graph.

The third and last goal is **Linguistic Analysis**. In particular, we want to be able to highlight quantitative differences between three learner groups: low, medium and high levels of English proficiency. Explore the following:

1. **Text length**: Do the groups as a whole write longer or shorter responses? <br>
   → Can be measured through average response length in number of words
1. **Syntactic complexity**: Are the sentences simple and short, or are they complex and long? <br>
   → Can be measured through average sentence length
1. **Lexical diversity**: Are there more of the same words repeated throughout, or do the essays feature more diverse vocabulary? <br>
   → Can be measured through [type-token ratio](http://www.lexically.net/downloads/version5/HTML/index.html?type_token_ratio_proc.htm) (with caveat!)
1. **Vocabulary level**: Do the essays use more of the common, everyday words, or do they use more sophisticated and technical words? <br>
   → a. Can be measured through average word length (common words tend to be shorter), and <br>
   → b. Can be measured against published lists of top most frequent English words.

There are five total measurements. Choose three if you are relatively new to programming; experienced programmers should work on four or all five. Importantly, you must employ **statistical tests** such as the **t-test** or **one-way ANOVA** to demonstrate whether or not a difference is significant.

Additional pointers on analysis: If you haven't taken [LING 1330 "Introduction to Computational Linguistics"](http://www.pitt.edu/~naraehan/ling1330/schedule.html), you might want to learn about NLTK's core text processing functions from [these slides](http://www.pitt.edu/~naraehan/ling1330/Lecture8.pdf). Additionally, if you are going for 4b., which is the most involved kind of task, you might want to consult [this homework](http://www.pitt.edu/~naraehan/ling1330/hw5a.html) or [this one](http://www.pitt.edu/~naraehan/ling1330/hw5b.html). (Thanks Na-Rae!)




## Your report, aka Jupyter Notebook file

- At the top of your Jupyter Notebook should be a markdown cell with your name, email and date.
- The second cell, another markdown cell, should contain a brief summary of the data set. This is just a starting point though -- probing and exploring the data set should be done throughout your report.
- Don't forget to make use of markdown cells for organization, explanation and notes. Use comments as you see fit.
- Remember: your Jupyter Notebook should be much more than a Python script: you should treat it as a written project report with embedded Python code. That means, producing correct numbers is not enough: you should provide your own interpretation of these numbers as part of your linguistic analysis. Also important: you should _show_ your data and your process, so your Notebook is easy to follow.
- Your report should have at least these three main sections. See the "Goal" section about contents.
   1. **Basic data processing**
   1. **Exploratory data analysis (EDA)**
   1. **Linguistic analysis**


## Submission

1. When you think you are finished, "Restart & Run All" your Jupyter notebook one last time, so the output is all orderly and tidy. Save the file.
1. After the usual local Git routine, push to your own GitHub fork one last time. Check it to make sure your file is there and everything looks OK.
1. Finally, create a pull request for me.

This is NOT rolling submission. The original repo is private, meaning only our class members have read access. Your fork will automatically become private for your access only. I will wait until the assignment deadline to merge in your pull requests, which means your homework will essentially be visible to yourself only until I process your pull request.
(ADDENDUM: Turns out there was a loophole. A pull request and its content, even those from a private fork, are visible to everyone who has read access to the original upstream repo. We are changing the submission method starting from HW3.)
