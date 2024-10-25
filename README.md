# Project Title: LITA-Class-on-Pivot-Table

## Project Preview
This project focuses on leveraging pivot tables in Excel to analyze business performance across multiple dimensions, including regions, business lines, and stores. The dataset contains key columns such as Line of Business, Day Category, Revenue, and Units Sold, with an additional column for Transaction Category derived using an Excel formula. By creating various pivot tables, we aim to uncover insights into revenue generation, top-performing regions and stores, and sales trends across different categories. Visualizations such as bar charts help illustrate these insights, making them easier to interpret and apply to decision-making.
#### Project Highlights:
- Dataset: Analyzed sales performance across six regions using columns like Line of Business, Day Category, Revenue, Units Sold, and Transaction Category.
- Pivot Tables: Created pivot tables to summarize key metrics such as region-wise revenue, top-performing stores, and line of business comparisons.
- Visualizations: Generated bar charts to visually compare revenue across regions for better insight.
#### Project Strengths:
- Comprehensive Analysis: The use of pivot tables allows for quick aggregation and comparison of critical metrics.
- Data-Driven Insights: Leveraging Excel functions and pivot tables ensures reliable categorization and trend analysis.
- Effective Visual Representation: Graphical visualization of data (e.g., revenue by region) makes it easier to interpret and present findings.

## Project Objective
The objective of this project is to derive meaningful insights into business performance and sales trends using pivot tables. By analyzing the dataset, the project aims to:
- Identify high-performing regions in terms of revenue generation.
- Highlight the top stores and markets based on sales and revenue.
- Examine sales patterns across different lines of business and transaction categories.
- Provide a clear comparison of units sold and average revenue for various business segments.

## Project Significance
This project underscores the importance of using Excel for business data analysis, particularly through pivot tables. Pivot tables enable efficient summarization and visualization of large datasets, allowing businesses to:
- Quickly spot trends and patterns in sales performance.
- Make informed, data-driven decisions to improve operations, marketing, and sales strategies.
- Compare performance across regions, stores, and product lines, optimizing resource allocation and strategic planning.

## Methodology
#### Dataset Overview:
The dataset includes key columns such as:
- Line of Business: Represents different business categories or sectors.
- Day Category: Classifies sales days into different segments.
- Revenue: Total sales or income generated.
- Units Sold: Quantity of items sold.
- Transaction Category: This was derived using the Excel formula: =IF(J2 <= 20, "Low", IF(J2 <= 50, "Medium", "High")), which categorized transactions based on their revenue.
#### Steps for Analysis:
1. Data Preparation:
- Imported the dataset into Excel.
- Used Excel’s formula to create a new column for the Transaction Category based on the revenue data.
2. Pivot Table Creation:
 Generated multiple pivot tables to summarize and analyze key metrics:
- Region vs. Sum of Revenue: To understand regional sales performance.
- Top 10 Stores by Revenue: Identified the highest revenue-generating stores.
- Line of Business vs. Average of Revenue and Units Sold: Analyzed business line performance in terms of revenue and units sold.
- Region vs. Sum of Units Sold: Compared units sold across regions.
- Top 5 Markets by Revenue: Highlighted top-performing markets.
- Line of Business vs. Sum of Revenue: Evaluated the total revenue for each business line.
- Top 5 Stores by Units Sold: Showed which stores sold the most units.
- Model by Sum of Revenue: Reviewed the revenue performance by different business models.
3. Data Visualization:
Bar Charts: Created visual representations to compare revenue and other metrics across different regions and categories, making it easier to draw insights.
#### Tools Used:
- Microsoft Excel: For data manipulation, pivot table creation, and visualization.
- Formulas: Used Excel formulas to enhance the dataset and derive transaction categories.

