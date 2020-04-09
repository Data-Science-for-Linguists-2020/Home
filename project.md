# Term Project Guidelines

Jump to: [Components](#components), [Submission](#submission), [Milestones](#milestones), [Project Ideas](#ideas), [Project Plan](#plan), [1st Progress Report](#prog1), [2nd Progress Report](#prog2).

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
