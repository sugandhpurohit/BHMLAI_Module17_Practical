## Bank Marketing Campaigns

### Overview

Goal is to compare the performance of the classifiers and to analyse dataset to provide insights if customers would subscribe to service or not.

### Data

URL: https://archive.ics.uci.edu/dataset/222/bank+marketing.

The data is related with direct marketing campaigns (phone calls) of a Portuguese banking institution. The classification goal is to predict if the client will subscribe a term deposit (variable y).

### Data Description

- Input variables:
   #### bank client data:
   1 - age (numeric)
   2 - job : type of job (categorical: "admin.","unknown","unemployed","management","housemaid","entrepreneur","student",
                                       "blue-collar","self-employed","retired","technician","services") 
   3 - marital : marital status (categorical: "married","divorced","single"; note: "divorced" means divorced or widowed)
   4 - education (categorical: "unknown","secondary","primary","tertiary")
   5 - default: has credit in default? (binary: "yes","no")
   6 - balance: average yearly balance, in euros (numeric) 
   7 - housing: has housing loan? (binary: "yes","no")
   8 - loan: has personal loan? (binary: "yes","no")
   #### related with the last contact of the current campaign:
   9 - contact: contact communication type (categorical: "unknown","telephone","cellular") 
  10 - day: last contact day of the month (numeric)
  11 - month: last contact month of year (categorical: "jan", "feb", "mar", ..., "nov", "dec")
  12 - duration: last contact duration, in seconds (numeric)
   #### other attributes:
  13 - campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)
  14 - pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric, -1 means client was not previously contacted)
  15 - previous: number of contacts performed before this campaign and for this client (numeric)
  16 - poutcome: outcome of the previous marketing campaign (categorical: "unknown","other","failure","success").


- Output variable (desired target):
  17 - y - has the client subscribed a term deposit? (binary: "yes","no")

### Summary of Findings

- Objective of the task is to identify customers that may be intereseted in subscribing to service or not.
- Based on the analysis of dataset, it would help to gather more data for the customers who subscribed to the service as around 10% only subscribed to service out of total dataset.
- Also dataset seems to imbalanced.
- Comparing model using large dataset resulted in utilizing Logistic Regression model for this task.
- Comparing model using small dataset to include SVM also resulted in utilizing Logistic Regression model for this task.

### Project URL
- GIT: https://github.com/sugandhpurohit/BHMLAI_Module17_Practical
- Notebook: https://github.com/sugandhpurohit/BHMLAI_Module17_Practical/blob/main/BankMarketing.ipynb
