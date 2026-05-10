## Retail-Marketing-A-B-Testing-Analysis
<div align="center"> <img src="https://github.com/user-attachments/assets/53408a4d-a9c2-4f0e-a0df-e37db0b9c9b3" alt="ab-testing-2" width="500"/> </div>

### Project Overview
This project focuses on analyzing a Retail Marketing A/B Testing campaign to understand how advertisements influence customer conversions. The analysis compares the performance of two groups:

Ad Group → Users who were shown advertisements.
PSA Group → Users who were shown Public Service Announcements (control group).

The project uses data analysis, visualization, hypothesis testing, and machine learning techniques to identify whether advertisements improve customer conversion rates.

### Problem Statement
Retail businesses invest heavily in marketing campaigns, but it is important to know whether advertisements actually increase customer conversions.
The main objective of this project is to:
- It compares the conversion performance between Advertisement (Ad) and PSA groups.
- It analyzes the impact of ad exposure on customer behavior.
- It identifies the best days and hours for customer conversions.
- It predicts customer conversion behavior using Logistic Regression.
- It helps businesses make better data-driven marketing decisions.

### Dataset Features
- user id	Unique ID of each customer
- test group	Group type (ad or psa)
- converted	Whether the user converted or not
- total ads	Total number of ads seen by the customer
- most ads day	Day with highest ad exposure
- most ads hour	Hour with highest ad exposure
  
### Analytical Approach
The project was completed using the following analytical steps:
- Data Understanding and Exploration
- Data Cleaning and Preprocessing
- Campaign Performance Comparison
- Conversion Analysis by Day and Hour
- Ad Exposure vs Conversion Analysis
- Hypothesis Testing
- Logistic Regression Modeling
- Data Visualization and Insights

These visualizations help identify trends, patterns, and relationships within the dataset.

### Hypothesis Testing
Hypothesis testing was performed to determine whether there is a statistically significant difference between the Ad group and PSA group.

- Null Hypothesis (H0): There is no significant difference between the Ad and PSA groups.
- Alternative Hypothesis (H1): There is a significant difference between the Ad and PSA groups.

The analysis showed that the p-value was less than 0.05, leading to the rejection of the null hypothesis.

### Regression Analysis
A Logistic Regression model was used because the target variable (converted) contains binary values (True/False).
The model helps:

- Predict customer conversion behavior.
- Understand the relationship between ad exposure and conversions.
- Estimate conversion probability based on the number of ads viewed.

### Key Insights
- The Ad group achieved higher conversion rates than the PSA group.
- Higher ad exposure increased the probability of customer conversion.
- Certain days and hours generated better conversion performance.
- Customer engagement changes depending on campaign timing.
- Statistical testing confirmed the effectiveness of advertisements.

### Future Work
This project can be improved further by:
- It's using larger detailed datasets.
- It will add customer demographic information.
- It will apply advanced machine learning models.
- The project will include performing time-series forecasting for better trend prediction.
- It will also focus on building interactive dashboards using Power BI or Tableau.
- Future enhancements will involve optimizing marketing budget allocation strategies.

### Conclusion
This project demonstrates how A/B testing can help retail businesses evaluate the effectiveness of marketing campaigns.
The analysis proved that advertisements positively influence customer conversions and customer engagement. 
By identifying high-performing days, hours, and ad exposure levels, businesses can improve marketing strategies and optimize campaign performance.

Overall, this project highlights the importance of data-driven decision-making in retail marketing.
