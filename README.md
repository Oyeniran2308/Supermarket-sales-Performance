## Project objective
_The primary objective of this analysis is to evaluate the sales performance of the business across multiple dimensions, including gender, product lines, cities, branches, and payment methods._

## Table of content
## Datasets
The growth of supermarkets in densely populated cities is increasing, and market competition is also high. The dataset used contains a historical sales data from a supermarket company recorded across three different branches over a three-month period.

Source: Kaggle (https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales)

**Key Fields:** 
- Date (Month, day)
- Branch
- City
- Gender
- Product line
- Unit Price
- Cost of goods sold
- Total sales
- Payment

## Tools and Technique used

• Tools: Microsoft Excel , Power BI, Google sheet (Query).

• Techniques

**Data Cleaning:** Microsoft excel was used to remove duplicate, check blank space, change 
the case and align columns.

**Data Visualization:** Measure table was created ('Measures' = ROW("measures", 
BLANK()) and under measure table some measures which help in the analysis was also 
created.

Female = CALCULATE(COUNTROWS('supermarket_sales - Sheet1'),'supermarket_sales - Sheet1'[Gender] = "Female")

Male = CALCULATE(COUNTROWS('supermarket_sales - Sheet1'),'supermarket_sales - Sheet1'[Gender] = "Male")

Total Sales = COUNT('supermarket_sales - Sheet1'[Invoice ID])

## Exploratory Data Analysiswhich month generates the highest revenue

- Which city has the highest sales performance contribution
- Identify the customer responsible for the highest singles sales
- which product line generate the most revenue and how significant is its compared to others
- Which product lines are more popular among male and female customers, and how does this affect overall sales performance?
- Analyze branch-level sales performance across different product lines to identify regional preferences and branch-specific strengths.
- Assess total sales performance by customer gender to determine which gender drives higher revenue

## Data Analysis

The dashboard contains key performance indicators (KPIs) such as total sales, the number of male and female customers, the product lines, and branch distribution. It also includes visualizations to showcase trends and patterns like:

**- City with the highest sales performance:** 

Sales transaction was carried out in three cities Naypyitaw, Yangon and Mandalay. Our analysis which was visualize with a stacked column chart reveals that sales performace are excellent at the three cities.
Customer with the highest sales: the dataset was queried using Google sheet, use the unique customer ID, we were able to get the customer wit the highest sales transaction.

**- Product line contribution:** analysis carried out among 6 product line show that people engage more with food and beverages more than other line of business, using the clustered column chart we were able to see the sales performance across the six line of product, with food and beverages ranking higher and health and beauty ranking lower sales; the six line of product all rank far above average justifying there performance is okay but theirs a little diffrence in sales.

**- Customer with the highest sales:** google query was used to get the customer with the highest sales.

**- Monthly sales performance:** the analysis carried out to check the monthly sales performance using a dough chart  to identify sales performance

- Branch-specific sales performance.
- Payment method preferences.


 **KPIs**
- Total sales : 1000
- Total sales made by male: 499
- Total sales made by female: 501
- Products line: 6 (food and beverages, sport and travel, electronic accessories, fashion accessories, home and lifestyle, health and beauty)
- Branch: 3 (A,B,C)
- Customer : Member and Normal

**Fig 1**
![Sheet 1](https://github.com/user-attachments/assets/eb0b68df-e34c-475b-84bb-3b0a205d04f8)

**Fig 2**
![sheet 2](https://github.com/user-attachments/assets/103c7d78-dc42-4867-83b4-3e84d107973e)


## Findings

**- Sales by City**
Sales performance is similar across Naypyitaw, Yangon City, and Mandalay, with no significant outlier indicating all cities contributed almost equally.

**Fig 3**
![sales performance by city](https://github.com/user-attachments/assets/70e2dd50-18c0-4db4-9ca4-8839f3cf45a1)

**- Customer with the highest sales order**

**-Sales by Product Line**

_Food and Beverages lead in sales, closely followed by Sports and Travel and Electronic Accessories.
All six product lines show strong sales contributions, suggesting a well-diversified revenue stream._

**Fig 4**
![sales destribution across product line](https://github.com/user-attachments/assets/c9cd3b2c-12d2-4ad2-9066-41470cc92065)

**-Branch Performance**
Branch C leads in overall sales performance, followed by Branch B and Branch A.
Home and Lifestyle performed best at Branch A, while Food and Beverages dominated in Branch C.

**-Fig 5**
![branch](https://github.com/user-attachments/assets/6fbba75e-5f9c-47b6-8bbc-a6a72e226b37)

**-Payment Methods**
Customers used E-wallets (34.74%) and Credit Cards (34.06%) almost equally, while Cash (31.2%) is slightly less preferred.

**-Fig 6**
![payment](https://github.com/user-attachments/assets/74085526-79be-4283-99d9-c2bb6db9eb17)


**-Monthly Sales Trend**

February has the highest sales compared to January and March. This suggests that specific marketing efforts or seasonal factors may drive higher sales during February.

**Fig 7**
![sales performance by month](https://github.com/user-attachments/assets/f53f4e6f-4ddd-4fcd-adba-4af93d6ea9d5)

**- Gender-Based Sales**
Male customers contributed slightly more (51.98%) to sales than female customers (48.02%).
Gender-based sales distribution across product lines shows a relatively balanced contribution but with slight variation in preferences.

![pie capstone](https://github.com/user-attachments/assets/3f18f552-fdf8-4570-a8fd-ec5297654c82)

## Recommendations
**- Enhance Gender-Specific Marketing:**

Design targeted campaigns for both male and female customers focusing on their slight product line preferences.
Use loyalty programs to attract male customers, given their slightly higher spending.

**- Regional Sales Strategy:**

Despite cities contributing equally, consider tailoring marketing campaigns to the specific culture and demands of each city to maximize engagement.

**-Product Line Optimization:**

Invest in promoting Food and Beverages, Sports and Travel, and Electronic Accessories as they are high-performing categories.
Explore product bundles or seasonal discounts to boost lower-performing product lines.

**-Branch Improvement Plan:**

Use insights from top-performing branches (Branch C) to improve sales strategies in weaker branches like Branch A.
Allocate resources to underperforming product lines at specific branches to balance overall sales.

**-Focus on Payment Preferences:**

Promote cashless transactions with incentives to maintain the growing trend of E-wallet and Credit Card usage.
Consider offering exclusive discounts or rewards for users of underutilized payment methods.

**Monitor Monthly Trends:**

Deep dive into February’s sales drivers to replicate success in future months.
Prepare for potential dips in March sales with proactive promotions.

## Conclusion

The analysis reveals a well-balanced sales distribution across gender, cities, and product lines. The consistency across branches and payment methods reflects strong operational strategies. However, opportunities exist to optimize specific areas such as marketing campaigns tailored to product line and gender preferences, enhancing branch-specific strategies, and leveraging payment method trends.

By implementing the recommendations, the business can further strengthen its sales performance, maximize revenue streams, and achieve a competitive edge in the market.







