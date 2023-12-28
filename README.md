# Classification-of-Phishing-websites
### Problem Description
The problem is the detection of phishing websites, which are maliciour sites designed to decieve users and extract sensitive information such as login credentials, financial details, personal information, etc. The goal is to create a model that can distinguish between phishing websites and legitimate websites based on varous factors.
#### Objective:
Build a model that predicts/classifies whether a website is a Phishing website.
#### Attributes:
having_IP_Address
URL_Length
Shortening_Service
having_At_Symbol
double_slash_redirecting
Prefix_Suffix
having_Sub_Domain
SSLfinal_State
Domain_registration_length
Favicon
port
HTTPS_token
Request_URL
URL_of_Anchor
Links_in_tags
SFH
Submitting_to_email
Abnormal_URL
Redirect
on_mouseover
RightClick
popUpWidnow
Iframe
age_of_domain
DNSRecord
web_traffic
Page_Rank
Google_Index
Links_pointing_to_page
Statistical_report
Result

## Dataset loading and loading libraries
Load of libraries such as pandas, numpy, maplotlib, seaborn, logistic regression, svc, auc_roc_score, random forest.
Load the dataset.

## Data Understanding:
Data Understanding include basic steps like understanding the rows and columns in the data. Check
the duplicates and the missing values.

a. Review the column name and their descriptions to understand the information they
represent.
b.Take time to explore and understand the dataset.

## 4.Data Cleaning:

• Check for missing values, inconsistencies in the dataset.
• Handle missing data appropriately, either through imputation or considering the
necessity of the variable for analysis.
• Remove any duplicate records to ensure data accuracy.

## 5.Data Visualization, Storytelling & Experimenting with charts: Understand
the relationships between variables.
Exploratory Data Analysis (EDA) is important because it helps in understanding the dataset,
checking data quality, identifying patterns, trends, and relationships, and selecting relevant
features for analysis. It plays a crucial role in preparing the data for further analysis and
making informed decisions based on the insights gained from the data.

Perform Bivariate analysis for getting the relationship between the two variables.
Perform Multivariate analysis for more than one variable behind resultant.

## Data Scaling:
Data scaling is the process of standardizing numerical variables to a consistent range for unbiased
analysis.
Standardization (zscore): It transforms the data to have a mean of 0 and a standard
deviation of 1. For eg, for Age and Income we will be using standardization.

## Data splitting:
Data splitting refers to the process of dividing a dataset into separate subsets, typically training and
testing sets, to assess the performance of a machine learning model.

What data splitting ratio have you used and why?
In this project, I have used a common data splitting ratio of 80:20, with 80% of the data used for
training and 20% for testing/validation. This ratio provides a balance between having enough data
for training the model and having a sufficient amount for evaluating its performance.

## ML Model Implementation
Model such as logistic regression, svc, random forest were used. evaluation metric used (e.g., accuracy, precision, recall, F1-score) 

## Conclusion:
With 94% training accuracy and 94% testing accuracy, Logistic regression and Random forest has proven to be the most efficient model out of the algorithms used in our model including svc. The logistic regression shows a balanced precision, recall, and F1-score, making it a good choice for this classification task. The Random forest achieve slightly higher accuracy.
