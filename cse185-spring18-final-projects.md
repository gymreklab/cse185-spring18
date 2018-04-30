# CSE185 Spring 2018 Final Project Guidelines

For the last three weeks of class, you will implement a bioinformatics pipeline to answer a scientific question, like we have been doing in the weekly tutorials, but this time *you will choose* the data and design an appropriate analysis pipeline. 

Your project will consist of identifying a dataset and a scientific question to answer. A few ideas for choosing a dataset and question:

* Re-analyze a published dataset to reproduce the result presented in the original paper but using a modified approach.
* Re-analyze a published dataset to answer a different biological question than the original paper.
* Compare software performance of different tools on the same dataset.

Your dataset must meet the following requirements:

* It must be *publicly available*.
* Data must be less than 2GB total so you can analyze it on `ieng6`.
* You cannot choose data we've already analyzed in class.
* While the most obvious choice is to analyze sequencing datasets available on SRA, other types of data are possible. If in doubt, ask an instructor for advice.
* Your project/data must be somewhat related to a class of methods we've covered in class. This is open to interpretation. Again if in doubt, ask an instructor.

The remainder lab sections on Tuesdays and Thursdays will be devoted to working on the projects. You are encouraged to come in and work during the class time, and attendance will still be taken. Take advantage of the instructors as useful resources during this time.

Like the lab assignments, projects will be completed on Github. A project link will be posted during week 8. During the project period, you are still expected to maintain a lab notebook as part of this repository. At the very least, you should have one entry per lab class period. You can document what you've tried, notes about datasets and ideas, and eventually the commands you're using to tackle your biological questions.

This project is worth 15% of your final grade, broken down as follows:

# Project Proposal (3%)
<a name="proposal"></a>
**Due Tuesday, May 29 11:00am**

No more than one page total, with a title and 3	sections, as described below:

### Biological Question
1 paragraph describing the scientific question you are trying to answer. no citations are required for the proposal.
### Dataset
1 paragraph describing the dataset used, which must meet the requirements specified above. Your description must include:

* A description of what the data is (e.g. whole genome-sequencing, RNA-seq, the library set up, which organism, etc.)
* The accession numbers (e.g., SRA numbers)
* Data file sizes and formats
* Publications linked with the data

### Bioinformatics pipeline
1 paragraph *briefly* summarizing how you plan to analyze the data. It is ok if you don't have every single detail yet. However, for your final report, your pipeline:

* Must use at least 5 different software tools that contribute to the analysis. Downloading data soes not count, nor do sub-commands within a single piece of software or trivial commands (e.g. `cp`).
* One of the software tools must be either: (1) a tool we haven't used in class, which you either install yourself or use a web version of or (2) an executable script (not just plotting) that you wrote for this project.

### Proposal scoring

Proposals are scored out of 6 points:

* 1pt: Title, spelling, and grammar
* 2pts: data meets guidelines above
* 2pts: scientific question is clearly stated and makes sense to analyze using the chosen dataset
* 1pt: Proposed pipeline seems plausible to complete in 2 weeks and demonstrates thought

# Lightning Talk (2%)
<a name="lightning"></a>
**Sign up to present either Wednesday May 30, Monday June 4, or Monday June 6**

A 60 second presentation to the class about what you’ve been working on. Include your project plans and any progress you’ve made. You must include one informative slide, and one slide with a clicker question for the class. You can ask a quiz question about your topic, for advice for your project, or for predictions about what your results will show. 

## Lightning Talk scoring

Talks are out of 4 pts:

* 1 pt: Talk is within tim (practice with a timer to make sure you're under 60 seconds!)
* 1 pt: Has informative slide AND clicker slide
* 2pts: Good summary of proposed work & any progress

# Project Report (10%)
<a name="report"></a>
**Due Friday, June 8 11:59pm**

Project resports will be structured the same as a regular lab report, with the following additional guidlines:

* Your abstruct must include what you did, why you did it, and a brief summary of the results.
* You must cite at least 4 scientific journal articles in your introduction. Your intro should explain the biological question, what is already known about it, and its significance.
* Make sure your methods section cites the bioinformatics tools you used, as well as the version of each tool.
* Methods section should be written in the past tense describing what you did.
* Make sure your results are written in paragraph form and all figures/tables are referred to in the text. You may choose to break up your results section with subheadings.
* If you write your own scripts, please include those in the Github.

## Project scoring:

Project reports will be out of 20 points:

* Title and Abstract: 2 points

(1 pt) Title is descriptive enough to understand the project

(1 pt) Abstract includes the 3 components stated above

* Introduction: 4 points

(1 pt) Explain current scientific knowledge related to the biological question

(1 pt) Explain importance of the biological question

(2 pts) Shows strong understanding of the science

* Methods: 4 points

(1 pt): Style is correct (uses past tense, tells what was done)

(1 pt): There are sufficient details to reproduce the analysis

(1 pt): There are at least 5 software tools

(1 pt): One of the tools is either new to the class or is a new script

* Results: 4 points

(1 pt): Style is correct (describes key observations in paragraph form, sticks to the facts)

(1 pt): Figures are well labeled and easy to understand

(1 pt): Results contribute to answering the biological question

(1 pt): Results document processing steps from methods (i.e. reads that pass each step)

* Discussion: 4 points

(1 pt): Interprets meaning of results in terms of the original biological question

(2 pts): Shows a strong understanding of the science

(1 pt): Makes a suggestion for further research or a different approach

* Citations, spelling, and grammar: 2 points

(1 pt): Has minimum required citations (4 for intro, tools used in methods)

(1 pt): Has only minor spelling and grammar mistakes
