# Walmart_Business_Case

# About Walmart

Walmart is an American multinational retail corporation that operates a chain of
supercenters, discount departmental stores, and grocery stores in the United States.
Walmart has more than 100 million customers worldwide.

# Business Problem

The Management team at Walmart Inc. wants to analyze the customer purchase
behavior (precisely, purchase amount) against the customer’s gender and the various
other factors to help the business make better decisions. They want to understand if the
spending habits differ between male and female customers.

# Columns Overview

● User_ID: User ID
● Product_ID: Product ID
● Gender: Sex of User
● Age: Age in bins
● Occupation: Occupation
● City_Category: Category of the City (A,B,C)
● StayInCurrentCityYears: Number of years stay in current city
● Marital_Status: Marital Status
● ProductCategory: Product Category
● Purchase: Purchase Amount

# Approach Used

I conducted a comprehensive Exploratory Data Analysis (EDA) by examining the structure and characteristics of the dataset, identifying the shape of the data, and addressing missing values for each column. Outliers in continuous variables were detected using boxplots, and histograms were created to analyze the relationship between product purchases and age groups. I performed multivariate analysis to explore the interaction between age, marital status, and the amount spent by customers. Additionally, I applied the Central Limit Theorem (CLT) and bootstrapping techniques to compute 95% confidence intervals for the average amount spent, based on gender, marital status, and age. This analysis was extended to sample sizes of 300, 3000, and 30000 to assess consistency and reliability of insights across various sample sizes.





