# Final Project Group 01
Data Sceince Job Salaries 

### Link : https://www.kaggle.com/datasets/saurabhshahane/data-science-jobs-salaries

# Dataset source
We pulled the data from Kaggle
The dataset was uploaded to Kaggle from the original [Source, Ai-salaries ](https://salaries.ai-jobs.net/download
)
The site is soley for Machine Learning/AI/Tech open positions and a salary database. People are able to submit their own info to add it to the dataset. 
# Dataset Explaination 

<b>work_year</b> : The year the salary was paid.

<b>experience_level</b> : The experience level in the job during the year with the following possible values: EN Entry-level / Junior MI Mid-level / Intermediate SE Senior-level / Expert EX Executive-level / Director

<b>employment_type</b> : The type of employement for the role: PT Part-time FT Full-time CT Contract FL Freelance

<b>job_title</b> : The role worked in during the year.

<b>salary</b> : The total gross salary amount paid.

<b>salary_currency</b> : The currency of the salary paid as an ISO 4217 currency code.

<b>salary_in_usd</b> : The salary in USD (FX rate divided by avg. USD rate for the respective year via fxdata.foorilla.com).

<b>employee_residence</b> : Employee's primary country of residence in during the work year as an ISO 3166 country code.

<b>remote_ratio</b> : The overall amount of work done remotely, possible values are as follows: 0 No remote work (less than 20%) 50 Partially remote 100 Fully remote (more than 80%)

<b>company_location</b> : The country of the employer's main office or contracting branch as an ISO 3166 country code.

<b>company_size</b> : The average number of people that worked for the company during the year: S less than 50 employees (small) M 50 to 250 employees (medium) L more than 250 employees (large)




## Random Forest Machine Learning Model.

Random forests or random decision forests are an ensemble learning method for classification, regression and other tasks that operates by constructing a multitude of decision trees at training time.

### Some interesting facts about Random Forests – Features
1. Accuracy of Random forest is generally very high
2. Its efficiency is particularly Notable in Large Data sets
3. Provides an estimate of important variables in classification
4. Forests Generated can be saved and reused

![Classification_report](https://user-images.githubusercontent.com/107137215/202321271-6143b156-ac96-489a-a2f1-54288a14a60c.jpg)

 

### Advantages and Disadvantages of Random Forest
1.It reduces overfitting in decision trees and helps to improve the accuracy
2. It is flexible to both classification and regression problems
3. It works well with both categorical and continuous values
4. It automates missing values present in the data
5. Normalising of data is not required as it uses a rule-based approach.

However, despite these advantages, a random forest algorithm also has some drawbacks.
1. It requires much computational power as well as resources as it builds numerous trees to combine their outputs. 
2. It also requires much time for training as it combines a lot of decision trees to determine the class.
3. Due to the ensemble of decision trees, it also suffers interpretability and fails to determine the significance of each variable.

### Exploratory Data Analysis (EDA)

![Outliers](https://user-images.githubusercontent.com/107137215/202324439-2c5d6c37-7146-4cd2-91a4-8a8b6323170e.jpg)



## Our Why:
Group selected this particular topic because it is relevant to the coursework and incorporates the information Prof Norman went over at the beginning of each topic. Salary matters in each field, and knowing what we are looking at is beneficial to all of us as we explore data science careers. 

This Tableau story can be seen at  [link to dashboard](https://public.tableau.com/app/profile/nensi.pandya/viz/ds_salary/JobtitleandSalaryinUSd)

What we plan to anaylze with our data: 
We have narrowed data down to residents of the US only to eliminate inaccuracies with currency. We plan to select 1-5 job titles to compare and make predictions with. 

Questions will include:
---- 
Average change in salary per year (Cecelia)

Salary based on company size (David)

Salary comparison for remote vs in-office positions. (Kinjal)

Salary comparison for Top 3 positions (Nensi) . 


What we will use:
Linear Regression Machine Learning 
Juoyter notebook, Tableau 


Presentation:

[Link to Google slides](https://docs.google.com/presentation/d/1EuZcaTtNKKLiq5Ai4xnP8bAwsP34RqSoqZRCWC5Jcxg/edit#slide=id.g12bc75dd6ef_0_15)


[Link to Dashboard](https://public.tableau.com/authoring/Salariesfordatasciencejobs/Sheet5/Story%201?%3Aignore_sticky_session=yes#1)





