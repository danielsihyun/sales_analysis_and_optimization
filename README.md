*Disclaimer: This project uses sample data for demonstration purposes only. No personally identifiable information (PII) is included in the dataset.*

---

**Overview**  
This project analyzes historical customer sales data for a leading fashion retailer. The goal is to uncover insights related to customer purchasing behavior, product affinity, segmentation, and sales performance, and to generate actionable business strategies to drive customer retention and increase revenue.

*Note: This analysis uses sample data. No personally identifiable information (PII) is present in the dataset.*

---

**Contents**  
1. Data Cleaning  
2. Sales Overview  
3. Customer Behavior  
4. Product Affinity  
5. Customer Segmentation  
6. Business Strategy Recommendations  

---

**1. Data Cleaning**  
Initial preprocessing focused on ensuring data quality by addressing:  
- Null values (e.g., gender, city, province, coupon, birthday)  
- 'Undefined' entries  
- Duplicate rows  
- Revenue outliers (unrealistically high or zero revenue)  

Key result:  
- 87.5% of sales account for 99% of revenue after cleaning

---

**2. Sales Overview**  
- Total Orders: 102,460  
- Total Revenue: $14.136M AUD  
- Average Order: 2.03 items, $137.97 revenue  
- Unique Items per Order: 1.98  

Breakdowns provided by:  
- Province and City  
- Time of Day and Hour  
- Payment Type and Day of Week  

---

**3. Customer Behavior**  
- 87.6% of customers only made one purchase  
- Drop-off among return customers is steep  

Potential reasons:  
- Product quality or sizing issues  
- Lack of variety or trends  
- Satisfying purchases that don’t require repeat orders  

Frequent buyer analysis by:  
- Payment Type  
- Gender  
- City and Province  

---

**4. Product Affinity**  
Top frequently purchased product pairs:  
- Modern Cotton Thong + Bralette (majority female)  
- Bikini + Customized Stretch Bralette  
- Tee + Shorts (higher male representation)

Top bulk purchase items:  
- Staple Shorts (21% male)  
- Crew Tees, Sandals, and Caps  

---

**5. Customer Segmentation**

Group 1: Low Value, Single Purchase  
- Revenue: 101.29 AUD  
- Size: 65,099  

Group 2: Moderate Value, Single Purchase  
- Revenue: 303.91 AUD  
- Size: 11,954  

Group 3: Moderate Value, Multiple Purchases  
- Revenue: 265.61 AUD  
- Size: 9,623  

Group 4: High Value, Multiple Purchases  
- Revenue: 883.73 AUD  
- Size: 1,532  

---

**6. Business Strategy Recommendations**  

Product Bundle Offers  
- Bundle frequently bought-together items at a slight discount  

Cross-Selling  
- Suggest complementary products based on purchase history  

Time-Based Promotions  
- Peak Time Promos: Maximize revenue during peak hours  
- Happy Hour Deals: Drive sales during low-traffic times  

Customer Retention Campaigns  
- Loyalty Coupons: Incentivize second purchases  
- Win-Back Emails: Re-engagement offers based on time since last purchase  

---

**Closing Notes**  
This analysis lays the foundation for data-driven marketing and business strategies focused on improving customer lifetime value, increasing repeat purchase rates, and optimizing product offerings.

For code, visuals, and exploratory data analysis, refer to the accompanying Jupyter Notebook.

---
