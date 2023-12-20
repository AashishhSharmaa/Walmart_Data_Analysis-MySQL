# Walmart Data Analysis

This project analyzes Walmart Sales data to identify top-performing branches and products, studying sales trends and customer behavior. The goal is to optimize sales strategies through data-driven insights for sustained growth and market leadership.

![Walmart Sales ](https://github.com/AashishhSharmaa/Walmart_Data_Analysis-MySQL/assets/152653168/388fb1b1-79cf-4133-8fec-66fab47efffb)

## Challenge

The retail industry is dynamic and highly competitive, demanding continuous improvement in sales strategies to enhance overall performance. In this context, our project aims to delve into the vast realm of Walmart Sales data, with a specific focus on identifying the top-performing branches and products. By conducting a thorough analysis, we intend to pinpoint trends in the sales of various products and gain a nuanced understanding of customer behavior. These insights will form the foundation for addressing the critical challenge of optimizing and improving sales strategies within Walmart's diverse market landscape.

To achieve this goal, our project aims to leverage data-driven decision-making processes. By scrutinizing Walmart's sales data, we seek to unearth actionable insights that can inform strategic adjustments in the company's sales approach. The ultimate objective is to contribute to sustainable growth and market leadership for Walmart. Through this exploration, we anticipate not only enhancing the company's sales performance but also establishing a framework for ongoing refinement and adaptation in response to the ever-evolving dynamics of the retail industry.

### This project aims to address a diverse set of business questions related to Walmart Sales data:

### Generic Questions

1. How many unique cities does the data encompass?
2. In which city is each branch located?

### Product

1. How many unique product lines are present in the data?
2. What is the most common payment method?
3. Which product line is the highest selling?
4. What is the total revenue by month?
5. Which month had the highest COGS (Cost of Goods Sold)?
6. Which product line generated the highest revenue?
7. Which city yielded the highest revenue?
8. Which product line incurred the highest VAT?
9. Which branch exceeded the average number of products sold?
10. What is the most common product line based on gender?
11. What is the average rating for each product line?

### Sales

1. How many sales were made during each time of the day per weekday?
2. Which customer type contributes the most revenue?
3. In which city is the VAT (Value Added Tax) percentage the highest?
4. Which customer type pays the most in VAT?

### Customer

1. How many unique customer types are represented in the data?
2. How many unique payment methods are utilized in the data?
3. What is the most prevalent customer type?
4. Which customer type makes the most purchases?
5. What is the predominant gender among customers?
6. How is the gender distribution per branch?
7. During which time of the day do customers provide the most ratings?
8. During which time of the day do customers give the most ratings per branch?
9. Which day of the week receives the highest average ratings?
10. Which day of the week attains the best average ratings per branch?

## Approach Used

1. **Data Wrangling:**
   In the initial phase, thorough data inspection was conducted to identify and address any instances of NULL or missing values. A database was constructed, tables were created, and data was inserted. The absence of NULL values was ensured by setting the **NOT NULL** constraint during table creation. This meticulous process laid the groundwork for a clean and reliable dataset.

   > 1. Constructed a robust database.
   > 2. Created tables with a focus on data integrity.
   > 3. Detected and addressed NULL values, ensuring data completeness.

![Create Database and Table](https://github.com/AashishhSharmaa/Walmart_Data_Analysis-MySQL/assets/152653168/97fb7aad-110d-4e42-be31-61796f2a2903)

2. **Feature Engineering:**
   The feature engineering stage aimed to derive additional insights by creating new columns from existing data. This step enhances the dataset's richness and provides valuable information for addressing project objectives.

   > 1. Introduced the `time_of_day` column to categorize sales into Morning, Afternoon, and Evening, facilitating analysis of peak sales periods.
   > 2. Implemented the `day_name` column to extract and categorize transaction days by weekdays (Mon, Tue, Wed, Thur, Fri), aiding in understanding branch activity patterns throughout the week.
   > 3. Created the `month_name` column to extract and categorize transaction months, enabling exploration of monthly sales trends and profitability.

![Feature Engineering](https://github.com/AashishhSharmaa/Walmart_Data_Analysis-MySQL/assets/152653168/055eb7de-243e-4cc9-940f-86c787ed7d80)

3. **Exploratory Data Analysis (EDA):**
   Comprehensive exploratory data analysis was undertaken to address project-specific questions and objectives. This phase involved detailed examination of various aspects of the dataset to extract meaningful insights.

![EDA](https://github.com/AashishhSharmaa/Walmart_Data_Analysis-MySQL/assets/152653168/5eda2ed6-b8dd-4a60-b803-b865951f1023)

5. **Conclusion:**
   In conclusion, the adopted approach encompassed meticulous data wrangling, insightful feature engineering, and rigorous exploratory data analysis. By ensuring data completeness, creating informative features, and extracting meaningful patterns, this methodology provides a solid foundation for deriving actionable insights. The subsequent phases of the project can now build upon these foundations to address specific business questions and optimize strategies for enhanced performance and profitability.

## Skills Gained
1. **Data Wrangling Proficiency**
2. **SQL Database Management**
3. **Feature Engineering Expertise**
4. **Exploratory Data Analysis (EDA)**
5. **Time-Series Analysis Skills**
6. **Data Visualization Techniques**
7. **Business Question Framing**
8. **Critical Thinking and Problem Solving**
9. **Communication of Technical Findings**
10. **Strategic Analysis and Optimization**
