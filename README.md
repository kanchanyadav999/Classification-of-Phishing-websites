# Classification-of-Phishing-websites
### Problem Description
The problem is the detection of phishing websites, which are maliciour sites designed to decieve users and extract sensitive information such as login credentials, financial details, personal information, etc. The goal is to create a model that can distinguish between phishing websites and legitimate websites based on varous factors.
#### Objective:
Build a model that predicts/classifies whether a website is a Phishing website.
#### Attributes:
1) having_IP_Address
2) URL_Length
3) Shortening_Service
4) having_At_Symbol
5) double_slash_redirecting
6) Prefix_Suffix
7) having_Sub_Domain
8) SSLfinal_State
9) Domain_registration_length
10) Favicon
11) port
12) HTTPS_token
13) Request_URL
14) URL_of_Anchor
15) Links_in_tags
16) SFH
17) Submitting_to_email
18) Abnormal_URL
19) Redirect
20) on_mouseover
21) RightClick
22) popUpWidnow
23) Iframe
24) age_of_domain
25) DNSRecord
25) web_traffic
27) Page_Rank
28) Google_Index
29) Links_pointing_to_page
30) Statistical_report
31) Result

## Dataset loading and loading libraries
Load of libraries such as pandas, numpy, maplotlib, seaborn, logistic regression, svc, auc_roc_score, random forest, train_test_split, zscore.
Load the dataset.

## Data Understanding:
Data Understanding include basic steps like understanding the rows and columns in the data. Check
the duplicates and the missing values.

1) Review the column name and their descriptions to understand the information they
represent.
2) Take time to explore and understand the dataset.

## 4.Data Cleaning:

• Check for missing values, inconsistencies in the dataset.
• Handle missing data appropriately, either through imputation or considering the
necessity of the variable for analysis.
• Removing any duplicate records to ensure data accuracy.

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
Logistic regression models the probability of binary response variable and one or more predictor variables. It uses sigmoid function that maps any real valued input to a value between 0 and 1, which is used to transform linear combination of predictor variable into a probability value between 0 and 1.

SVM is a simple supervised machine learning algorithms used for classification and regression task. For classification problem we use SVC. 

Random forest is an example of ensemble learning that uses bagging plus bootstrap method. It trains multiple decision trees with different subsets of the data with replacement. It then combines the results to make a final predicition.

Evaluation techniques such as, Precision, Recall, F1 score, Auc_roc, we used.

## Conclusion:
With 94% training accuracy and 94% testing accuracy, Logistic regression and Random forest has proven to be the most efficient model out of the algorithms used in our model including svc. The logistic regression shows a balanced precision, recall, and F1-score, making it a good choice for this classification task. The Random forest achieve slightly higher accuracy.