## Disussion of Results
![pivot1](https://github.com/user-attachments/assets/3f72ce39-ba39-40c5-870c-068c64ebf08c) ![graph1](https://github.com/user-attachments/assets/f5b5a90b-9c7d-4921-bdc6-a0dfb3d74699)
### Revenue by Region:
- North East: Highest revenue at ₦18.64 billion.
- South West: Second, with ₦15.88 billion.
- South South: ₦12.18 billion.
- South East: ₦10.46 billion.
- North West: ₦9.39 billion.
- North Central: Lowest revenue at ₦6.49 billion.
#### Key Insights:
- North East leads in revenue, contributing about 25% of the total.
- North Central presents an opportunity for growth as it has the lowest revenue.
- Total Revenue: ₦73.03 billion across all regions.
- The chart visually confirms these trends, with North East and South West clearly standing out.
#### Recommendations:
- Leverage North East's Success: Invest in maintaining and growing sales in the North East by improving product availability and marketing.
- Enhance South West's Revenue: Expand product lines and promotions in the South West to capitalize on its strong performance.
- Boost North Central: Focus on growth strategies like targeted promotions in North Central, which has the lowest revenue.
- Regional Campaigns: Use localized marketing efforts in South East, South South, and North West to increase engagement and sales.
- Optimize Distribution: Ensure efficient distribution in underperforming regions to improve product availability and responsiveness.

### Top 10 Stores by Revenue 
![pivot2](https://github.com/user-attachments/assets/166ebed8-48a0-43de-a27a-e79ad9d55d84)   ![graph2](https://github.com/user-attachments/assets/aaab5443-768d-4a89-a849-9bab9df07a17)


#### Key Insights:
Ankpa leads with ₦1.7 billion in revenue, followed by Ajaokuta and Arochukwu at ₦1.4 billion each.
The total revenue from the top 10 stores is ₦11.8 billion, with Nembe, Ekiti East, and others contributing between ₦0.9 billion - ₦1.2 billion.
Ankpa stands out, but revenue is fairly well-distributed among the top stores.
#### Recommendations:
- Focus on High Performers: Strengthen operations and marketing in Ankpa, Ajaokuta, and Arochukwu to sustain and boost their top performance.
- Explore Growth Potential: Investigate why Bauchi and Askira/Uba have lower revenues and develop strategies to improve sales in these locations.
- Expand Top Performers’ Model: Consider replicating successful strategies from high-performing stores in other regions.

### Line of Business by Average Revenue and Units Sold
#### Key Insights:
- Service Plan leads in average revenue with ₦4.2 million, followed by Copier Sale with ₦3.3 million and Printer Sale with ₦2.6 million.
- Parts has the highest average units sold (35.54), despite contributing the lowest revenue (₦0.5 million), suggesting lower margins or pricing per unit.
- Copier Sale and Printer Sale show moderate sales but higher average revenue per unit.
#### Recommendations:
Optimize Parts Pricing: Review pricing strategies for Parts, as its high unit sales do not translate into higher revenue.
Leverage Service Plans: Focus on expanding Service Plan offerings, as they yield the highest average revenue per unit.

### Region by Sum of Units Sold 
#### Key Insights:
The table shows the total units sold across different regions:
- North East leads with 208,983 units sold, making it the top-performing region in terms of sales volume.
- South West follows with 169,730 units, contributing significantly to the total.
- South South and South East also perform well, with 126,189 and 122,240 units sold respectively.
- North West sold 105,014 units, while North Central has the lowest at 54,522 units.
#### Recommendations:
- Focus on North East: The high sales in the North East indicate strong demand. Consider bolstering supply chain operations in this region to maintain momentum.
- Expand in South West: With a solid number of units sold, further marketing or promotional efforts could help increase sales.
- Address Lower Sales in North Central: Investigate potential factors behind the lower performance in North Central and develop strategies to boost sales in the region.

### Top 5 Markets by Revenue 
#### Key Insights
The top 5 markets by revenue contribute a total of ₦22.8 billion:
- Ekiti leads with ₦5.6 billion, making it the highest revenue-generating market.
- Abia follows with ₦5.0 billion, closely competing with Ekiti.
- Bayelsa and Akwa Ibom contribute ₦4.2 billion and ₦4.1 billion respectively.
- Kogi rounds out the top five with ₦3.8 billion.
#### Recommendations:
- Strengthen Ekiti and Abia: Focus on sustaining and growing revenues in these top two markets through targeted promotions and customer engagement strategies.
- Leverage Bayelsa and Akwa Ibom's Potential: Explore opportunities to further increase revenue in Bayelsa and Akwa Ibom, as they show strong performance but have room for growth.
- Growth Strategy for Kogi: While performing well, Kogi could benefit from additional investment in marketing and infrastructure to push revenue further.

### Bottom 5 Stores by Units Sold  
#### Key Insights
The table displays the bottom 5 stores based on units sold, contributing a total of 102 units:
- Boki and Kwali have the lowest sales with only 2 and 4 units sold, respectively.
- Chibok and Isiala Ngwa South sold 42 and 54 units, which are still quite low compared to other stores.
#### Recommendations:
- Investigate Low Performers: The stores in Boki and Kwali are underperforming with minimal sales. It is essential to assess the factors leading to these low numbers, such as lack of demand, inventory issues, or weak local presence.
- Boost Sales in Chibok and Isiala Ngwa South: Develop targeted marketing campaigns or promotions to increase awareness and sales in Chibok and Isiala Ngwa South.
- Evaluate Product Offerings: Consider evaluating whether the product mix in these low-performing stores aligns with local market demand. Adjusting the product offerings might help improve performance.

### Revenue by Model 
#### Key Insights
The total revenue across all models amounts to ₦73.0 billion, with the following highlights:
- 3002P is the top revenue generator with ₦26.2 billion, contributing significantly to the total.
- 4500C follows with ₦16.7 billion, while 2500C and 3002C bring in ₦7.5 billion and ₦7.3 billion respectively.
- Models 2500P and 5001P also perform well, generating ₦6.1 billion and ₦4.7 billion.
- 4055T and 4500P bring in smaller amounts of ₦1.2 billion and ₦1.5 billion, while 5001C generates ₦1.8 billion.
#### Recommendations:
- Focus on High Performers: Prioritize maintaining and enhancing performance for top models like 3002P and 4500C, which are driving the bulk of revenue.
- Review Strategy for Lower Performers: Evaluate the performance of models like 4055T, 4500P, and 5001C to identify opportunities for improvement, either through marketing, pricing adjustments, or product enhancements.
- Expand Popular Models: Consider increasing production and availability for models like 3002P and 4500C to capitalize on their strong market demand.

### 






















