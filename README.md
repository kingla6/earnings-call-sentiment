# earnings-call-audio-modeling
This is a template repository for a proof-of-concept model to generate insights from earnings calls in order to make predictions on stock market prices.

### Prerequisites (TBD)
To most easily run this code out of the box, the following packages must be installed:
* pandas
* numpy
* scikit-learn
* matplotlib
* seaborn
* great expectations
* h2o
* fastai
* huggingface
* datasets

This is easiest to achieve through first installing an Anaconda distribution, which installs the first 5 packages and all of their dependencies.  The install directions to the other packages may be found on their documentation pages.

# Quick navigation
[Background](#background)  
[Data](#data)  
[Models](#models)  
[Timeline](#timeline)  
[Repo Structure](#repo-structure)  
[Logistics](#project-logistics)  
[Resources](#resources)  
[Contact](#contact-info)

# Goal

Provide an overview of the goals and deliverables of the project. Mention any relevant details or issues. 

Make use of transformer models to extract data from earnings calls. This data will be used for tasks such as predicting stock prices for companies associated with each call. The model created is intended to demonstrate a proof-of-concept, success will not be measured by model performance. However, future work on this project should focus on improving model performance for related use-cases. 

# Background  

A topic of interest in the finance community has been extracting data from various sources such as earnings calls in order to predict performance of companies. Previous work has been done with NLP to make predictions using text data, however transformers now make it possible to make predictions with audio data. Application of this state-of-the-art modeling technique will work to solve an existing problem in the finance community while also opening the door for future improvement on this project and other new projects. 

# Data

Describe the data - what kind of data is it?  Describe the general format, and potential quirks.

## Data security

All data used within this course is publicly available from [earningscast](https://earningscast.com/).

## Counts (TBD)

Describe the overall size of the dataset and the relative ratio of positive/negative examples for each of the response variables.

# Models (TBD)

Clearly identify each of the response variables of interest.  Any additional desired analysis should also be described here.

# Timeline

This project will be completed during Vanderbilt's 2022 Spring Semester, beginning January 17th and ending April 29th. Intermediate progress updates will occur weekly, every Friday unless scheduled otherwise. 

# Repo Structure (TBD)

Give a description of how the repository is structured. Example structure description below:

The repo is structured as follows: Notebooks are grouped according to their series (e.g., 10, 20, 30, etc) which reflects the general task to be performed in those notebooks.  Start with the *0 notebook in the series and add other investigations relevant to the task in the series (e.g., `11-cleaned-scraped.ipynb`).  If your notebook is extremely long, make sure you've utilized nbdev reuse capabilities and consider whether you can divide the notebook into two notebooks.

All files which appear in the repo should be able to run, and not contain error or blank cell lines, even if they are relatively midway in development of the proposed task. All notebooks relating to the analysis should have a numerical prefix (e.g., 31-) followed by the exploration (e.g. 31-text-labeling). Any utility notebooks should not be numbered, but be named according to their purpose. All notebooks should have lowercase and hyphenated titles (e.g., 10-process-data not 10-Process-Data). All notebooks should adhere to literate programming practices (i.e., markdown writing to describe problems, assumptions, conclusions) and provide adequate although not superfluous code comments.

# Project logistics

**Sprint planning**:  
Weekly, Fridays

**Data location**:  

# Resources 
* **HuggingFace**: [Website](https://huggingface.co/transformers/index.html), [Course/Training](https://huggingface.co/course/chapter1), [Inference using pipelines](https://huggingface.co/transformers/task_summary.html), [Fine tuning models](https://huggingface.co/transformers/training.html)

# Contact Info

Logan King, M.S. in Data Science Candidate  
Vanderbilt University  
logan.a.king@Vanderbilt.Edu  
