
# Zomato Restaurant Performance Analysis



## Introduction

This project aims to analyze the business performance of restaurants on Zomato. The focus is on identifying the most popular restaurants, those generating the highest revenue, and understanding the factors behind their success. The analysis provides actionable insights to improve restaurant operations and customer satisfaction and offers recommendations for Zomato to enhance its service offerings.


### Data Overview
    - Food: Information about food items available at restaurants.
    - Menu: Details of menus offered by restaurants, including prices and categories.
    - Orders: Data on customer orders, including items ordered, quantities, and total cost.
    - Restaurant: Information about restaurants, including location, type, and ratings.
    - Users: Data on customers, including demographics and order history.

### Data Understanding and Cleaning
To ensure data quality, the following steps were taken:

    - Handling missing values
    - Removing duplicates
    - Correcting inconsistencies
    - Standardizing data formats

### Table Joins and Relationships
Key joins were performed to combine relevant data:

    - Food and Menu tables on `f_id`
    - Menu and Restaurant tables on `r_id`
    - Orders and Restaurant tables on `r_id`
    - Optionally, Orders and Users tables on `user_id`

### Exploratory Data Analysis (EDA)
EDA provided an overview and visualization of the data:

    - Summary statistics for numerical variables
    - Histograms and bar charts for distribution analysis
    - Box plots for outlier identification
    - Correlation heatmaps to identify relationships between variables

### Restaurant Popularity Analysis
To identify the most popular restaurants and cuisines, we defined and calculated popularity metrics:

    - Number of orders per restaurant
    - Unique user_ids ordering from each restaurant
    - Ratings and review counts

### Revenue Analysis
Revenue metrics were calculated to identify high-revenue restaurants:

    - Summing the `sales_amount` per restaurant
    - Average `sales_amount` per order
    - Top cuisines by revenue

### Factor Analysis
Factors contributing to popularity and revenue were analyzed:

    - Cuisine and service style impact
    - Urban vs. suburban location advantages
    - Menu variety and pricing
    - Customer demographics

### Insights and Recommendations
Key insights and recommendations were derived from the analysis:

#### For Restaurants:

    - Menu optimization
    - Pricing strategies
    - Targeted marketing
    - Improved customer service
#### For Zomato:

    - Enhanced search algorithms
    - Personalized recommendations
    - Improved user interface design



## Documentation and Presentation

A comprehensive dashboard was created to visualize the analysis. It includes filters for profit-to-order analysis, average order by cuisine, and restaurant chains. The entire research process was meticulously documented, ensuring reproducibility.

### dashboard
[Tableau Dashboard](https://public.tableau.com/app/profile/jonquis.d.bouyea/viz/ZomatoProject_17228227612790/Dashboard1?publish=yes)


## Tools and Technologies

```
The following tools and technologies were utilized:
```

| Tools     || Description  |
| :-------- | :------- | :------------------------- |
| `Python ` || pandas, numpy, matplotlib, seaborn, statsmodels, scikit-learn |
| `SQL`      || For querying and aggregating data |
| `Tableau/Power BI`      || For creating interactive dashboards and visualizations |
| Jupyter Notebooks || For documenting the analysis process and sharing results     |





##Conclusion

This project accurately analyzed the business performance of restaurants on Zomato, identifying key factors driving success and providing actionable insights to improve restaurant operations and customer satisfaction. The use of various tools and technologies ensured a thorough and accurate analysis, helping Zomato enhance its service offerings.


## Badges


[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)


## Feedback

If you have any feedback, please reach out to us at `Jbouyea3@gmail.com`

