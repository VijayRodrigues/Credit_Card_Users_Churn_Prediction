# Credit_Card_Users_Churn_Prediction


###  Description
### Context
The Thera bank recently saw a steep decline in the number of users of their credit card, credit cards are a good source of income for banks because of different kinds of fees charged by the banks like annual fees, balance transfer fees, and cash advance fees, late payment fees, foreign transaction fees, and others. Some fees are charged to every user irrespective of usage, while others are charged under specified circumstances.

### Objective
Customers’ leaving credit card services would lead the bank to loss, so the bank wants to analyze the data of customers and identify the customers who will leave their credit card services and the reason for same – so that the bank could improve upon those areas.

You as a Data Scientist at Thera Bank need to explore the data provided, identify patterns, and come up with a classification model to identify customers likely to churn, and provide actionable insights and recommendations that will help the bank improve its services so that customers do not renounce their credit cards.

### Data Description

Data Description
- CLIENTNUM: Client number. Unique identifier for the customer holding the account
- Attrition_Flag: Internal event (customer activity) variable - if the account is closed then "Attrited Customer" else "Existing Customer"
- Customer_Age: Age in Years
- Gender: The gender of the account holder
- Dependent_count: Number of dependents
- Education_Level:  Educational Qualification of the account holder - Graduate, High School, Unknown, Uneducated, College(refers to a college student), Post-Graduate, Doctorate.
- Marital_Status: Marital Status of the account holder
- Income_Category: Annual Income Category of the account holder
- Card_Category: Type of Card
- Months_on_book: Period of relationship with the bank
- Total_Relationship_Count: Total no. of products held by the customer
- Months_Inactive_12_mon: No. of months inactive in the last 12 months
- Contacts_Count_12_mon: No. of Contacts between the customer and bank in the last 12 months
- Credit_Limit: Credit Limit on the Credit Card
- Total_Revolving_Bal: The balance that carries over from one month to the next is the revolving balance
- Avg_Open_To_Buy: Open to Buy refers to the amount left on the credit card to use (Average of last 12 months)
- Total_Trans_Amt: Total Transaction Amount (Last 12 months)
- Total_Trans_Ct: Total Transaction Count (Last 12 months)
- Total_Ct_Chng_Q4_Q1: Ratio of the total transaction count in 4th quarter and the total transaction count in the 1st quarter
- Total_Amt_Chng_Q4_Q1: Ratio of the total transaction amount in 4th quarter and the total transaction amount in the 1st quarter
- Avg_Utilization_Ratio: Represents how much of the available credit the customer spent- 



### Table of contents
- [Project Overview](#Context)
- [Dataset](#Dataset)
- [Model Used](#Models_Used)
- [Model Performance](#Model_Performance)
- [Model Building - Oversampled data](#Model_Building_Oversampled_data)
- [Model Building - Undersampled data](#Model_Building_Undersampled_data)
- [Model Performance Improvement using Hyperparameter Tuning](#Model_Performance_Improvement_using_Hyperparameter_Tuning)
- [Actionable Insights & Recommendations](#Actionable_Insights_&_Recommendations)


### Dataset

[BankChurners.csv](https://github.com/user-attachments/files/17790926/BankChurners.csv)



### Models_Used

- DecisionTreeClassifier
- RandomForestClassifier
- AdaBoostClassifier
- GradientBoostingClassifier
- XGBClassifier





### Model_Performance
![image](https://github.com/user-attachments/assets/a2acbff6-3e5d-456c-83a7-419bdd739492)







### Model_Building_Oversampled_data

![image](https://github.com/user-attachments/assets/8000ce11-3eee-4221-81be-b0757b62abf5)






### Model_Building_Undersampled_data

![image](https://github.com/user-attachments/assets/0a74b2ed-c46c-4dc4-8501-fe3ebe7220bd)







### Model_Performance_Improvement_using_Hyperparameter_Tuning

##### Models Chosen:
- RandomForestClassifier
- GradientBoostingClassifier
- XGBClassifier

![image](https://github.com/user-attachments/assets/c85892b7-dede-4bc0-9845-737553ab4388)






### Actionable_Insights_&_Recommendations


##### Targeted Retention Strategies:
**1) High-Risk Customers:**
Focus retention efforts on customers with high balances, low transactions, and low credit usage by offering personalized products like balance transfers or credit limit increases.

**2) Re-engage Inactive Customers:**
Target customers who haven't been active in the last 12 months with special offers, financial reviews, or loyalty rewards to encourage more engagement.


##### Improve Customer Value Proposition:
**1) Upgrade Card Tiers:**
Encourage customers with basic cards to upgrade by offering additional benefits like rewards, travel perks, or cashback to increase satisfaction.

**2) Personalized Offers:**
Create customized offers based on customer profiles, such as premium services for higher-income customers.


##### Enhance Onboarding and Early Experience:
**1) First-Year Engagement:**
Start a program to engage customers in their first year to ensure they use the bank's services actively. Address early dissatisfaction through personalized offers or support.

**2) Customer Education:**
Simplify product offerings and provide clear financial advice to customers with lower education levels to encourage better use of services.


##### Increase Customer Interaction:
**1) Boost Engagement:**
Target customers with few interactions over the past year by offering personal finance consultations or alerts for potential savings to increase loyalty.

**2) Automated Retention:**
Set up automated outreach (emails, SMS, or calls) for customers who haven't interacted with the bank in a while to prompt re-engagement.


##### Leverage Predictive Modeling for Attrition:
**1) Early Warning System:**
Integrate the attrition prediction model into the bank's CRM to flag at-risk customers in real-time and offer personalized retention strategies.

**2) Targeted Retention Offers:**
Develop marketing campaigns based on customers' risk of leaving, focusing on retention for high-risk groups and premium services for loyal customers.


##### Loyalty Programs:
**1) Reward Long-Term Customers:**
Create loyalty programs that offer benefits like discounts, exclusive rewards, or lower interest rates for long-term customers.

**2) Family-Oriented Programs:**
Use the insight that customers with more dependents tend to stay longer by offering family-friendly banking packages, like joint accounts or special offers for dependents.


##### Customer Feedback Loop:
**1) Learn from Attrition:**
Gather feedback from customers who have left to understand why, and use this information to improve services.

**2) Engage Current Customers:**
Regularly survey current customers to identify any dissatisfaction early and prevent future attrition.


##### Cross-Sell and Up-Sell Opportunities:
**1) Family-Oriented Products:**
Offer financial products tailored to customers with dependents, like education savings plans or family insurance, to strengthen relationships.

**2) Premium Services for Loyal Customers:**
For highly engaged customers, offer premium banking services or wealth management options to deepen their connection to the bank.




