# Cracking the Code of Consumer Spending: A Data-Driven Analysis of Purchasing Patterns

## Introduction 

In today’s data-driven world, marketing campaigns are evolving to be more targeted and efficient. This analysis aims to understand how different promotional strategies impact sales across various market sizes and store characteristics. By leveraging data insights, businesses can optimize marketing spends and design campaigns that generate the highest returns.
This article will take you through the journey of analyzing a marketing campaign dataset — starting with data cleaning, through exploratory analysis, and finally, extracting insights that drive actionable recommendations.

## Data Overview
The dataset used for this analysis contains information about a marketing campaign, focusing on sales (SalesInThousands) across multiple weeks, promotions (Promotion), market size (MarketSize), and store characteristics like AgeOfStore. The data provides a rich context for understanding the effectiveness of different promotional tactics and how they vary across market segments.
![image](https://github.com/user-attachments/assets/1c8bb595-ccf5-4291-83d2-3712387c5337)


## Data Cleaning and Preprocessing
The initial step involved cleaning the dataset by removing duplicates, correcting data types, and dropping non-essential columns. After ensuring the integrity of the data, proceeded to engineer new features. For example, added fields like Average Purchase Amount, Total Purchases, and Days Since Last Purchase to get a clearer picture of customer value and behavior patterns.

## Key Insights from the Data
1. High-Value Customers vs Low-Value Customers
One of the most crucial insights was differentiating between high-value and low-value customers. By categorizing customers with an average purchase above $75 as high-value, it was found significant behavioral differences between these two segments.
![image](https://github.com/user-attachments/assets/334cb0d6-91d0-4a0e-b096-ad0d3dcd5d12)
A t-test revealed a statistically significant difference in the purchasing amounts of high-value customers compared to low-value ones (p-value < 0.05). This suggests that a distinct group of customers consistently makes larger purchases, and businesses could benefit from loyalty programs or targeted promotions for this segment.

2. Gender-Based Spending Analysis
When analyzing the purchasing amounts by gender, it was found only a subtle difference, with female customers spending slightly more on average (≈ $60.25) compared to male customers (≈ $59.54). Though the difference is not significant, it still indicates a slight skew, which may be useful in fine-tuning marketing messages.
![image](https://github.com/user-attachments/assets/d8c3b4fd-8b5c-4144-b431-b056d68e69c1)

3. Relationship Between Discount Usage and Customer Value
Conducted a chi-square test to assess whether frequent discount usage was linked to being a high-value customer. Interestingly, the results showed no statistically significant relationship between the two, suggesting that high-value customers do not necessarily rely on discounts, but instead may be more loyal or satisfied with the brand’s offerings regardless of promotional incentives.

4. Age Group Analysis and Purchase Trends
Age is often a significant determinant of consumer behavior. Segmented our customer base into several age groups (<18, 18–35, 35–50, 50–65, and 65+). The analysis showed that customers in the 50–65 age group tend to have the highest average purchase amount, indicating that middle-aged individuals are more likely to make higher-value purchases.

Interestingly, younger customers (<18) and those between 18–35 also showed considerable spending, suggesting a strong potential market for younger demographics if appropriate marketing and product offerings are introduced.
![image](https://github.com/user-attachments/assets/9316a7ee-d84c-48ad-a493-e9ebf654b759)

Seasonal Trends and Payment Preferences
Seasonal Variations in Purchase Behavior
The analysis of seasonal trends indicated that Spring and Fall are peak seasons for purchasing. Customers tend to spend more during these periods, potentially due to new product launches, holidays, or weather changes influencing buying behavior. Understanding this pattern allows businesses to allocate marketing budgets strategically during these high-revenue months.

Payment Method Preferences
Analyzing payment method usage revealed that Credit Card was the most commonly used payment method, followed by PayPal and Bank Transfer. This insight helps businesses optimize their payment gateway options and ensure that they are providing convenient payment methods to maximize conversions.
![image](https://github.com/user-attachments/assets/b4601cfe-9b6b-4db3-ae88-cc85961d3c55)

## Visual Insights
To support the findings, various visualizations were created:

Correlation Heatmap: Highlighting relationships among numerical variables such as purchase amounts, customer age, and review ratings.
![image](https://github.com/user-attachments/assets/71829714-c517-43ae-bd13-36cef80225ca)

Category-Wise Sales Analysis: The Clothing category emerged as the top contributor to total sales, emphasizing its popularity among customers.
![image](https://github.com/user-attachments/assets/ec324688-d93c-4020-a00b-1047bde3c712)

Purchase Amount Distribution: This visualization showed a right-skewed distribution, indicating that while most customers make smaller purchases, a few high-value transactions have a substantial impact on overall sales.
![image](https://github.com/user-attachments/assets/d2d55ca3-9136-4c04-bdf5-e7f6e0356bc7)

## Summary and Business Recommendations
Target High-Value Customers: The significant difference between high and low-value customers emphasizes the need for businesses to cultivate relationships with high-value customers through loyalty programs or exclusive offers.
Seasonal Campaign Planning: Since Spring and Fall are peak seasons, businesses should plan promotions, inventory, and marketing efforts accordingly to maximize sales.
Age-Specific Marketing Strategies: Given that middle-aged customers are the most lucrative group, businesses could create premium offerings targeting this demographic, while also appealing to younger customers with trendy and affordable product options.
Payment Method Optimization: Considering that Credit Card is the preferred payment method, businesses should ensure that their payment systems are seamless and secure, encouraging customers to complete their purchases without friction.

## Final Thoughts
Data-driven insights provide an edge in understanding customer behavior and tailoring business strategies. This analysis sheds light on valuable customer segments, seasonal trends, and spending patterns that can inform both short-term campaigns and long-term strategic initiatives. With a well-informed approach, businesses can not only boost revenue but also create a more personalized and satisfying shopping experience for their customers.

Stay tuned for more data-driven articles that help bridge the gap between analytics and business strategy!

Data Source: https://www.kaggle.com/datasets/bhadramohit/customer-shopping-latest-trends-dataset/data
Image: https://camoinassociates.com/resources/navigating-shifts-in-american-consumer-spending/




**Explore the insights in the R Markdown file or the Medium article to gain a better understanding of consumer behavior through data analytics!**
link: https://medium.com/@dhanusha.viraj/from-boring-to-brilliant-using-data-to-supercharge-marketing-campaigns-and-win-big-1235c24efffb 
