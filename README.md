---
title: "Data Analysis - MoBi SS2020"
author: "Carl Herrmann"
date: "22/04/2020"
#output: github_document
output:
  rmdformats::readthedown:
    highlight: kate
    keep_md: true
---


----------

## Presentation

Responsible teacher: 

#### Carl Herrmann
#### carl.herrmann@bioquant.uni-heidelberg.de
#### [Health Data Science Unit - Medical Faculty Heidelberg](http://www.hdsu.org)


The goal of the Data Analysis Module in the Summer Semester is to provide **hands-on experience** in data analysis of large scale datasets and get first insights into using computational tools to provide a reproducible data analysis.

After this module, you will have

* gained **skills in programming language** such as R or Python (depending on the chosen project)
* learn to **use tools to perform reproducible analysis**, like Markdown/Notebooks and GitHub
* understand the **key steps in a large-scale data analysis**

----------

## News

We will provide news and deadlines under this section.

## Projects

We have defined **4 projects** in data analysis; each project will comprise **5 different sub-projects**. Most of the time, these 5 sub-projects are very similar to each other but analyze slightly different datasets.

You can find a description of the 4 projects here:

1. [Hallmarks of cancer and cancer metabolism](https://github.com/datascience-mobi/01_Cancer-Hallmarks_2020)
2. [Biomedical image analysis](https://github.com/datascience-mobi/02_Image-Analysis_2020)
3. [Analysis of Cancer transcriptome](https://github.com/datascience-mobi/03_Cancer-Transcriptome_2020)
4. [Aberrant expression in metastatic lung cancer](https://github.com/datascience-mobi/04_Lung-Cancer_2020)

You will find a description of the projects an a list of supervisors/tutors in these description files.

**Important information**:

* Projects 1,3,4 are data analysis topics/projects which will be conducted in R
* Projects 2 is rather a *programming project*, which requires some more advanced programming skills, and will be done in Python.

### Online presentations

You can find the videos presenting the overall organization of the course, as well as individual presentations for each project:

* [General presentation - update 24/04/2019 (C. Herrmann)]()
* [Presentation Project 01 (C. Herrmann)]()
* [Presentation Project 02 (C. Ritter)](https://youtu.be/6DIKBiq_T3g)
* [Presentation Project 03 (C. Heyer)](https://youtu.be/7gtzjOnReC8)
* [Presentation Project 04 (A. Dugourd)](https://www.twitch.tv/videos/597324040)


### Documentation

These are the Python Notebook files with Python intro provided by David Schwarzenbacher

* [Python notebooks (D. Schwarzenbacher)](./doc/Python_Intro.zip)

----------

## How to ...

### How do I select my project/team?

1. check the project description on this page!
2. select your teammates; each sub-project will be worked out by groups of **4 students**. 
3. once the choice has been made, register your team in the [Google Sheet](https://docs.google.com/spreadsheets/d/1jZ6fissYZsaxXeWwvzSioOhV_9f4er5HUzaLABEkJEk/edit?usp=sharing) **(registration will open Friday 24.04, 10 am)**; the choice of sub-project and definition of the teams should be completed by **Wednesday, 29.04** (no extension!)
4. create a **[GitHub account](https://github.com)** and register your github name in the registration Google Sheet


### Who will help me?

For each project, there will be a **master tutor** assigned to this project. Each team within a project will have **a weekly online meeting** with his tutor on **Wednesday between 10am and 1 pm** during 20-30 minutes.

**VERY IMPORTANT**: as the weekly time which the tutor can dedicate to your project is limited, you should **carefully prepare** your meeting. We have provided a template which should help you organize your weekly meeting efficiently!

### What am I supposed to do?

1. select your project and you teammates and register **before Wednesday, 29.04, 10am**
2. go to DataCamp, and follow some of the [recommended courses in R/python](#datacamp), which will help you start with your project!
2. **Project presentation on 20.05**: prepare a 10 minutes presentation (+10 minutes discussion/questions) based on the indicated literature for each project, listing the relevant questions/topics that you want to adress in your project. During this presentation, you should also explain the datasets you will be working with, and how you want to make use of them. 
3. **Final presentation mid/end July** (15 minutes + 10 minutes discussion / questions) 

### How will I be evaluated?

Each student will have an individual evaluation! This will take into account the *2 presentations* listed above, as well as the report (markdown report / jupyter notebook depending on the projects).

Here are the relevant points taken into account during the **project proposal presentation**:

* presentation of the literature results
* understanding of the biological question
* clarity of presentation of planned analysis and milestones
* knowledge of the datasets
* teamwork aspects
* quality of the oral presentation and slides


During the oral presentations, each student will be asked to explain part of the analysis, especially to explain the code! So everyone should make sure to be involved in the project.

Final reports will be submitted (or "committed") to the Github repository of the group as a `.Rmd` or `.ipynb` file.

**Important note**: *Science is collaboration!* so please make sure to share your insights/knowledge with other groups! You are free to choose whatever way to do so, e.g. Whatsapp groups or [Slack groups](https://slack.com/intl/de-de/).

----------

## Practical aspects

Depending on the projects, you will use either R (Topics 01/03/04) or python (Topics 02). 

### R-based projects

You will use [RStudio](https://www.rstudio.com/), and create a [R markdown document](https://rmarkdown.rstudio.com/). 

#### RStudio

* For those of you who want to work on their laptops, you can install RStudio using the previous link; however, since some datasets are rather large, you will need a decent laptop to be able to process the data in a reasonable time (i5/i7 CPUs with 8Gb RAM at least)

* An alternative possibility is to use the RStudio server that has been set up on the de.NBI cloud; this requires some additional steps from your side:

#### RMarkdown documents

These will consist in a mixture of plain text (explanations about the analysis, comments,...) and code pieces (called `chunks`). The advantage is that the report will be automatically generated (either as pdf or html document) when compiling the markdown file. All plots will be automatically and dynamically created from the code pieces in the markdown document.

Have a look at [this tutorial](https://rmarkdown.rstudio.com/lesson-1.html) or [this one](https://support.rstudio.com/hc/en-us/articles/205368677-R-Markdown-Dynamic-Documents-for-R) to get started with RMarkdown; RMarkdown is very easy to generate with RStudio.

### Python based projects

Similar to R markdow documents, the [Jupyter Notebook](https://jupyter.org/) offers a way to mix markdown text together with Python code. Installing Jupyter Notebook requires the installation of Python. Just follow the instructions on the previous link.

### DataCamp <a name='datacamp'></a>

You have been provided a registration link to DataCamp; as part of this course, you get a **free, full access** to all DataCamp courses! Use it...

We recommend taking some basic courses, before you start with your project; this will help you in overcoming the initial difficulties (reading a data frame, accessing a file, ...); here are the courses we recommend taking

#### R-projects

* [Introduction to R](https://learn.datacamp.com/courses/free-introduction-to-r)
* [Intermediate R](https://learn.datacamp.com/courses/intermediate-r)
* [Cleaning data in R](https://learn.datacamp.com/courses/cleaning-data-in-r)
* [Data Visualization in R](https://learn.datacamp.com/courses/data-visualization-in-r)
* and many others, as you will progress through your project...

#### Python projects

* [Intro to python for data science](https://www.datacamp.com/courses/intro-to-python-for-data-science)
* [Intermediate Python for data science](https://learn.datacamp.com/courses/intermediate-python-for-data-science)
* [Unsupervised learning in Python](https://learn.datacamp.com/courses/unsupervised-learning-in-python)


### GitHub

Git is a system to handle collaborative projects, in which each member of the team is contributing to the project. You can check [this website](https://guides.github.com/activities/hello-world/) for a simple intro to Git/GitHub.

Git can be used either from the command line, or using [GitHub Desktop](https://desktop.github.com/), a GUI manager which makes commiting changes, etc... very easy.

This tool will help you (and us...) track the progress of your project.



