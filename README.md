
# The Data Science Process

### Introduction

Just as it's important to understand the kinds of problems that can be solved by data science, it's also important to have a sense of the process used to conduct data science. In this lesson we'll outline the lifecycle of a typical data science project - from business understabnding through data visualization.

## Objectives
You will be able to:
* Describe the data science process

## The Data Science Process

There is much more to data science that just selecting, applying and tuning Machine Learning algorithms. A data science project will often include the following stages:

<img src="chart.png" width = "500"/>

In the following section, we shall go through each of these stages and see what is involved:

### Business Understanding / Domain Knowledge

Before trying to solve a data related problem, it is important that a data scientist/analyst has a clear understanding of the problem domain. The questions generally asked at this stage might include:

* How much or how many? e.g. Identifying number of new customers likely to join your company in next quarter. (Regression analysis)

* Which category? e.g. Assigning a document to a given category for a document management system. (Classification analysis)

* Which group? e.g. Creating a number of a groups (segments) of your customers based on their monetary value. (Clustering)

* Is this weird? e.g. Detecting suspicious activities of a customers by a credit card company to identify potential fraud. (Anomaly detection)

* Which option should be taken? e.g. Recommending new products (e.g. movies/books/music by Amazon) to exisating customers (Recommendation systems)

<img src='domain.gif'>

### Data Collection

After asking the analytical question and identifying objectives for your analysis, the next stage of analysis is to identify and gather the required data. 

Data mining is a process of identifying and collecting data of interest from different sources - databases, text files, APIs, the Internet and even printed documents. Some of the questions that you may ask yourself at this stage are:

* What data items do I need in order to answer my analytical question ?
* Where can I find this data ?
* How can I obtain the data from data source ?
* How do I sample from this data ?
* are their any privacy/ legal issues that I must consider prior to data usage ?

<img src='data-collection.png'>

### Data Cleaning

Data cleaning and wrangling is usually the most time consuming stage within the data science process. This stage may take up to 50-80% of a data scientist's time as there are a vast number of possible problems that make the data "dirty" and unsuitable for analysis. Some of the problems you may see in data are follows:

* Inconsistencies in data
* Mis-spelled text data
* Outliers
* Imbalanced data
* Invalid/outdated data
* Missing data

The data cleaning stage requires the development of a strategy on how to deal with these issues. Such a strategy may vary substantially between different analysis experiments depending on the nature of problem being solved. 

<img src='clean.png'>

### Data Exploration

Data exploration or Exploratory Data Analysis is the stage that follows data cleaning. Exploratory analysis help highlight the patterns, relations, variance and bias of available data. Exploratory analysis may involve following activities:

* Selecting a subset of a bigger dataset for exploration
* Calculating basic statistics i.e. mean, median and mode etc.
* Plotting histograms, scatter plots, distribution curves to identify trends in data
* Other interactive visualisation with filtering to focus on a specific segment of data 

<img src='eda.png'>


### Feature Engineering

A "Feature" is a measurable attribute of phenomenon being observed. Based on the nature of analystical question asked in the first step, a data scientist may have to engineer additional features not found in the original dataset. Feature engineering is the process of using expert knowledge to transform raw data into meaningful features that directly address the problem you are trying to solve. For example, taking weight and height to calculate Body Mass Index for the individuals in the dataset. This stage will substantially influence the accuracy of the predictive model you construct in the next stage. 

<img src='feat.png'>

### Predictive Modelling

Modelling is the stage where you use mathematical and/or statistical approaches to answer your analytical question. Predictive Modelling refers to the process of using probabalistic statistical methods to "Predict" the outcome of an event. For example, based on employee data, an organisation can develop a predictive model to identify employee attrition rate in order to develop better retention strategies.

Choosing the "right" model is often a challenging decision as there is never a single right answer. Selecting a model involves balancing the accuracy and the computational cost of the analysis process. For example, some recent approaches in predictive modelling such as deep learning have been shown to offer vastly improved accuracy of results, but with a very high computational cost.

<img src='predict.png'>

### Data Visualisation

After deriving the required results from a statistical model, visualisations are normally used to summarise and present the findings of the analysis process in a form which is easily understandable by non-technical decision makers. 

Data visualisation could be thought of as an evolution of visual communication techniques as it deals with the visual representation of data. There are a wide range of different data visualisation techniques, from bar graphs, line graphs and scatter plots to alluvial diagrams and spatio-temporal visualisations, each of which will work better for presenting certain types of information.

<img src='viz.png'>

### Summary

In this lesson, we looked at the data science process and different activities that data scientists are engaged with while doing data analysis. 


