# Term Project Guidelines

Jump to: [Components](#components), [Submission](#submission), [Milestones](#milestones), [Project Ideas](#ideas), [Project Plan](#plan), [1st Progress Report](#prog1), [2nd Progress Report](#prog2), [3rd Progress Report](#prog3), [Presentation Guidelines](#presentation), [Final Project Submission Guidelines](#final).

Individual students will work on a project of their own choice and design over the course of the semester, culminating with a class presentation followed by a final project delivery. The goal of this project is to make a linguistic discovery through application of data-intensive methods.

<a name="components"></a>
## Components

A project consists of three main components: data, analysis, and presentation.


### A. Data

> **Start with found data**. Many linguistics research projects begin with a targeted data collection effort -- field work, surveys, elicitation, human subjects, and more. But the underlying assumption of data science is that data exists in the wild, and it is up to a data scientist to harness it. True to this assumption, we will have you start with data that is found in the wild, be it published data sets, corpora, or social media streams.

> **Add value**. You should not, however, be content with data as it is packaged and presented to you. In many cases, your data will need a lot of work -- sourcing, cleaning up, and reorganizing. In other cases, you may be dealing with published data that's more or less ready for analysis. You are, then, expected to _add value_: augmenting, annotating and leveraging multiple data sets are all potential avenues.

> **Follow best data practices**. Throughout this semester, we will be learning about best data practices, both emerging and firmly established in data science circles. Make sure your own data efforts and the output are in compliance.

### B. Analysis

> **Linguistic analysis**. You will have designed your data with a research question in mind. Your data should make a suitable empirical basis for your linguistic inquiry; your research question should be properly motivated and addressed in a theoretically and methodologically sound manner. You interpretations of the findings should likewise be rigorously supported by your data. Even with meticulous preparation, however, your data in the end may not prove fruitful grounds for your original research question. Pivoting is therefore allowed up to a certain point; whether or not this move is ultimately successful, reasons for pivoting and/or failure of the original research agenda must be thoroughly probed and documented, since this sort of outcome is all part and parcel in research efforts deeply grounded in real-life data and, further, provides valuable insight.

> **Computational methods**. In your linguistic analysis, you are expected to employ various computational methods including natural language processing, statistics, machine learning, topic modeling and more. Proper techniques should be used in accordance with your research question and the specifics of your data. At the same time, you should demonstrate mastery of these techniques by justifying your choice of computational methods and thoroughly evaluating the outcome, rather than blindly applying them and accepting the returned output. As with linguistic analysis, failed experimentation should not be brushed aside, but rather receive proper investigation and documentation, as this is all part of the discovery process.


### C. Presentation

This component encompasses all audience-facing aspects of your project, which include but are not limited to:

- Proper use of GitHub as a project-hosting and publication platform.
- Overall documentation.
- Structure, readability and organization of your Python code in the form of Jupyter notebooks.
- Visualization through graphs and plots.
- Your oral presentation, scheduled in the last two weeks of class.
- Your final report: language, content, clarity, precision, organization, citation, etc.

**Weight distribution**. Ideally, a project will have the three components in perfect balance: a total of say 180 points will be equally split between data/analysis/presentation as 60-60-60. In reality, everyone's project will be different: some will have ambitious and challenging data curation plans, while others might wish to focus their efforts on extensive use of advanced computational methods. To accommodate this, a limited amount of trade-off is provisioned between the "data" and the "analysis" components: more data-focused projects therefore may have up to 70-50-60 distribution with more data-side contribution, while projects heavily focused on analysis are allowed to go easier on data-related efforts, with up to 50-70-60 split.


<a name="submission"/></a>
## Submission

Your project should be initiated and developed in the form of a GitHub-hosted public repository. The final deliverables should include:

- A README document and a LICENSE document accompanying your GitHub repository.
- A written report containing a summary of your data and linguistic analysis.
Anywhere between 5 and 10 pages, of which a minimum of 3 pages must be devoted to written descriptions (not including charts, graphs, examples, tables, etc.).
- Your data.
- Python scripts in Jupyter Notebook form, that you created and used to process, explore and analyze the data.
- Slides or other materials you used for your in-class presentation.


<a name="milestones"/></a>
## Milestones

The term project carries a total of 400 points, which you accrue over the course of the semester through meeting several, structured, milestones. Refer to the [Schedule page](https://github.com/Data-Science-for-Linguists-2020/Home/blob/master/schedule.md) for the dates.

<!--
<table class=grey style="table-layout: fixed;">

<col style="width: 24px;"/>
<col style="width: 150px;"/>
<col style="width: 40px;"/>
<col style="width: 205px;"/>
<col />
-->

<table>

<!--
<tr><th></th><th>Milestone</th><th>Pts</th><th>Distribution: Data <font color="blue">&#9401;</font>; Analysis <font color="red">&#9398;</font>; Presentation <font color="limegreen">ⓟ</font></th><th>What</th></tr>
-->

<tr><td></td><td>Milestone</td><td>Points</td><td>Distribution: Data <font color="blue">&#9401;</font>;<br> Analysis <font color="red">&#9398;</font>; Presentation <font color="limegreen">ⓟ</font></td><td>What</td></tr>

<tr><td>1</td><td><a href="#ideas">Project ideas</a></td><td>20</td>   
<td><font color="blue">&#9401;&#9401;</font><font color="red">&#9398;&#9398;</font></td>
<td>Send instructor 1-2 project ideas. </td></tr>

<tr><td>2</td><td><a href="#plan">Project plan</a></td><td>20</td>   
<td><font color="blue">&#9401;</font><font color="red">&#9398;</font><font color="limegreen">ⓟⓟ</font></td>
<td>Finalize project plan, create a GitHub project repository.</td></tr>

<tr><td>3</td><td><a href="#prog1">1st progress report</a></td><td>40</td>
<td><font color="blue">&#9401;&#9401;&#9401;&#9401;&#9401;&#9401;</font><font color="red"></font><font color="limegreen">ⓟⓟ</font></td>
<td>Focus on data curation, report progress.</td></tr>

<tr><td>4</td><td><a href="#prog2">2nd progress report</a></td><td>40</td>
<td><font color="blue">&#9401;&#9401;&#9401;&#9401;</font><font color="red">&#9398;&#9398;</font><font color="limegreen">ⓟⓟ</font></td>
<td>Continue with data curation, attempt analysis.</td></tr>

<tr><td>5</td><td><a href="#prog3">3rd progress report</a></td><td>40</td>
<td><font color="blue">&#9401;&#9401;</font><font color="red">&#9398;&#9398;&#9398;&#9398;</font><font color="limegreen">ⓟⓟ</font></td>
<td>Data-side effort should be done; ramp up analysis.</td></tr>

<tr><td>6</td><td><a href="#presentation">Project presentation</a></td><td>60</td>
<td><font color="blue"></font><font color="red">&#9398;&#9398;&#9398;&#9398;&#9398;&#9398;</font><font color="limegreen">ⓟⓟⓟⓟⓟⓟ</font></td>
<td>Oral presentation of your work in classroom.</td></tr>

<tr><td>7</td><td><a href="#final">Final project submission</a></td><td>180</td>
<td>
<font color="blue">&#9401;&#9401;&#9401;&#9401;&#9401;&#9401;</font><font color="red">&#9398;&#9398;&#9398;&#9398;&#9398;&#9398;</font><font color="limegreen">ⓟⓟⓟⓟⓟⓟ</font>
<font color="blue">&#9401;&#9401;&#9401;&#9401;&#9401;&#9401;</font><font color="red">&#9398;&#9398;&#9398;&#9398;&#9398;&#9398;</font><font color="limegreen">ⓟⓟⓟⓟⓟⓟ</font>
</td>
<td>Turn in final project in the form of a GitHub repository.</td></tr>

</table>

**_More detail will follow as each milestone approaches._**


<a name="ideas"/></a>
## Project Ideas

You should come up with one or two project ideas. Include these details:

- A working title.
- A brief summary.
- The DATA portion. Example points you should address: What will your data look like? What sorts of data sourcing and cleaning up effort will be involved? Do you have a sense of the overall data size you should be aiming for? Do you have an existing data source in mind that you can start with, and if so, what are the URLs or references?
- The ANALYSIS portion. Example points you should address: What is your end goal? What linguistic analysis do you have in mind? Any hypothesis you will be testing? Are you planning to do any predictive analysis (machine learning, classification, etc.), and using what methods?
- The PRESENTATION portion. We don't expect a whole lot of variability on this, but describe anything noteworthy you have in mind.

**Submission**: In the `project_ideas/` directory of `Class-Exercise-Repo`, create a markdown-formatted text file named `project_ideas_YOURNAME.md`. Commit, push to your fork, and create a pull request for the instructors.



<a name="plan"/></a>
## Project Plan


Launch your project as a GitHub repository and publish a project plan.

- Create a repository within our [GitHub class organization](https://github.com/Data-Science-for-Linguists-2020).
   - Give it a descriptive name that is not too long. Good choice: "Inaugural-Address-Analysis", bad: "Jevon-Term-Project".
   - Provide a description. This is a short tagline that appears under your repo title. Start with something simple. Make sure your name is in there. (See the two screenshots above.)   
   - The repository should be public.
   - Initialize with a README.
- This is YOUR repo! No forking necessary: just clone it and get to work.
- Your repo should have the following files:
   - `README.md`: Include your name, project title, and a brief summary here. We'll keep this page minimal for now.
   - `LICENSE.md`: You will eventually need to specify a license for your project. Build it now as a place holder.
   - `project_plan.md`: This is your project plan. Start with your project ideas document and polish it up.
   - `progress_report.md`: This is where you will log your progress. Add your first entry.
   - `.gitignore`: Include the usual files and directories to be ignored.
- Can't wait to get started? Read the following.
   - You are welcome to put other directories and files in your local repo as you see fit, but do NOT commit them to Git yet. Reason: once anything is on Git and GitHub, it's always there (i.e., recoverable) as part of the commit history.
   - Likewise, don't commit your data files yet. You are likely unsure at this stage whether or not you have the rights to share the data freely.
   - A suggestion: create a directory called `private/` where you will keep any private notes and data files. Add this directory to your `.gitignore` file.
   - Having said that, don't be afraid to publish changes to your GitHub repo on an ongoing basis. The instructors have access to your repo's state at any given point in time, so there is no need to keep your repo pristine & frozen until a grade is posted.

<br>
**Submission**: Your project repo counts as your submission.




<a name="prog1"/></a>
## 1st Progress Report

For the 1st progress report, **focus on your data**. This milestone consists of 30 data points and 10 presentation points. Goals:

- Attempt and mostly complete the data acquisition process.
- Start and make headway into cleaning and reorganizing your data.
- By now, you should have concrete ideas on the "data end game": what your data's final form will be like, the target total size, format, etc.
- Devise a couple of options regarding the "sharing plan" of your data.

Contents:

1. `progress_report.md`
    - Create a section entitled "1st Progress Report", and then provide a summary of what you accomplished. Keep it short (a screen-full), and provide links to related documents, including your Jupyter Notebook and data samples.
	- Include a subsection where you outline a couple of options (or a single option, if you are fairly sure) regarding the "sharing plan" for your data. You should plan out how much and what you will be sharing. Make sure to include a justification.
1. A python script in the form of a Jupyter Notebook.
   - Provide an overview of your data. Clearly document each step of your data processing pipeline.
   - Compile some basic stats on your data: the size and the make up are the bare minimum.
   - Bullet points have their uses, but let's see some written summaries and explanations too.
   - Remember: your Jupyter Notebook file is also your presentation. Make it easy for the instructors and your classmates to understand what you are doing. Explain your goals, show your data and your processes.
1. _Some form_ of your data. If all of your data is currently stored in a git-ignored directory, make an appropriately sized samples available in a directory called `data_samples/`.


Above are the minimum requirements, but do feel free to impose additional organization as you see fit. This is your project after all! But when you do so, make sure you provide an explanation.

<input type="button" class="button" onclick="return toggleMe('startover')" value="Need to start over?" >
<div class="hint" id="startover">
Some of you may have discovered that your project is not panning out as you had hoped and you need to start over. This is your last chance to do so; you will have to launch a viable project quickly. As far as your project repository is concerned, you should keep the old one (along with its Git history) but alter it to fit your new project:
<ul>
<li>Change your GitHub repository's name. That changes its URL, so you will need to update your local Git's remotes setting.</li>
<li>In your <code>project_plan.md</code> file, round up the old content into a section and mark it clearly as your old plan which is no longer current. On the top, write out your new plan.</li>
<li>Upate your <code>progress_report.md</code> file with an explanation of what happened and why this change of course was necessary. You'll need your 1st progress report too.</li>
<li>You should edit <code>README.md</code> and any other files accordingly to fit your new project direction. They shouldn't contain references to your old plan.</li>
</ul>
</div>  

**Submission**: Your project repo counts as your submission.

<a name="prog2"/></a>
## 2nd Progress Report

For the 2nd progress report, **ease up your focus on data** and start working on **analysis**. This milestone consists of 20 data points, 10 analysis points and 10 presentation points. Goals:

- Complete your the data acquisition process.
- Be mostly done with cleaning and reorganizing your data. It should be more or less in its final form.
- The overall format, shape and size of your data should be known at this point. Document them.
- Finalize the sharing scheme of the "found" portion of your data, and get your overall data into a sharable form.
- Finalize the license for your data and project.
- Start bringing in the analysis part into your project. In particular, your manipulation of data should be shaped by the linguistic analysis you are after.

As for the progress report itself, these should be the content:

1. Your **progress report**: `progress_report.md`
   - Create a section entitled “2nd Progress Report”, and then provide a summary of what you accomplished. Again keep it short (a screen-full), and provide links to related documents, including your Jupyter Notebook and other folders/documents.
   - Include two subsections:
       - Sharing scheme for the "found" portion of your data. You had already made some tentative plans as part of the previous progress report; you are finalizing the scheme here.
       - Your decision on licensing for your project and reasons/justification. See "Your license" item below.

1. Your code, in **Jupyter Notebook** form. You have three options:
   - EXISTING: the existing script file which was part of your 1st progress report. You continue to update and add to it.
   - NEW REPLACEMENT: a whole new script file that replaces the earlier one. The script you submitted earlier as part of the 1st progress report is now regarded as initial exploration and is no longer part of your work pipeline.
   - NEW CONTINUING: a new script file that's part of a pipeline. The earlier script you submitted for the 1st progress report accomplishes PART 1 of your work pipeline, and this new file is PART 2 that picks up where PART 1 left off.
   - On top of your script, specify which type it is so we will have a sense of how the script fits in your project. Make a note of this in your progress report section as well.

1. Your **data**: include it in a designated folder. Suggested name: `data/`. Be careful not to commit anything that you cannot publish.
   - If including the found portion of your data in its entirety, make sure it's within your right to do so. Present a justification in progress report.
   - If you are including samples, make sure it's within fair use. Document your sampling method and justification in progress report.
   - Are you including derived data? Again provide justification.
   - Are you including some new data you created yourself, like annotation? Again, document it.

1. Your **license**: `LICENSE.md`.
   - This is a binding licensing document, intended as audience-facing. This is where you lay out your licensing terms _for your future visitors_ wanting to _use your data and code_.
   - Do not confuse this with the license of the dataset you downloaded: this document is about YOU specifying a license for YOUR PROJECT REPOSITORY.
   - You may adopt popular, existing licensing standards: revisit Lauren Collister's materials, and consult [this quick guide](https://github.blog/2013-07-15-choosing-an-open-source-license/) and also [this one from GitHub Help](https://help.github.com/en/articles/licensing-a-repository).
   - Include reasons/justifications in the appropriate subsection in your progress report.


**Submission**: Your project repo counts as your submission.

**NOTE**: After 'submission', don't hold yourself back from pushing more updates and changes thinking you should freeze the repo until grading is done.
There's no need: the instructors have access to your repo at every stage it moves through.


<a name="prog3"/></a>
## 3rd Progress Report

For the 3rd and last progress report, you should focus on **analysis**. This milestone consists of 10 data points, 20 analysis points and 10 presentation points. Goals:
- Wrap up your data-side effort: your data is in its final form with clear documentation.
- The license for your data and project is all ready, and your data is in its ready-to-share form.
- Make headway into the analysis part of your project. You should have some preliminary findings that are either sufficiently close to what you set out to investigate, or at least meaningful enough in their own right and point to immediate next steps.

As for the progress report itself, these should be the content:

1. Your **progress report**: `progress_report.md`
   - Create a section entitled “3rd Progress Report”, and then provide a summary of what you accomplished. Again keep it short (a screen-full), and provide links to related documents, including your Jupyter Notebook and other folders/documents.

1. Your code in the form of **Jupyter Notebook**. The same three options:
   - EXISTING: the existing script file which was part of your earlier progress report. You continue to update and add to it.
   - NEW REPLACEMENT: a whole new script file that replaces something earlier. The script you submitted earlier as part of the 1st progress report is now regarded as initial exploration and is no longer part of your work pipeline.
   - NEW CONTINUING: a new script file that's part of a pipeline. The earlier script you submitted for a previous progress report accomplishes PART 1 of your work pipeline, and this new file is PART 2 that picks up where PART 1 left off.
   - On top of your script, specify which type it is so we will have a sense of how the script fits in your project. Make a note of this in your progress report section as well.

1. Your **data**:
   - Some of you have worked on your data files. Make sure to note it in your progress report.
   - Are your data files finished as of last progress report? No new changes since? If so, make a note of it in your progress report.

1. `README.md` file:
   - We'll give this file a proper structure in due time, but for now, put a link to your guestbook, so you'll have a handy link.    

**Submission**: Your project repo counts as your submission.


<a name="presentation"/></a>
## Presentation Guidelines

#### Format
- Your presentation will consist of two parts: a ~20 minute recorded presentation using PowerPoint or an equivalent; and a ~5 minute condensed summary in class on Thursday, April 16th.

#### Content
- Your project, of course! But unlike your project itself that dives right into data, you should start with **motivating and contextualizing your project topic**. That means supplying background information, research questions, theoretical foundations and related literature, and so on.
- And, be sure to **show** your data and findings through visualization. All the nifty plots and charts you have been generating can be saved as an image file, which you can incorporate into slides.
- Make sure to include an analysis as the central focus.

#### Evaluation
- Your presentation carries a **total of 60 points**, with 30 points based on analysis and the remaining 30 on the presentational aspect.
- Overall, it will be evaluated based on the following: accuracy and depth of content, originality, presentation, and delivery.

<!--
If you are presenting in Week 14, I will take into consideration that your analysis part may be slightly less developed.
-->


<a name="final"/></a>
## Final Project Submission Guidelines

You've worked hard through many project milestones, and it's time to prepare your project for final submission. Unlike the three progress reports where the focus was firmly on the process, the final submission should highlight the results and your interpretation of them. The process should still get a fair and clear illustration, but you should prune out from your production code any "branches" representing trials-and-errors that led to a dead end. (You are encouraged to move any old code bits into a designated subfolder.) All in all, your GitHub repo should present a coherent picture of your project, from start to finish.

#### Your repo: files and folders

(Note: Objects that are entirely/substantially new in this submission are in <span style="color:blue">blue</span>.) Below are the required files with fixed file names:

- LICENSE.md
- project_plan.md
- progress_report.md
- <span style="color:blue">README.md</span> (Details below)
- <span style="color:blue">final_report.md</span> (Details below)

In addition, you should have:
- A designated folder for your data, and data files inside
- <span style="color:blue">A designated folder for figures, graphs and other image files</span> (Details below)
- Jupyter Notebook files (Details below)
- <span style="color:blue">Your presentation slides</span>, saved in a PDF format

Lastly, some of you might have extra files and directories serving some purpose. Perhaps a folder containing some old code that is no longer relevant, or something like that. Make sure to explain what these are in your `README.md` document.

#### README.md

Revamp your README document and give it a proper structure. This document is what greets your visitors, so its goal should be to give them a short but proper orientation. It should include:

- Front matter: the title of your project, your name, email, date
- A brief description of your project
- A brief description of the "found" data set you started your project with. Include a web link (if any) along with proper attribution.
- A "directory" of your repo. Have a bullet-point list of the files and folders along with a one-line description of what they are. Make them into clickable links so your visitors can easily navigate to the files/folders.
   - For your Jupyter Notebook files, provide a link to the nbviewer's version in addition to the usual GitHub view. You can do this by prefixing `https://nbviewer.jupyter.org/github/` instead of `https://github.com/`. [Example](https://github.com/Data-Science-for-Linguists-2020/Home/blob/master/Notebooks/regression_intro.ipynb) [here](https://nbviewer.jupyter.org/github/Data-Science-for-Linguists-2020/Home/blob/master/Notebooks/regression_intro.ipynb)
- Do NOT list individual data files or image files under a subfolder.
- A link to your visitor's log.

#### Images folder and files
Your `final_report.md` file will need figures and graphs for illustration.
- Have a folder, named `images` or something, where all image files should go.
- Plots can easily be exported. [See here](https://pythonspot.com/matplotlib-save-figure-to-image-file/). Alternatively, they are automatically exported as .png files during Jupyter Notebook --> Markdown conversion.
- With other types of objects, say trees, see if you can export them as an image file. As a last resort, you may use screenshots, but **only as a very last resort**.

#### Your code: Jupyter Notebook
The same usual guidelines for your Jupyter Notebook files continue to apply: your code should work correctly while walking the audience through the whole process. This time around, however, your code should be in a streamlined form: you should prune your code of any unsuccessful bits and experiments that have since been abandoned. In other words, your code files should demonstrate your project in a lean and coherent manner. Some important points:

1. For many of you, breaking down your code into multiple Jupyter Notebook files will make organizational sense. For example, the first notebook could focus on data clean-up effort, and the second one takes from there and conducts data analysis, and so forth.
1. Still, your Jupyter Notebook file will get long and unwieldy, which makes scrolling a pain. So please include a table of contents with shortcuts to various subsections.
1. Your code may produce interim outputs (such as saved pickle files). If you decide against sharing them, make sure to exclude them from GitHub repo via `.gitignore`.
1. Make sure to "Restart & Run All" your Jupyter Notebook file before pushing to your GitHub repo! You want all cell outputs to be tidy.

#### final_report.md
Think of this as a usual "final report" that is in a markdown format instead of MS Word. Details:

- Shoot for around 1,500 words, excluding references if any. That's the length of a short paper of about 4-5 pages. (Remember to use the `wc` command!)
- Use headers and clearly mark your sections.
- Use visualization! Display figures you had saved as external image files.
- Link to relevant parts of your Jupyter Notebook. As explained above, you should reference sections of your code on jupyter.org's nbviewer.
- What should you include in this report? Revisit the [overall description of the term project](#components) at the top of this page.
- Have a paragraph devoted to the overall history and process of your project, warts and all. Document setbacks, false starts, and other difficulties you experienced.

**Submission**: Your entire project repo is your submission. Make sure everything is in order and looks good. It is due at the end of April 24 (Fri), meaning 11:59pm.
