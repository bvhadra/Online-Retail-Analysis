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


## Hypothesis and how to validate?
* List here your project hypothesis(es) and how you envision validating it (them) 

## Project Plan
* Data Extraction: Load data from the CSV file.
* Data Cleaning: Handle missing values, remove negative quantities and prices
* Data Transformation: Create new features like TotalTransactionValue
* Exploratory Data Analysis: Generate basic statistics and information about the dataset
* Data Visualization: Create various charts and graphs to visualize key insights

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

## Ethical considerations
* Were there any data privacy, bias or fairness issues with the data?
* How did you overcome any legal or societal issues?

## Dashboard Design
* List all dashboard pages and their content, either blocks of information or widgets, like buttons, checkboxes, images, or any other item that your dashboard library supports.
* Later, during the project development, you may revisit your dashboard plan to update a given feature (for example, at the beginning of the project you were confident you would use a given plot to display an insight but subsequently you used another plot type).
* How were data insights communicated to technical and non-technical audiences?
* Explain how the dashboard was designed to communicate complex data insights to different audiences. 

## Unfixed Bugs
* Please mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a significant variable to consider, paucity of time and difficulty understanding implementation are not valid reasons to leave bugs unfixed.
* Did you recognise gaps in your knowledge, and how did you address them?
* If applicable, include evidence of feedback received (from peers or instructors) and how it improved your approach or understanding.

## Development Roadmap
* What challenges did you face, and what strategies were used to overcome these challenges?
* What new skills or tools do you plan to learn next based on your project experience? 

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

## Acknowledgements 
* Thank the people who provided support through this project.