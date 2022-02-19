# How-to-do-Repeated-Measures-ANOVAs-in-R

The details of the codeset and plots are included in the attached Microsoft Word Document (.docx) file in this repository. 
You need to view the file in "Read Mode" to see the contents properly after downloading the same. We have used Psycho package
with this repository. Below are the details about the same.

Goal
======
The main goal of the psycho package is to provide tools for psychologists, neuropsychologists and neuroscientists, to facilitate and speed up the time spent on data analysis. It aims at supporting best practices by providing tools to format the output of statistical methods to directly paste them into a manuscript, ensuring standardization of statistical reporting.

Contribute
==============
blog posts:

    The end of errors in ANOVA reporting
    Variable vs. Participant-wise Standardization
    Formatted Correlation with Effect Size
    Extracting a Reference Grid of your Data for Machine Learning Models Visualization
    Copy/paste t-tests Directly to Manuscripts
    Easy APA Formatted Bayesian Correlation
    Fancy Plot (with Posterior Samples) for Bayesian Regressions
    How Many Factors to Retain in Factor Analysis
    Beautiful and Powerful Correlation Tables
    Format and Interpret Linear Mixed Models
    How to do Repeated Measures ANOVAs
    Standardize (Z-score) a dataframe
    Compute Signal Detection Theory Indices
    Installing R, R Studio and psycho

General Workflow
==================
The package revolves around the psychobject. Main functions from the package return this type, and the analyze() function transforms other R objects into psychobjects. Four functions can then be applied on a psychobject: summary(), print(), plot() and values().

Installation
=================
    To get the stable version from CRAN, run the following commands in your R console:

library("psycho")

    To get the latest development version, run the following:

