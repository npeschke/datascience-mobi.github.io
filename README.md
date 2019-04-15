---
title: "Data Analysis - MoBi SS2019"
author: "Carl Herrmann"
date: "15/04/2019"
#output: github_document
output:
  rmdformats::readthedown:
    highlight: kate
    keep_md: true
---


----------

## Presentation

The goal of the Data Analysis Module in the Summer Semester is to provide **hands-on experience** in data analysis of large scale datasets and get first insights into using computational tools to provide a reproducible data analysis.

After this module, you will have

* gained skills in programming language such as R or Python (depending on the chosen project)
* learn to use tools to perform reproducible analysis, like Markdown/Notebooks and GitHub
* understand the key steps in a large-scale data analysis

----------

## Topics

We have defined **5 topics** in data analysis; each topic will comprise **5 different projects**. Most of the times, these 5 projects are very similar to each other but analyze slightly different datasets.

You can find a description of the 5 topics here:

1. [Genetic interactions in cancer](https://github.com/datascience-mobi/01-genetic-interactions-in-cancer)
2. [Cellular response to drug perturbations](https://github.com/datascience-mobi/02-cellular-response-to-drug-pertubations)
3. [Biomedical image analysis](https://github.com/datascience-mobi/03-biomedical-image-analysis)
4. [K-means programming](https://github.com/datascience-mobi/04-kmeans)
5. [Cancer genomics](https://github.com/datascience-mobi/05-cancer-genomics)

You will find a description of the projects an a list of supervisors/tutors in these description files.

**Important information**:

* Topic 1,2,5 are data analysis topics/projects which will be conducted in R
* Topics 3,4 are rather *programming projects*, which require some more advanced programming skills, and will be done in Python.

----------

## Rules

### How do I select my project/team?

* each project will be worked out by groups of **4 students**. 
* the choice of project and definition of the teams should be completed by **Wednesday, 24th April** (no extension!)
* once the choice has been made, register your team in the Google Sheet (URL provided during the first presentation)

### Who will help me?

For each topic, there will be a **master tutor** assigned to this topic. Each team will have **a weekly meeting** with his tutor on **Wednesday between 10am and 1 pm** during 20-30 minutes.

Meeting places will be:

* BioQuant Seminar room SR042 / SR044
* BioQuant meeting lounges (ground floor, red sofas)
* IPMB meeting room 5th floor (behind the CIP room)

### What am I supposed to do?

1. select your project and you teammates and register **before Wednesday, 24th April**
2. **Project presentation on Wednesday, 15th May**: prepare a 10 minutes presentation based on the indicated literature for each project, listing the relevant questions/topics that you want to adress in your project. During this presentation, you should also explain the datasets you will be working with, and how you want to make use of them. 
3. **Midterm-presentation Wednesday 19th June** (15 minutes)
4. **Final presentation Wednesday 24th July** (20 minutes)

### How will I be evaluated?

Each student will have an individual evaluation! This will take into account the *3 presentations* listed above, as well as the report (markdown report / jupyter notebook depending on the projects).

During the oral presentations, each student will be asked to explain part of the analysis, especially to explain the code! So everyone should make sure to be involved in the project.

Reports will be submitted (or "committed") to the Github repository of the group as a `.Rmd` or `.ipynb` file.

**Important note**: *Science is collaboration!* so please make sure to share your insights/knowledge with other groups! You are free to choose whatever way to do so, e.g. Whatsapp groups or [Slack groups](https://slack.com/intl/de-de/).

----------

## Practical aspects

Depending on the projects, you will use either R (Topics 01/02/05) or python (Topics 03/04). 

### R-based projects

You will use [RStudio](https://www.rstudio.com/), and create a [R markdown document](https://rmarkdown.rstudio.com/). These will consist in a mixture of plain text (explanations about the analysis, comments,...) and code pieces (called `chunks`). The advantage is that the report will be automatically generated (either as pdf or html document) when compiling the markdown file. All plots will be automatically and dynamically created from the code pieces in the markdown document.

### Python based projects

Similar to R markdow documents, the [Jupyter Notebook](https://jupyter.org/) offers a way to mix markdown text together with Python code. Installing Jupyter Notebook requires the installation of Python. Just follow the instructions on the previous link.


### GitHub

Git is a system to handle collaborative projects, in which each member of the team is contributing to the project. You can check [this website](https://guides.github.com/activities/hello-world/) for a simple intro to Git/GitHub.

Git can be used either from the command line, or using [GitHub Desktop](https://desktop.github.com/), a GUI manager which makes commiting changes, etc... very easy.

This tool will help you (and us...) track the progress of your project.


