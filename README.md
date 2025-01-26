# SQL Analysis Project: E-commerce Performance Insights
### **I. Project Assumption**
Our company runs business in E-Commerce field. Stakeholders have 8 questions to get more information of website performance, user behavior, and product sales metrics. As a data analst, I need to explore, analyze the data and give answers by using:
- Data source: bigquery-public-data.google_analytics_sample
- Data set: bigquery-public-data.google_analytics_sample.ga_sessions_20170801 
- Tool: Google Bigquery
### **II. Questions and Data Exploration**
1. What is total visits, pageviews, transactions for Jan, Feb and March 2017?
![image](https://github.com/user-attachments/assets/08296a42-6145-4b28-a644-c8909d3161f1)

2. What is bounce rate per traffic source in July 2017?
![image](https://github.com/user-attachments/assets/90cfcbbb-8118-4597-a6ac-9d876eacd0d9)

3. What is revenue by traffic source by week, by month in June 2017?
![image](https://github.com/user-attachments/assets/13865ad5-71b2-4643-ac5e-7dd99707a3f6)
![image](https://github.com/user-attachments/assets/b82d3455-60df-4062-9b5c-6894e4cba096)
![image](https://github.com/user-attachments/assets/5a17cdfb-f31f-4c4f-9ce5-e836eb8d55b6)

4. What is average number of pageviews by purchaser type (purchasers vs non-purchasers) in June, July 2017?
![image](https://github.com/user-attachments/assets/982241b0-4aaa-45fc-9a71-cb0efe015b92)
![image](https://github.com/user-attachments/assets/cfaaefb3-733b-4b35-a172-a92271164246)

5. What is average number of transactions per user that made a purchase in July 2017?
![image](https://github.com/user-attachments/assets/a1f67206-2ded-409d-a6a2-3af938f67a73)

6. What is average amount of money spent per session. Only include purchaser data in July 2017?
![image](https://github.com/user-attachments/assets/c8a12424-346e-44c6-862d-ac768d2e537c)

7. Which products are purchased by customers purchasing product "YouTube Men's Vintage Henley" in July 2017?
![image](https://github.com/user-attachments/assets/9dda8ff3-d183-4913-815b-f373908ed9e5)

8. What is cohort map from product view to addtocart to purchase in Jan, Feb and March 2017?
![image](https://github.com/user-attachments/assets/5b346a84-f773-448d-929c-040f2bdc4c3b)
![image](https://github.com/user-attachments/assets/bb9a3a6a-750d-40d9-b4b2-c916a270bbe7)

### **III. Technical skills**
- Common Table Expressions (CTEs)
- Aggregations (SUM, COUNT, ROUND)
- Window Functions
- Joins (LEFT JOIN, FULL JOIN)
- Filtering and Data Transformation
