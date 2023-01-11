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

![image](https://user-images.githubusercontent.com/103538049/211820040-2e2332cd-005a-4873-9d61-a28d07bcf6f8.png)



1. 26.6% of current customers switched to another firm
2. There are 49.5% females and 50.5% males.
3. There's almost no difference between the gender who churned, as both men and women are churn in equal ratio.



![image](https://user-images.githubusercontent.com/103538049/211822124-9bbaf3ab-622a-4ac5-8944-5ba3a031a35d.png)



![image](https://user-images.githubusercontent.com/103538049/211822580-78f9b534-26de-4dc1-bb47-73f9a4c32fda.png)

# Observations:

1. Majority of the customers who moved out were having Electronic Check as Payment Method and others who opted for Credit-Card automatic transfer / Bank Automatic        Transfer and Mailed Check as Payment Method were less likely to switch.
2. Fiber optic service was choosen by a lot of customers and a high churn rate among these customers. This could mean an issue with the Fiber optic service which and      its dissatisfaction among customers.
3. Customers who opted for DSL service are greater in mumber and have less churn rate compared to Fibre optic service
4. Customers without dependents are more likely to churn.
5. Customers who have partners are more likely to churn while senior citizens being the most of churn.



![image](https://user-images.githubusercontent.com/103538049/211824267-1c247c0d-9420-4ebc-a380-beca78f81c0f.png)


![image](https://user-images.githubusercontent.com/103538049/211824522-c46cd587-baf5-4c5e-a9e2-714b9ae8d0f9.png)

# Observations:

1. Absence of online security,makes most customers churn.
2. Paperless Billing seems like one the reasons because of which customers are most likely to churn.
3. The absence of online security, Paperless Billing system and services with no TechSupport were the similiar trend are of the customers who are most likely churn.
4. Eventhough there's a small fraction of customers but it's better to point out as they are more likely to churn because don't have a phone service.


![image](https://user-images.githubusercontent.com/103538049/211830628-e6144de7-a947-48fa-9542-7fcbf704a514.png)



# Conclusion
1. 75% of customer who have Month-to-Month Contract have opted to move out as compared to 13% of customers who have signed One Year Contract and 3% of customers who     have signed Two Year Contract.
2. Majority of the customers who moved out were having Electronic Check as Payment Method and others who opted for Credit-Card automatic transfer / Bank Automatic       Transfer and Mailed Check as Payment Method were less likely to switch.
3. Fiber optic service which was choosen by a lot of customers and it's evident that there's high churn rate among these customers. This could expose an issue in the     Fiber optic service which dissatisfied most of it's customers, further looking into the issue might find a better and apt solution.
4. Customers who opted for DSL service are larger in number and is found to have less churn rate compared to Fibre optic service
5. Customers without dependents and customers who have partners are more likely to churn while senior citizens being the most of churn.
6. The absence of online security, Paperless Billing system and services with no TechSupport were the similiar trend are of the customers who are most likely churn.
7. There's a small fraction of customers who are more likely to churn and it's been found that they don't have a phone service.
8. High Monthly Charges are also one of a reason which makes Customers more likely to churn
9. High Total Charges are also one of a reason which makes Customers more likely to churn,there might be an issue with pricing system which needs to addressed
10. 

