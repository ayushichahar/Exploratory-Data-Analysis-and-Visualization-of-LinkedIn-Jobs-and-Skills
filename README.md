# Exploratory Data Analysis and Visualization of LinkedIn Jobs and Skills
## Import Libraries
- import numpy as np
- import pandas as pd
- import matplotlib.pyplot as plt
- import seaborn as sns
- import warnings
warnings.filterwarnings('ignore')
## Loading Dataset
## This dataset have 3 csv files:

### 1. linkedin_skills: it has 1296381 rows and 2 columns

- job_link : job details and description
- job_skills: skills which arae needed for that job
### 2. linkedin_jobs : it has 1297332 rows and 2 columns

- job_link : job details and description
- job_summary: summary of that job and qualifications
### 3. linkedin_posts: it has 1348454 rows × 14 columns

- job_link:link of that job profile
- last_processed_time: process time
- got_summary:
- got_ner:
- is_being_worked:
- job_title: title of job
- company: name of the company providing job
- job_location: job location
- first_seen: jobs providing time
- search_city : city_name
- search_country: country_name
- search_position:position of job
- job_level:level of job
- job_type:type of the job
## Goal of project:
- to know the skills which need for a jobs,
- to know the jobs providing countries and cities,
- to know the which skills need to be learn for a specific position,
- to get connections with high proffessional employees and experienced employees,
- to know which location providings jobs for our requirement.

## Data Preparation
Explorings rows and columns

## Data cleaning
*Data cleaning is the process of fixing or removing incorrect, corrupted, incorrectly formatted, duplicate, or incomplete data within a dataset.

### Benefits of data cleaning
- Error free data
- Acurracy and efficiency
- Data quality
- Data consistency

### Data performing:
the process of systematically applying the statstical,numerical and logic techinques to describe and illustrate and evaluate data

### Exploratory Data Analysis & Visualization
- EDA plays an important role in Data Analysis
- Exploratory data analytics focuses on all the parts of context, mainly the why and how. An outcome can be statistically calculated, modeled, or visualized to tell you the likelihood of certain events based on preconceived variables.

## Data visualization
### Question and Answers
By using different libararies to perform EDA and VISUALIZATION
### 1. Provide the list of top 10 jobs present in linkedin profiles?
![image](https://github.com/user-attachments/assets/9f483505-d9bd-4370-a2ce-e00a1ba4afbc)

### 2. When did most of the proccessing time of jobs done in a week?
![image](https://github.com/user-attachments/assets/52e7b92b-c278-4b6f-b162-48aef449f5f7)

### 3. Provide the list of top companines which provides job openings in linkedin?
![image](https://github.com/user-attachments/assets/dac57d3a-4da6-4717-bd92-cc6e9521d504)

### 4. Plot the possible graphs of the bottom 10 companines in data set?
![image](https://github.com/user-attachments/assets/89b95ebb-6956-405d-a5d9-73e569eb43d6)

### 5. Provide how many number of jobs having different job types in linkedin?
![image](https://github.com/user-attachments/assets/deee1efb-c8fd-4640-ac95-e4d745d7568c)

### 6. Provide how many number of jobs positions having different jobs in linkedin?
![image](https://github.com/user-attachments/assets/8c862aae-d2c4-4fc0-a4fd-e5328f694f5d)

### 7. Recommend the top job locations present in linkedin for working?
![image](https://github.com/user-attachments/assets/c584f586-4d16-467e-ba5c-e249ef12eeb0)

### 8. Whats the best timings of job openings in linkedin?
![image](https://github.com/user-attachments/assets/41d94f1e-2388-461e-8718-6f1db5f7237c)

### 9. Plot the violin plot on the basis of job opening day in month?
![image](https://github.com/user-attachments/assets/d225a80d-e276-40f2-84e7-462e4807af7a)

### 10. Plot the histplot with respect to various positions to be searched by users of linkedin to get jobs ?
![image](https://github.com/user-attachments/assets/5e59089a-3754-4cf1-a3d1-a456b025c3ec)

## SUMMARY:
- Good way to network
- Linkedin used to build easy connections with recuriters
- Updating skills and resume will lead to fast recuriting
- Freshers can know the all list of jobs and can easily apply to those positions
- Easily understanding the types and positions of various jobs online
- Better oppurnities of internships and jobs.
### We can say that above 1.3 million people are using linkedin for job and learning purpose in world ..linkedin is an useful social media platforms for both recuriters and job seekers.
