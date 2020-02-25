# Homework 3: Machine Learning with the ETS Corpus

This homework carries a total of 80 points.

For this homework, we will apply machine learning methods to the [ETS Corpus of Non-Native Written English](https://catalog.ldc.upenn.edu/LDC2014T06) data, using Python's `sklearn` library.

## Data set
- You should be fairly familiar with this corpus by now. It was published by the LDC ([Linguistic Data Consortium](https://www.ldc.upenn.edu/)). I have acquired license on behalf of all Pitt faculty and students. I am distributing the data through the privately held "Licensed-Data-Sets" repo of our class GitHub organization.
- You should have it already cloned the repo as your local repository. There's no need to fork.
- As with the previous homework, you should keep the corpus data files in its original directory location and its original form.
- NEW to HW3: you should work with a saved pickle file. See next section.

## Repo, files and folders

- We will re-use the [`HW2-Repo/`](https://github.com/Data-Science-for-Linguists-2020/HW2-Repo), which already contains your previous work on the ETS data. Like before, your files should be in your designated folder, say jevon/.
<!-- - I am providing a starter script for this homework. Copy it into your personal directory, rename it, and then work on it. More details on this JNB file below. -->
- As before, the ETS corpus data files should remain in their original directory location. Do not move or copy them into this repo.
- NEW: You shouldn't have to start from the original ETS data files and go through the basic text processing steps every single time! We already completed these steps as part of HW2. So, assuming you have the **processed dataframes saved as pickle files** at the end of HW2, you should simply unpickle the two dataframes `essay_df` and `prompt_df`, and then go from there. See [Jevon's HW2 KEY script](https://github.com/Data-Science-for-Linguists-2020/HW2-Repo/tree/master/jevon) on how it's done, then modify your HW2 to produce the pickle files. The files should be in your personal folder, alongside your JNB files.    
- Should you be committing these pickle files? Absolutely not! I have already updated the `.gitignore` file to ignore pickle (`.pkl`) files and CSV (`.csv`) files, so you should be set.
- While working on your code, you should be frequently committing and pushing to your fork. Important!



## Goals

Let's build machine learning models for the following three tasks.

1. **L1 identification**: Given a response, predict the first language (L1) of the writer
1. **Topic (= prompt) identification**: Given a response, predict the prompt for which it was written
    - This task is pretty similar to 1. above with one caveat: topic distribution is not even.
1. **Score prediction**: Given a response, predict its score
    - The targets ('low', 'intermediate', 'high') are ordinal, not nominal, categories. The question then becomes: Regression models or classification models?

The three tasks have a lot in common, but they also come with some fundamental differences that require special attention, which are noted above.

Evaluation:

1. **L1 identification**: Remember the data set itself came with its own training-test-development data partition. Use this split in your evaluation.
1. **Topic (= prompt) identification**: Use your own training-test split, in 80-20 ratio. Use random seed 0.
1. **Score prediction**: Try 5-fold cross validation.  

Plots:

- Confusion matrices in `seaborn`'s "heat map" format is an obvious choice. You should use it.
- In addition, you should try at least one additional visualization method.

Machine learning algorithms:

- Try at least two different machine learning algorithms/models for each task.

Features:

- The "bag-of-words" approach is the most basic one. You should try it.
- Try additional features. Text-based features that go beyond individual words could be interesting. How about features that are _not_ based on text: for example, will L1 be a helpful predictor for the prompt? How about the token count for the score level?

BONUS POINTS:
- Try dimensionality reduction through PCA (Principal Component Analysis) or SVD (Singular Value Decomposition).


## Your report, aka Jupyter Notebook file

It should meet the following requirements:

- At the top of your Jupyter Notebook should be a markdown cell with the homework title (use `#`), your name, email and date.
- It should have these five section headers (use `##`):
   - Load the data, recap basic stats
   - Task 1: L1 identification
   - Task 2: prompt identification
   - Task 3: score prediction
   - Summary analysis
- Those are the top-level sections (use `##`), but feel free to add your own sub-sections and other markdown cells as you see fit.
- Don't forget to make it presentable! Keep in mind that your JNB file is a written project report with embedded Python code. Don't just produce evaluation scores: your own analysis and interpretation of the numbers are the end goal.


## Submission
A big change: **don't push your commits before the homework deadline**. (Reason: the moment you push to a fork, the entire content of your request becomes visible on your version of the repo.) Instead, just make sure to **commit your final, "submission-ready" version before the 12:30pm deadline**. After the deadline passes, go ahead and push to your origin, then submit a pull request. You can do this at the beginning of the class too.
