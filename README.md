# Retention Analysis of Transaction

## 🗂️ Project Overview
In this project, I will analyze the customer retention rate based on transaction data. The goal is to understand how well the business retains its customers over time. This analysis will help me identify repeat purchase patterns, factors influencing retention, and opportunities to enhance customer loyalty.

[Analysis Data](https://github.com/Sopyaan/Retention-Rate-Analysis/blob/main/Retention_Analysis.ipynb) 

## 🎯 Objectives
1. Calculate Retention Rate: Measure the percentage of customers who return to make a purchase within a specific period.
2. Identify Retention Trends: Analyze time-based patterns and customer characteristics that contribute to retention.
3. Provide Recommendations: Develop strategies based on retention insights to improve customer loyalty.

## 📊 Data Description
The dataset contains the following information:

- Transaction Details: Includes transaction data, such as dates, transaction IDs, and order statuses.
- Customer Details: Contains customer IDs to track repeat purchases.
- Product Details: Information about purchased products, including brand, product line, and pricing.
- Order Details: Covers order status (online/offline) and order size.
  
Analysis Steps:
- Identify unique customers in each period (monthly/yearly).
- Track repeat purchases from unique customers in the subsequent period.
  
Calculate the retention rate as:
Retention Rate = Number of Returning Customers / Number of Customers in the Previous Period × 100 %

## 🌟 Adventure Works: Comprehensive Performance Report
<p align="center">
  <img src="https://github.com/Sopyaan/Retention-Rate-Analysis/blob/main/images/Cuplikan%20layar%202025-01-08%20063835.png", width="" height="">
</p>

### Retention Rate Over Time:
- Across most cohorts, the retention rate declines gradually in the second and third months.
The April 2017 cohort stands out with the highest 3rd-month retention rate (46%), suggesting effective engagement strategies or product launches during this period.

### Strong Recovery in July 2017:
- The July 2017 cohort displays a peak retention rate of 48% in the 4th month. This indicates a significant effort or event that successfully re-engaged users during this timeframe.
  
### Long-Term Retention Stability:
- Retention rates stabilize around 37–39% in the later months (10th to 12th) for many cohorts, showcasing consistent user loyalty over time.

<p align="center">
  <img src="https://github.com/Sopyaan/Retention-Rate-Analysis/blob/main/images/Cuplikan%20layar%202025-01-08%20064009.png", width="" height="">
</p>

### Peak Transaction Frequency:
- The highest number of customers completed 5-6 transactions, with over 600 customers in this range. This indicates a sweet spot where customers are most engaged.
  
### Right-Skewed Distribution:
- The chart displays a right-skewed distribution, meaning most customers tend to have fewer transactions, while a smaller number of customers are highly active with 10+ transactions.
  
### Declining Frequency with Higher Transactions:
- As the number of transactions increases beyond 6, the frequency drops significantly. Few customers reach 12-14 transactions, suggesting it is challenging to keep customers consistently engaged at higher levels.
  
### Customer Base Segmentation:
- The majority of customers fall within the 2-8 transaction range, making this group a key target for retention and upselling strategies.

## 📋 Actionable Recommendations
### Strengthen Early Retention (First 3 Months)
- Retention rates drop significantly after the second month. The actions are Implement personalized onboarding emails or campaigns for new customers to encourage repeat purchases early. Offer "welcome back" discounts or limited-time promotions for customers who haven’t made a second purchase within the first 60 days.
Introduce loyalty programs that reward repeat purchases within the first 3 months.

### Build on the Sweet Spot (5-6 Transactions)
- Most customers complete 5-6 transactions, making it a key engagement point. The actions are Design tiered loyalty rewards to encourage customers to move from 5-6 transactions to 7-8.
  
### Optimize for the 2-8 Transaction Range
- Most customers fall in this range, making it vital for upselling and retention. Use data to create product bundles that encourage larger purchases.
Follow up after purchases with tailored product suggestions.

### Monitor and Reduce Churn
- Retention drops after the initial peak periods.Build churn prediction models to identify customers at risk of leaving.
Offer subscription-based perks to promote consistent repeat purchases.

### Enhance Customer Segmentation
- Different engagement levels require tailored strategies. Segment customers by transaction frequency and create customized approaches for each group.
Focus retention efforts on mid-tier customers (4-6 transactions) to move them up.

