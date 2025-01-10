# Online Retail Analysis

This project conducts a comprehensive data analysis of online retail transactions, exploring customer behavior, product popularity, and sales patterns. By examining a dataset of online purchases, we aim to identify trends, uncover interesting patterns, and draw actionable conclusions. The insights gained will help optimize pricing strategies, inform marketing decisions, and enhance understanding of customer preferences in the online retail space.

# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)


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
* The project is currently running in a Jupyter Notebook environment. Future plans include deploying it as a web application.

### Heroku

* The App live link is: https://YOUR_APP_NAME.herokuapp.com/ 
* Set the runtime.txt Python version to a [Heroku-20](https://devcenter.heroku.com/articles/python-support#supported-runtimes) stack currently supported version.
* The project was deployed to Heroku using the following steps.

1. Log in to Heroku and create an App
2. From the Deploy tab, select GitHub as the deployment method.
3. Select your repository name and click Search. Once it is found, click Connect.
4. Select the branch you want to deploy, then click Deploy Branch.
5. The deployment process should happen smoothly if all deployment files are fully functional. Click now the button Open App on the top of the page to access your App.
6. If the slug size is too large then add large files not required for the app to the .slugignore file.


## Main Data Analysis Libraries
* pandas: For data manipulation and analysis
* matplotlib: For creating static visualizations
* seaborn: For statistical data visualization
* numpy: For numerical computing


## Credits 

* Dataset source: Kaggle 


### Content 

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign-Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos used on the home and sign-up page are from This Open-Source site
- The images used for the gallery page were taken from this other open-source site



## Acknowledgements (optional)
* Thank the people who provided support through this project.