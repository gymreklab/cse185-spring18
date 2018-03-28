# CSE185 Spring 2018 Lab Guidelines

For the first 7 weeks, we will work on a different lab assignment each week during the Tuesday and Thursday lab sessions. Lab reports are due the following Tuesday before the start of the next lab.

Each lab will require you to have access to the joint class server for data analysis and to complete a lab notebook and report using Github. Detailed instructions are given below.

## Connecting to the server
If you already have a UCSD username on `ieng6.ucsd.edu`, you should be able to log in with that. To activate a course specific account, go to: https://sdacs.ucsd.edu/~icc/index.php.

Once you've obtained a username, you can log into the server from the terminal using ssh:
```
ssh $username@ieng6.ucsd.edu
```

This will take you to your course home directory (`/home/linux/ieng6/cs185s/$username`). All materials for the course will be provided in the `/home/linux/ieng6/cs185s/public` directory each week.

If you are logging in with your UCSD username, you will need to run the `prep` command to active the cse185 course environment.

## Accessing the lab assignment on Github classroom
All lab assignments are distributed using Github classroom. Before you start, make sure you have a Github username (sign up at http://github.com).

To get up to speed on Git and Github technology, please take a look at this tutorial: https://guides.github.com/activities/hello-world/. We'll learn various Github features throughout the course.

A link to each assignment will be posted on the course homepage (https://github.com/gymreklab/cse185-spring18). To start the assignment, simply click the link. This will automatically create a new personal repository where you can complete the assignment. Your work will only be visible to you and the instructors of the course.

The repository for the week's assignment will consist of:
* Tutorial materials (CSE_WeekX_PartX.md) containing instructions for the lab.
* A (mostly blank) lab notebook file (CSE185_WeekX_LabNotebook.md) for you to fill in (see below)
* A `labreport` folder for you to upload your final lab report and any materials you used to write it. This will contain a template file `CSE185_WeekX_LabReport.md` where you can fill in the report.

You'll be responsible for filling out the lab notebook and completing a lab report each week.

## Lab notebooks
Lab notebooks are often just as important in bioinformatics as they are for bench
work. Every week in the lab, create entries in your weekly lab notebook (a markdown file in the assignment Github repository). Include the week number, date, and a short descriptive phrase about the project in each entry title. Create a separate entry for each day you do lab work. You are encouraged to take advantage of markdown syntax (e.g. to denote code, create tables, etc.).

At bare minimum, your lab notebook should include commands and code you enter into terminal, and the results of those commands if they are easily pasteable (don't paste more than 20 or so lines of text).

For commands and code, you are encouraged to include notes about commands and scripts that fail or don't do what you want them to so you can keep a record of what does and doesn't work. Certainly include any command used to generate results that you will include in your lab report so you can reproduce them. You only need to include commands and code that process or analyze data. I don't need to know that you printed your working directory or `cd`'d into a parent folder, or moved something around.

For results, include results as directed by the weekly lab project instructions, and
any additional observations, like unusual software behavior. Please include at
least enough information so that when you are writing your lab report, you can
rely on your lab notebook for the data, and won’t have to re-run your analyses. 

In addition to commands and results, include informal text that explains, in your
own words, what the commands are doing and what the results are. An outside
reader (or yourself a couple days or weeks from now) should be able to understand and reconstruct your analysis.

Feel free to include your own running commentary on what you think is going on,
as well as tips on usage and syntax. At the end of the class, you can download
your journal, and use it as a future reference. 

Lab notebooks are worth 10% of your total grade. You can earn up to 1% point
each week. You lab notebooks will be examined each week; if you don’t have
any entries, you get 0%, if you have entries but they don’t meet the guidelines
above, you’ll get 0.5% (and some comments/advice about what needs to
improve), and if you meet the guidelines above, you’ll get 1%. For the literature
review (week 7) and final project weeks, there will be specific directions for your lab notebook.

## Lab reports
For the first 6 weeks of the course, you will be writing a lab report on each week’s
project/tutorial. Each report will be graded on a 10 point scale, described at the
end of this document. Format your lab report with the sections shown below (in
the markdown document in the assignment repository each week). In addition to the content
described below, you must follow the specific guidelines found at the end of each
week's tutorial. Week 7’s report and the independent project will have their own
guidelines). In addition to the lab report itself, you may include supplementary components such as custom code used to generate results in the `labreport` folder.

* **Title**:  A descriptive title that indicates the topic of the week’s project
* **Abstract**:  In no more than 100 words, briefly summarize what was done in the lab this week, what the findings were, and why they were important.
* **Introduction**:  In 2-3 paragraphs, provide enough background information to understand the biology behind the weeks project. Be sure to state what problem or question the week’s lab work addressed, and why it is important. You must cite at least one scientific journal article for this section (it can, but doesn’t have to be, the assigned reading). When you use outside resources, use in-text citations in the text attributing any ideas or information from materials outside of our course lecture or tutorial. In-text citations give the source for information right where it is written (1). 
* **Methods**: This section should contain sufficient information so that other bioinformaticists could reproduce your results. You should briefly describe your raw data (what is it, what is the name of the reference) and describe what you did with it. You should write this in 2-3 paragraphs, not in a list. When you use a bioinformatics software program, do not write out the full command you typed, but do specify which program (ie ‘bwa-mem’ or ‘samtools tview’) you used and whether you used the default options. If you did not use the defaults, you should specify the exact settings you used. The first time you mention bioinformatics
software or an online tool, you should cite it and specify which version of the tool you used. The correct citation for most software can be found by looking up its documentation online (you don’t have to cite common tools like python or perl or the bash shell). If you write a custom script, (for example, our awk script from week 1), include that code in the `labreport` folder and reference it in your writeup.
* **Results**:  This section should include the results of your data processing and data analysis, and may include tables with read lengths, pictures of quality distributions, or tables of gene names for examples. In the text, briefly restate how you got the results in full sentences, but in less detail than the methods, before you say what the results are (ie ‘reads were mapped to the reference and scanned to identify positions that likely contained mutations. We found….’). Refer to tables and figures by number, and include a brief descriptive title for each. Be sure to include any results specifically requested in the lab project tutorial. The results section should be as objective as possible, so please refrain from interpreting the meaning or significance here. It should be just the facts. 
* **Discussion**:  In 2-3 paragraphs, explain what you think the results mean, and
why you are interpreting them this way. If you encountered any problems, or
answered questions, discuss them and suggest ways to solve them with future
experiments or analyses. Also include any information specifically requested in
the tutorial. 
* **Citations**:  You can use any commonly used format you like, but be consistent. Lab reports will be submitted via turnitin to check for plagiarism, so be sure to cite other people’s ideas, and put everything in your own words (paraphrasing) if you aren’t using direct quotes. 

### Scoring

#### Title and Abstract (1 point)
* 0 (one or both is missing)
* 0.5 (title is not descriptive OR abstract has large scientific mistakes)
* 1 (title is descriptive, abstract includes what was done and why, and the major finding(s)

#### Introduction (2 points)
* 0 (the section is missing)
* 0.5 (there are large scientific inaccuracies)
* 1 (missing 2 of: mostly correct science, a citation, clearly stated significance)
* 1.5 (missing 1 of: mostly correct science, a citation, clearly stated significance)
* 2 (has all 3: mostly correct science, a citation, clearly stated significance)

#### Methods (2 points)
* 0 (the section is missing)
* 0.5 (there is not enough to reproduce the results AND there are mistakes in analysis)
* 1 (there is not enough to reproduces the results OR there are mistakes in analysis)
* 1.5 (everything is there and correct, but style is incorrect)
* 2 (everything is there and correct, and style is correct)

#### Results (2 points)
* 0 (the section is missing)
* 0.5 (missing 3: all results from tutorial, text is clear and shows understanding, figures/tables are clear and labeled, sticks to the objective facts)
* 1 (missing 2 of: all results from tutorial, text is clear and shows understanding, figures/tables are clear and labeled, sticks to the objective facts)
* 1.5 (missing 1 of: all results from tutorial, text is clear and shows understanding, figures/tables are clear and labeled, sticks to the objective facts)
* 2 (has all 4: all results from tutorial, text is clear and shows understanding, figures/tables are clear and labeled, sticks to the objective facts)

#### Discussion (2 points)
* 0 (the section is missing)
* 0.5 (missing interpretation and/or request items from tutorial)
* 1 (interprets meaning of results, has requested items from tutorial, has large misunderstandings of science)
* 1.5 (interprets meaning of results, has requested items from tutorial, may have small misunderstandings of science)
* 2 (interprets meaning of results, has requested items from tutorial, shows strong understanding of the science)

#### Citations, spelling, and grammar (1 point)
* 0 (there are no citations)
* 0.5 (there are major spelling and grammar issues)
* 1 (there are only minor spelling and grammar mistakes)
