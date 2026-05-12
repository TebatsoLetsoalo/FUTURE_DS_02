# Bank Customer Retention & Churn Analysis Dashboard

## Dashboard link
View interactive dashboard: https://app.powerbi.com/groups/me/reports/a9c30f49-3821-49c5-8440-21ff5820da4b?utm_source=chatgpt.com&experience=power-bi 

## Project Overview 
This project analyses bank customer churn and retention patterns to answer key business questions such as:

1. Why are customers leaving the bank?
2. Which customer segments are most likely to churn?
3. How many customers are being retained versus lost?
4. Does customer engagement affect customer retention?
5. Does the number of banking products influence churn?
6. Do certain countries or demographic groups experience higher churn?
7. Does customer balance or financial behavior impact retention?
8. Are long-term customers more loyal than newer customers?
9. What actions can the bank take to improve customer retention and reduce churn?

## Tools used 

- Microsoft Power BI
- DAX
- Power Query

## Data Cleaning 

The dataset was cleaned and transformed using Power BI Power Query Editor to ensure data quality and consistency before analysis.

The following cleaning steps were performed:

* Checked for missing/null values across the dataset
* Verified and corrected column data types
* Removed duplicate records using the CustomerId column
* Checked and standardized text consistency
* Converted binary values (0/1) into readable labels:
     * Active Member: Yes / No
     * Has Credit Card: Yes / No
     * Churn Status: Churned / Retained
       
These cleaning steps improved the accuracy, readability, and usability of the dataset for customer churn and retention analysis.

## Key Insights from analysis

1. The overall customer churn rate was 20.40%, with 204 customers leaving out of 1,000 customers analyzed.
2. The customer retention rate was 79.69%, indicating that the majority of customers remained with the bank.
3. France recorded the highest number of churned customers (77), followed closely by Germany (75), suggesting possible regional differences in customer satisfaction, competition, or service engagement.
4. Customers aged 41–50 showed the highest churn levels, while customers under 30 were the least likely to churn.
5. Female customers demonstrated higher churn levels compared to male customers.
6. Inactive customers were significantly more likely to leave the bank, indicating that customer engagement strongly influences retention.
7. Customers using multiple banking products were less likely to churn, suggesting that higher product engagement improves customer loyalty.
8. Newer customers showed higher churn patterns compared to long-term customers, indicating challenges in early customer retention.
9. Customers with high account balances showed higher churn levels, followed by customers with no balance, suggesting that both high-value and disengaged customers may require targeted retention strategies.

## Bank Recommendations

1. Improve customer engagement strategies for inactive customers through personalized communication, loyalty campaigns, and regular account activity incentives.
2. Encourage customers to adopt multiple banking products, as customers using more products showed stronger retention behavior and lower churn levels.
3. Develop targeted retention strategies for customers aged 41–50, since this group demonstrated the highest churn levels.
4. Strengthen customer relationship management in high-churn regions such as France and Germany by investigating customer satisfaction, service quality, and competitor influence.
5. Implement onboarding and early-retention programs for newer customers, as newer customers showed a higher likelihood of leaving the bank.
6. Closely monitor high-balance customers and provide premium retention strategies, as high-value customers demonstrated unexpectedly high churn behaviour.
7. Re-engage customers with zero or low balances through personalized financial products, account activity campaigns, or tailored banking solutions.
8. Use predictive churn monitoring and customer segmentation to proactively identify at-risk customers before they leave the bank.



