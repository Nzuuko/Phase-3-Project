# SyriaTel Customer Churn Predictive Analysis
## Overview
This Project seeks to help a telecommunications company, SyriaTel predict customer churn with the use of machine learning. 

## Business Problem
SyriaTel, a telecommunications company, grapples with the challenge of customer churn in the highly competitive and dynamic telecommunications market. Recognizing the detrimental impact of customer churn on business growth and profitability, SyriaTel aims to address this issue by leveraging machine learning. By analyzing consumer data to understand tastes and trends, SyriaTel can tailor its services to prevent customer churn and maximize profits. Implementing a machine learning model allows the company to predict and mitigate customer churn, minimizing revenue loss and strengthening customer relationships for sustainable market growth.

## Data Understanding
The data used for this project is sourced from Kaggle. It consists of the following column data: 
1. **State**: this is the state in which the customer resides
2. **Account Length**: This refers to the number of months customers had an account with the company.
3. **Area code**: this is the customers area code.
4. **Phone Number**: the customer's phone number.
5. **International plan**: this indicates whether the customer is subscribed to an international calls plan. It is a binary feature (yes/no).
6. **Voice mail plan**: indicates whether a customer has a voicemail plan. Also a binary feature
7. **Number vmail messages**: this is a numerical variable showing the total number of voicemails the customer received.
8. **Total day minutes**: The total number of calls made by the customer during the day
9. **Total Day Calls**: The total number of calls made by the customer during the day.
10. **Total Day Charge**: The total cost incurred by the customer for calls made during the day.
11. **Total Eve Minutes**: The total duration (in minutes) of calls made by the customer during the evening.
12. **Total Eve Calls**: The total number of calls made by the customer during the evening.
13. **Total Night Minutes**: The total duration (in minutes) of calls made by the customer during the night.
14. **Total Night Calls**: The total number of calls made by the customer during the night.
15. **Total Night Charge**: The total cost incurred by the customer for calls made during the night.
16. **Total Intl Minutes**: The total duration (in minutes) of international calls made by the customer.
17. **Total Intl Calls**: The total number of international calls made by the customer.
18. **Total Intl Charge**: The total cost incurred by the customer for international calls.
19. **Customer Service Calls**: The number of calls made by the customer to customer service.
20. **Churn**: Indicates if the customer has terminated their contract with the company. (Yes/No).

## Data Preparation
In this stage, the data is preprocessed and cleaned in order to make it suitable for analysis. This ensures that the data is of a higher quality and thus will help in the process of getting insights and thus aiding the SyriaTel make more informed decisions.

## Data Analysis and Modelling 
The data undergoes analysis methods to produce a result which is then visualized to convey data driven insights. Once the data models are created it becomes easier to explain the results of the study.

4. Exploratory Data Analysis
- Univariate EDA
Univariate data analysis focuses on analyzing individual variables. This involves studying each feature's distribution to comprehend its properties and detect anomalies like outliers.

- Bivariate Analysis
Bivariate analysis examines the relationship between two variables. This will help understand how different features relate to customer churn.

- Multivariate Analysis
Multivariate analysis investigates the interplay among multiple variables, focusing on their correlation with the target variable, customer churn. A correlation matrix will be utilized to discern associations among variables.

5. Modeling
In the churn prediction project, various models will be created, evaluated, and fine-tuned to predict customer churn based on dataset features.

5.1 Logistic Regression
Logistic regression is a statistical technique for binary classification tasks, estimating the probability of an observation belonging to a specific class.

5.2 Decision Tree Classifier
The Decision Tree Classifier partitions the dataset into refined subsets, predicting the class of new data based on feature values.

5.3 Random Forest Classifier
Random Forest creates multiple decision trees and derives predictions by averaging their outputs, suitable for classification tasks.

5.4 XGBoost
XGBoost merges weak models, like decision trees, using gradient boosting and ensemble learning, forming a potent predictive model.

The ROC_AUC metric will evaluate the performance of these models.

6. Model Evaluation
During this stage, models will be assessed using recall scores and ROC_AUC. The top two models will then be selected for further fine-tuning.

6.1 Model Comparison - Recall Score
The recall score quantifies the proportion of actual positive instances that the model correctly identifies.

6.2 Model Tuning
After assessing the models, it's evident that both XGBoost and RandomForest classifiers exhibit promising performance. Fine-tuning via GridSearch will be employed to enhance their effectiveness further.

Conclusion

Recommendations to reduce Customer Churn are:
1. **Total Charges**:
- **Targeted Promotions**: Offer attractive discounts or bundle deals to high-spending customers who might be considering switching providers.
- **Loyalty Programs**: Implement a tiered loyalty program rewarding high spenders with exclusive benefits like priority customer service or early access to new features.

2. **Customer Service Calls**:
- **Improved Service**: Analyze call transcripts and customer feedback to identify areas for improvement in customer service interactions.
- Proactive Outreach: Train customer service representatives to identify at-risk customers based on call frequency and proactively address their concerns.

3. **International Plan & Voice Mail Plan**:
- **Plan Bundles**: Create attractive bundled plans that combine these features with other popular services at a competitive price.
- **Targeted Upselling**: Identify customers who might benefit from these plans based on usage patterns and offer personalized upselling campaigns.


