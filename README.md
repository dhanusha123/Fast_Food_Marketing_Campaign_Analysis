# Cracking the Code of Consumer Spending: A Data-Driven Analysis of Purchasing Patterns

## Introduction 

In today’s data-driven world, marketing campaigns are evolving to be more targeted and efficient. This analysis aims to understand how different promotional strategies impact sales across various market sizes and store characteristics. By leveraging data insights, businesses can optimize marketing spends and design campaigns that generate the highest returns.
This article will take you through the journey of analyzing a marketing campaign dataset — starting with data cleaning, through exploratory analysis, and finally, extracting insights that drive actionable recommendations.

## Data Overview
The dataset used for this analysis contains information about a marketing campaign, focusing on sales (SalesInThousands) across multiple weeks, promotions (Promotion), market size (MarketSize), and store characteristics like AgeOfStore. The data provides a rich context for understanding the effectiveness of different promotional tactics and how they vary across market segments.
![image](https://github.com/user-attachments/assets/1c8bb595-ccf5-4291-83d2-3712387c5337)

A quick summary of the dataset:
Variables: Promotions, sales, market size, week, store age.
Dataset Quality: The initial inspection included checks for missing values, duplicates, and a summary of key metrics. Data visualization was extensively used to identify patterns and outliers.

The diversity in promotional tactics and the information on weekly trends and store demographics allowed to build a comprehensive understanding of what drives sales for each segment.

## Data Cleaning and Preprocessing
The first step in this analysis was to ensure data quality. As the initial step, checked for missing values and duplicates, which, if not handled, could lead to incorrect conclusions.
Missing Values: Analysis revealed some missing data, which was either imputed or excluded based on its potential impact.
Duplicates: Duplicate records were minimal, and these were removed to prevent skewing the analysis.
Outlier Analysis: A boxplot was used to identify outliers in the sales data (SalesInThousands). Handling these outliers ensured that extreme values did not overly influence our results, especially during trend analysis and predictive modeling.
![image](https://github.com/user-attachments/assets/3dd17708-dc82-4dcf-9831-ed020b93cacf)

The data was then transformed to create more meaningful visualizations. For instance, categorical variables like Promotion were converted into factors for easier grouping, while numerical variables such as AgeOfStore and week were standardized for effective analysis.

## Key Insights from the Data
The heart of the analysis focused on uncovering patterns through exploratory data analysis (EDA) and visualizations. Here are some of the significant insights:

**1. Sales by Promotion:**
Promotion Effectiveness: Different promotions impacted sales significantly. Promotions aimed at higher market sizes saw distinct improvements in sales, which was evident from the boxplots visualizing sales distribution.
![image](https://github.com/user-attachments/assets/81d1b41c-92ca-410b-8255-a152c5ff4a31)
![image](https://github.com/user-attachments/assets/fec7a1e6-7234-4174-98dc-7e89c62fc0ef)

Promotional Timing: Weekly trends indicated that certain promotions were more effective during specific weeks, suggesting a temporal element in the customer response that businesses can leverage.
![image](https://github.com/user-attachments/assets/25a31e66-f7eb-4834-98ce-08e0a2fbb293)

**2. Market Size Analysis:**
Sales and Market Size: Larger markets saw a higher impact from promotional activities. A comparative boxplot analysis showed that while promotions worked across all market sizes, the relative increase in sales was more pronounced in larger markets.
![image](https://github.com/user-attachments/assets/832fdc02-f7e4-4448-8653-89d574503a90)

**3. Store Characteristics and Sales:**
Age of Store: The analysis explored the relationship between the store age and sales, indicating that older stores tended to perform differently based on the promotion type and market size. This insight is valuable for targeting stores for future campaigns.
![image](https://github.com/user-attachments/assets/ab4c6be3-e023-41b9-9601-67ffb470702c)

Linear Model for Age Impact: The use of linear models helped quantify the effect of store age on sales. Stores with medium age benefited most from certain promotions, showing a clear trend that could be capitalized on.

**4. Sales Distribution by Weeks:**
Weekly Sales Trends: Observed peaks in sales during particular weeks, highlighting the cyclical nature of the response to promotions. The boxplots and line charts provided a comprehensive view of how sales varied week by week, suggesting potential seasonal or situational influences.
![image](https://github.com/user-attachments/assets/4876872f-3f5c-4933-aea7-8079f1ef13c6)
![image](https://github.com/user-attachments/assets/6a89b3a3-c04d-40d4-b548-2235197782a1)

**5. Promotion vs. Market Size:**
Best Combinations: By grouping sales data by Promotion and MarketSize, identified the combination that generated the highest average sales. Certain promotions worked particularly well in large markets, making them suitable candidates for scaling campaigns.
![image](https://github.com/user-attachments/assets/538d54f7-8afb-44be-a104-4c5ab4b62d87)


## Summary and Business Recommendations
Based on the analysis, here are the derived recommendations:
Target Promotions by Market Size: Promotions should be tailored according to the market size. Large markets respond well to promotions with broader reach, while smaller markets may benefit more from focused, personalized campaigns.
Timing of Promotions: Promotions should be concentrated during weeks where sales historically show an upward trend. Aligning promotional campaigns with these weeks will likely boost sales due to heightened customer interest during these periods.
Focus on Store Demographics: Age-specific targeting could optimize promotional effectiveness. Stores that are neither too new nor too old benefit the most from specific promotions, suggesting that mid-aged stores should be prioritized for future campaigns.
Invest in Data-Driven Campaigns: Incorporating data-driven insights into campaign planning can enhance ROI. Sales densities and trends across different promotions provide a clear understanding of customer preferences, which can help refine promotional messages and offers.


## Final Thoughts
This marketing campaign analysis provided insights into optimizing promotional strategies by leveraging data on sales, market size, store characteristics, and customer response patterns. The visual exploration allowed us to understand which market segments to target and how promotions can be designed to achieve maximum impact.
The power of data lies in its ability to inform and drive decisions that align with business goals. With these insights, companies can now design campaigns that are more strategic, targeted, and likely to yield better results.


Data analytics is not just about understanding the past — it’s about shaping future business decisions to maximize efficiency and profitability.
Data Source: https://www.kaggle.com/datasets/chebotinaa/fast-food-marketing-campaign-ab-test
Image:https://images.app.goo.gl/oeMGoSf9dBSk5rLAA

**Explore the insights in the R Markdown file or the Medium article to gain a better understanding of consumer behavior through data analytics!**
link: https://medium.com/@dhanusha.viraj/from-boring-to-brilliant-using-data-to-supercharge-marketing-campaigns-and-win-big-1235c24efffb 
