## Course Marketing: Customer Segmentation by Lead Scoring Strategy
Lead scoring is a pivotal metric for assessing leads and has become a standard in contemporary CRM systems. Within this repository, we delve into how the lead scoring strategy helps solve customer conversion problems, exploring the application of various supervised machine learning models 

## Problem Statement:
An education company named X Education sells online courses to industry professionals. On any given day, many professionals who are interested in the courses land on their websites and browse for courses.

The company markets its courses on several websites and search engines like Google. Once these people land on the website, they might browse the courses, fill up a form for the course, or watch some videos. When these people fill out a form providing their email address or phone number, they are classified as leads. Moreover, the company also gets leads through past referrals. Once these leads are acquired, employees from the sales team start making calls, writing emails, etc. Through this process, some of the leads get converted, while most do not. The typical lead conversion rate at X Education is around 30%.

Now, although X Education gets a lot of leads, its lead conversion rate is very poor. For example, if, say, they acquire 100 leads in a day, only about 30 of them are converted. To make this process more efficient, the company wishes to identify the most potential leads, also known as ‘Hot Leads’. If they successfully identify this set of leads, the lead conversion rate should go up, as the sales team will now be focusing more on communicating with the potential leads than making calls to everyone.

<img width="640" alt="Screen Shot 2023-11-10 at 6 20 44 AM" src="https://github.com/Katyayani09/Course-Marketing---Lead-Scoring/assets/80200480/ae865c13-9972-4fe9-8567-c764532d16aa">

There are a lot of leads generated in the initial stage (top) but only a few of them come out as paying customers from the bottom. In the middle stage, you need to nurture the potential leads well (i.e., educate the leads about the product, constantly communicate, etc. ) in order to get a higher lead conversion.

X Education wants to select the most promising leads, i.e., the leads that are most likely to convert into paying customers. The company requires you to build a model wherein you need to assign a lead score to each of the leads such that the customers with a higher lead score have a higher conversion chance and the customers with a lower lead score have a lower conversion chance. The CEO, in particular, has given a ballpark estimate of the target lead conversion rate to be around 80%.

## Solution:
For this case study, we're going to use several classification models to predict whether the lead is going to be quantified as a hot lead. The steps involved in this case study are listed below:

1. Data Loading
2. Exploratory Data Analysis
3. Preprocessing
4. Feature Engineering
5. Outlier Analysis
6. Model Building
7. Model Performance Benchmarking
8. Model Performance Evaluation
9. Cross Validation + Hyperparameter Tuning
10. Model Diagnosis Using Probability Calibration, ROC-AUC Curve, and Precision-Recall Curve

## Notebooks:
* Exploratory Data Analysis + Feature Engineering + Outlier Analysis Notebook
* Lead Scoring Model Diagnosis Notebook
* Final Lead Scoring Model Notebook
