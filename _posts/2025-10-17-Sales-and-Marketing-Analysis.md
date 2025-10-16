---
layout: single
title:  "Sales and Marketing Analysis"
date:   2025-10-17
author: Bashirat Sulyman
categories: [excel]
tags: [excel, visualization, sales, beginner]
---
# Sales and Marketing Data Analysis

I explored this dataset to understand how discount levels, customer segments, and product categories affect sales and profit. 
It’s one of my early projects in data storytelling and Excel analysis showing how data can support business decisions.

### **Dataset Overview**
This dataset contains sales transaction records, including details like order date, discount, profit, region, and customer segment.  
It provides insights into how pricing, product category, and customer type affect sales performance.

---

### **Research Questions**
1. Does discount affect sales revenue?  
2. Which customer segments generate the highest revenue and profit?  
4. Which product categories are most popular in each region?

---

### **Data Cleaning Summary**
- Removed duplicates and ensured consistent date formatting  
- Grouped discounts into ranges: 0–10%, 10–20%, 20–30%, 30–40%, and 40%+  
- Created PivotTables to summarize sales, profit, and quantity  
- Used calculated fields to find average order value per customer segment  

---

### **Key Analysis and Visuals**
#### **Impact of Discount on Sales and Profit**
The analysis shows that discounts between 0–10% generated the highest sales revenue and profit. As the discount percentage increased, both total sales and profit decreased significantly. From this, we can deduce that discount does affect sales revenue but in proportions. 
Discounts above 30% resulted in losses, with negative profit values despite moderate sales.This means that higher discounts do not necessarily boost sales revenue and have a negative impact on profitability. Therefore, moderate or low discounts appear to be the most effective for maintaining both sales and profit levels.
![Impact of Discount on Sales and Profit](assets/images/chart-2.JPG)


#### **Revenue and Profit by Customer Segment**
The Consumer segment drives the highest sales and profit.  
Encouraging more frequent purchases from these customers can further boost revenue.  

![Revenue and Profit by Customer Segment](assets/images/chart-one.JPG)


#### **Most Popular Product Categories by Region**
Across every region, Office Supplies consistently had the largest number of items sold, which shows a strong demand compared to Furniture and Technology. 
This indicates that customers across all regions need and purchase office-related products more frequently than other categories.
  
![Most Popular Product Categories by Region](assets/images/chart-3.JPG)


---

### **Insights and Conclusions**
Moderate discounts (0–10%) produced the highest sales and profits.
Consumers remain the biggest revenue drivers with frequent purchases.
Home Office customers place smaller orders but spend more each time.
Office Supplies were the most purchased category across all regions, with the West region leading overall.

**Overall, the data suggests that profitability is influenced more by how often customers buy than by how much discount they receive or how large each order is.**



---

### **Limitations and Future Work**
- Limited to sales data; customer demographics not included  
- Further analysis could explore how delivery time or product type affects repeat purchases  
