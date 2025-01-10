# Online Retail Analysis

This project conducts a comprehensive data analysis of online retail transactions, exploring customer behavior, product popularity, and sales patterns. By examining a dataset of online purchases, I aim to identify trends, uncover interesting patterns, and draw actionable conclusions. The insights gained will help optimize pricing strategies, inform marketing decisions, and enhance understanding of customer preferences in the online retail space.


## Dataset Content
The dataset contains information on customer transactions made through an online retail platform. It includes data on products purchased, quantities, transaction dates and times, prices, customer identifiers, and customer locations. The dataset is sourced from Kaggle: Online Retail Transactions Dataset.


## Business Requirements
* Understand customer purchasing patterns and behavior
* Identify top-selling products and their characteristics
* Analyze sales trends over time
* Examine the geographic distribution of sales
* Investigate the relationship between product pricing and sales volume


## Project Plan
* Data Extraction: Load data from the CSV file.
* Data Cleaning: Handle missing values, remove negative quantities and prices
* Data Transformation: Create new features like TotalTransactionValue
* Exploratory Data Analysis: Generate basic statistics and information about the dataset
* Data Visualization: Create various charts and graphs to visualize key insights
* Key summaries from basic data analysis
* Advanced Data Analysis & Visualizations
* Provide final conclusions & recomendations based on data analysis

## The rationale to map the business requirements to the Data Visualisations
* Monthly Sales Trend: Addresses requirement 3
* Top 10 Countries by Sales: Addresses requirements 4 and 5
* Customer Purchase Frequency: Addresses requirement 1
* Product Price Distribution: Addresses requirements 2 and 5
* Correlation Heatmap: Addresses requirements 1, 2, and 5

## Analysis techniques used
* Descriptive statistics.
* Time series analysis.
* Correlation analysis.
* Distribution analysis

## Development Roadmap
* What challenges did you face, and what strategies were used to overcome these challenges?

Sometime the notebooks were running very slow or having errors, requiring me to re-install pandas, and other libraries.  Not sure sure exactly why this was happening.  But I fixed the issues in the end.

## Deployment
* The project is currently running in a Jupyter Notebook environment. Future plans could include deploying it as a web application.

## Main Data Analysis Libraries
* pandas: For data manipulation and analysis
* matplotlib: For creating static visualizations
* seaborn: For statistical data visualization
* numpy: For numerical computing

## Credits 

* Dataset source: Kaggle 

## Content 

* Dataset source: Kaggle 

## Executive Summary

This project focuses on analyzing online retail transaction data to understand customer behavior and improve sales strategies. Over two days, I worked on extracting, cleaning, and visualizing data sourced from Kaggle.

I started by loading the dataset from a CSV file and ensuring its accuracy by fixing missing values and removing duplicates. This was essential for reliable analysis. I also calculated new features, such as the total transaction value for each purchase.

On the second day, I created various visualizations using libraries like Matplotlib, Seaborn, and Plotly. Key visualizations included an interactive line chart showing daily sales trends and a heatmap displaying sales patterns by day of the week and hour. I also developed a scatter plot to explore the relationship between quantity sold and price across different countries, along with a treemap illustrating sales distribution by country and product category. Finally, I created a 3D scatter plot for customer segmentation based on Recency, Frequency, and Monetary value.

The insights gained from this analysis are valuable for shaping marketing strategies and optimizing product offerings. Understanding peak sales periods can enhance inventory management, while identifying popular products can guide promotional efforts.

Overall, this project demonstrated my ability to apply ETL processes and data visualization techniques to derive meaningful insights from online retail data.

## Final Conclusions & Recomendations

Based on the analysis and visualizations from my project, I have drawn several personalized conclusions and recommendations specifically tailored to the insights gathered:

### Daily Sales Trends

The interactive line chart revealed clear trends in daily sales, with notable peaks during holiday seasons. Businesses should capitalize on these peak periods by ramping up marketing efforts and ensuring adequate stock levels to meet increased demand.

### Sales Patterns by Time

The heatmap displaying sales patterns by day of the week and hour highlighted specific times when sales are highest. This insight can guide targeted marketing campaigns, allowing businesses to focus their promotions during peak sales hours for maximum impact.

### Pricing Strategies

The scatter plot exploring the relationship between quantity sold and price across different countries showed how pricing affects customer purchasing behavior. Businesses should consider adjusting their pricing strategies based on regional preferences to optimize sales.

### Product Performance

The treemap illustrated the distribution of sales by country and product category, helping identify top-performing products and markets. This information can inform inventory decisions and marketing strategies, ensuring that popular products are well-stocked and promoted effectively.

### Customer Segmentation

The 3D scatter plot for RFM (Recency, Frequency, Monetary) segmentation provided insights into customer purchasing behavior. Businesses can use this information to tailor their marketing efforts, focusing on high-value customers with personalized promotions to enhance customer loyalty.

## Acknowledgements 
* Thank the people who provided support through this project.