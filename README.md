# Vrinda Stores Sales Analysis

Vrinda Store seeks to develop a detailed annual sales report for 2022. This report will offer crucial insights into customer behavior and sales trends, aiding the store owner in better understanding their customers and boosting sales in 2023.

By examining monthly sales performance, customer demographics, order statuses, and sales channels, the store can uncover key patterns and growth opportunities. Utilizing Excel's advanced data analysis and visualization features, this report will facilitate data-driven decisions to optimize operations, refine marketing efforts, and enhance overall business strategy.

This Analysis is done just by using EXCEL.

## Dataset Used

[Vrinda Store Raw Dataset](https://github.com/ShalikOP/Vrinda_Stores_Sales_Report_2022/blob/main/Vrinda_Stores_Raw_Dataset.numbers)

## Questions (KPIs)

- Compare sales and orders using a single chart.
- Identify the month with the highest sales and orders.
- Determine whether men or women purchased more.
- Examine the different order statuses in 2022.
- List the top 10 states contributing to sales.
- Analyze the relationship between age and gender based on the number of orders.
- Identify the channel contributing the most to sales.
- Determine the highest selling category.

## Process

### Data Cleaning

- Verify the data for missing values and anomalies, and resolve them.
- Ensure data consistency and cleanliness regarding data type, format, and values.

- Replaced M and W in gender column with Men and Women Respectively(Using Find and Replace).
- Replaced one,Two in Quantity Column with 1,2 Respectively(Using Find and Replace).

### Data Processing

- Made 2 new Column AgeGroup and MonthName for Conveniance.
- AgeGroup : (Senior — Above 50)|(Adult — between 30 and 50)|(Young — below 30)
       
- using : =IF(E2 >= 50, "Senior", IF(E2 >= "Adult", "Young"))

### Data Analysis

- Here we created many pivot Tables which were adressing to the Questions stated above.

### Dashboard

After all the analysis and visualization, we Merged all the charts and graphs on one sheet.
Also added Slicers for Month Channel and category to make the Dashboard Interactive

![App Screenshot](https://github.com/ShalikOP/Vrinda_Stores_Sales_Report_2022/blob/main/Vrinda_Store_Sales_Report_DashBoard.png)

## Project Insights

- Women customers are more likely to buy products compared to men (~65%).
- 92% Orders are Delivered, 3% are returned and 5% are either Cancelled or Refunded.
- Maharashtra, Karnataka, Uttar Pradesh, Telangana and Tamil Nadu are the top 5 states for product purchases.
- The adult age group (30-49 years) contributes the most (~50%) to product purchases.
- Most customers order products from Amazon, Flipkart, and Myntra channels.

## Inference/Conclusion

To enhance Vrinda Store's sales, focus on targeting women aged 30-49 in Maharashtra, Karnataka, and Uttar Pradesh with ads, offers, and coupons on Amazon, Flipkart, and Myntra.
