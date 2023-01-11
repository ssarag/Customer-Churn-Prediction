# Telecom Customer Churn Analysis (EDA and Model Building)


# Customer Churn
Customer attrition, commonly referred to as customer churn, is the decision made by a customer to discontinue utilizing a company's goods or services. However, for each client who churns, there are usually early signs or metrics that can be discovered through churn research.Because customers can choose from a range of service providers and actively switch from one to another, the telecom industry experiences a high rate of churn (annual churn rate of 15-25%).

In general, from a business standpoint, acquiring new clients is more expensive than keeping current ones. In fact, a 5% improvement in client retention alone can boost profits by at least 25%. This is due to the fact that returning consumers are likely to spend an additional 60% on a company's goods and services. As a result, the company can spend less on the operating costs of having to attract new consumers by spending time and money encouraging a current customer to choose your company over competitors because they've already made up their mind.

If a business could predict which customers are most likely to depart and why, it could concentrate its customer retention efforts exclusively on these "high risk" clients. This contributes to the company's goal of extending its consumer base and regaining customer loyalty.

# Dataset

For the analysis, I have used "Telecom Customer" dataset from kaggle.

Each row represents a customer, each column contains customer’s attributes described on the column Metadata.

The raw data contains 7043 rows (customers) and 21 columns (features).

The “Churn” column is our target.



# Objectives for the Analysis of Telecom Dataset:

1. What is the percentage of active customers and customers who churn?
2. Does gender influence customer churn?
3. Does the sort of service supplied result in greater or less customer churn?
4. What are the most profitable service categories?
5. Features and services offered by the business that are profitable


# Dataset Description
To load the dataset, I have used pandas.

Churn Column - Customers who left recently

Services provided by the company to its customer – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies

Customer's Information Columns - Old/New Customer and their Active Period, contract, payment method, paperless billing, monthly charges, and total charges

Customer's Demographic Columns – gender, age range, and if they have partners and dependents


![image](https://user-images.githubusercontent.com/103538049/211817683-ed57786b-4a71-4156-8c16-e14900b1632e.png)


# Exploratory Data Analysis and data Visualization 

![image](https://user-images.githubusercontent.com/103538049/211819245-249a32eb-d55e-4109-8d8f-250aed4b7b5c.png)


1. 26.6% of current customers switched to another firm
2. There are 49.5% females and 50.5% males.
3. There's almost no difference between the gender who churned, as both men and women are churn in equal ratio.

