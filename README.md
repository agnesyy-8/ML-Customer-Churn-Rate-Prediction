# Machine Learning Project - Predict the customer churn rate of a telecom company
By Agnes CHAU | Data Analyst | Master Student in Data Science in EMLyon Business School

Please feel to connect with me if you have any further suggestion on this project
- LinkedIn: https://www.linkedin.com/in/agneschaau/
- Github: https://github.com/agnesyy-8


# Purpose
The purpose is to enable the telecom company to predict the customers who have a high probability of churn with a good precision to help them activate the right retention strategies. Customer churn is one of the most important metrics a growing business needs to evaluate.

# Data
For the analysis, I use the data “Telco-Customer-Churn.csv”.
The csv file contains 7043 rows corresponding to customerID and 21 columns or features. The columns are describing customers account information, demographic information, customer subscribed services and the customer churn Vs previous month:
- The Churn column is binary with Yes/No values for each customer: 'Yes' representing a customer who churned i.e: he left the company within the last month. 'No' corresponding to a current customer of the telecom company. It is our target variable.
- Other columns represent customer account information: tenure (duration in months in the company), customer payment method, paperless billing (yes or no), subscription or contract type (month-on-month, one year-contract or 2-years contract) and monthly and annually total charges.
- Additional columns represent the customer subscribed service (or not): phone service, multiple lines, internet service, online security, device protection, technical support, TV streaming and movies streaming.
- And finally; we have the columns representing the demographic information for each customer: gender type, if they are senior citizens and if they have a partner and dependents.

# Objective:
- Can we predict the customers who are going to churn using a supervised learning model?
- Are there features that are correlated to customer churn?
- Are there different types of churn (satisfaction? product/service related?) ?
- What can we recommend the Telecom company to do?
