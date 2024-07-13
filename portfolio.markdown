---
layout: page
title: Portfolio
permalink: /portfolio
order: 1
---

---

## Table of contents

1. [Data Engineer](#data-engineer)
2. [Data Analytics](#data-analytics)

---

## Data Engineer

### 🤖 [Quiz Data Processing](https://github.com/linhnde/quiz-data-processing){:target="_blank"}

In this project, we will build a Jupyter notebook to create a synthetic quiz dataset for using in web application.

I use Vertex AI to generate text data mimics quiz which input by human in common format. From the mockup document, we will load, extract and process, re-engineer it into JSON format which is widely used for web application.

### 🧐 [Exam Practice (Flask base)](https://github.com/linhnde/exam-practice-flask){:target="_blank"}

Simulating a demand for practicing on certain quiz set, I create this web app, Exam Practice (EP).

Originally, app was built on Tkinter. But later I adapted it on Flask to take advantages of responsive designing.

Using Google Cloud Run for deploying, we can save expense significantly in the early stage 
as we don't have to worry about 24/7 uptime bill.

Google Cloud Run also makes it easy to scale up the infrastructures if we need.

---

## Data Analytics

### 🚖 [Automatidata](https://github.com/linhnde/automatidata){:target="_blank"}

#### [Identify data types and relevant variables using Python](https://github.com/linhnde/automatidata/blob/master/automatidata_1_start_python.ipynb){:target="_blank"}
To get clear insights, New York TLC's data must be analyzed, key variables identified, and the dataset ensured it is ready for analysis.

#### [Exploratory Data Analysis](https://github.com/linhnde/automatidata/blob/master/automatidata_2_eda.ipynb){:target="_blank"}
I use Python to show data structuring and cleaning, as well as any matplotlib/seaborn visualizations plotted to help understand the data, a box plot of the ride durations, and some time series plots, like a breakdown by quarter or month.

#### [Conduct an A/B test](https://github.com/linhnde/automatidata/blob/master/automatidata_3_statistics.ipynb){:target="_blank"}
The project is reaching its midpoint. Next, I get a specific assignment: to compute descriptive statistics and conduct a hypothesis test.

#### [Build a multiple linear regression model](https://github.com/linhnde/automatidata/blob/master/automatidata_4_regression_analysis.ipynb){:target="_blank"}
It’s time to work on predicting the taxi fare amounts. We are ready to build the regression model and update the client New York City TLC about our progress.

#### [Machine Learning](https://github.com/linhnde/automatidata/blob/master/automatidata_5_machine_learning.ipynb){:target="_blank"}
Our client, the New York City Taxi & Limousine Commission (New York City TLC), has requested that I build a machine learning model to predict if a customer will not leave a tip. They want to use the model in an app that will alert taxi drivers to customers who are unlikely to tip since drivers depend on tips.
* [Executive Summary](https://github.com/linhnde/automatidata/blob/master/automatidata_executive-summary.pdf){:target="_blank"}

### 👔 [Salifort Motors](https://github.com/linhnde/salifort-motors/blob/master/salifort_motors.ipynb){:target="_blank"}
In this project, my goals are to analyze the data collected by the HR department and to build a model that predicts whether or not an employee will leave the company.
* [Project Proposal](https://github.com/linhnde/salifort-motors/blob/master/salifort-motors_project-proposal.pdf){:target="_blank"}
* [Executive Summary](https://github.com/linhnde/salifort-motors/blob/master/salifort-motors_executive-summary.pdf){:target="_blank"}

### 🚀 [Space Mission](https://github.com/linhnde/space-mission/blob/master/space_mission.ipynb){:target="_blank"}
An incredibly rich dataset from [nextspaceflight.com](https://nextspaceflight.com/launches/){:target="_blank"} that includes all the space missions since the beginning of Space Race between the USA and the Soviet Union in 1957! It has data on the mission status (success/failure), the cost of the mission, the number of launches per country, and much much more.

### 💰 [Earning Predict](https://github.com/linhnde/earning-predict/blob/master/earning_predict.ipynb){:target="_blank"}
The National Longitudinal Survey of Youth 1997-2011 dataset is one of the most important databases available to social scientists working with US data.
It allows scientists to look at the determinants of earnings as well as educational attainment and has incredible relevance for government policy.
When we have a better understanding how these variables affect education and earnings we can also formulate more suitable government policies.

###  🦄 Unicorn Companies
#### [Discovery](https://github.com/linhnde/unicorn-companies/blob/master/unicorn_companies_discovery.ipynb){:target="_blank"}
The data I will use for this task provides information on over 1,000 unicorn companies, including their industry, country, year founded, and select investors. I will use this information to gain insights into how and when companies reach this prestigious milestone and to make recommentations for next steps to the investing firm.

#### [Structure](https://github.com/linhnde/unicorn-companies/blob/master/unicorn_companies_structure.ipynb){:target="_blank"}
We work with the unicorn companies dataset, discovering characteristics of the data, structuring the data in ways that will help us draw meaningful insights, and using visualizations to analyze the data. Ultimately, we will draw conclusions about what significant trends or patterns we find in the dataset.
