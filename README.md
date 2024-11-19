# Which Promotion Wins? Analyzing Campaign Performance and Sales Drivers for a New Menu Item
Group 3 Homework Session 5 - Fast Food Chain Data Analysis

## Introduction  

Launching a new menu item in the competitive fast food industry requires not only an appealing product but also an effective marketing strategy. To decide the best promotional approach for maximizing sales, a fast food chain tested three different marketing campaignes across multiple store locations in various market sizes. The fast food chain recorded over a four-week period the weekly sales for the new item, alongside key factors such as market size, store age and promotion type. 
This report aims to analyze the collected data and evaluate the effectiveness of each promotion. Furthermore, it tries to uncover additional factors that influence the sales such as age of store and market size. While the dataset presents challenges due to "dirty" data such as inconsistencies, after careful cleaning, this analysis will provide insights to guide future promotional strategies.


## Project Objectives 

The primary objectives of this project are: 
1. Address Data Quality Issues 
    - Identify and clean inconsistencies or errors in the dataset to ensure accurate and reliable analysis.

2. Evaluate Promotinal Performance 
    - Assess the effectiveness of the three different promotions in driving the sales for the new menu item

3. Understand Other Key Sales Drivers
    - Analyze other factors such as market size and age of store 

4. Provide Recommendations
    - What is the most effective promotion for maximizing sales?
    - Offer insights into optimizing future marketing strategies based on the data (observed trends and relationships)

By achieving these goals, this analysis tries to provide the fast food chain with data-driven insights and can be used to suppport strategic decision-making for the new menu item.


## Data Description

This dataset collected the weekly sales over a four-week period for a new menu item. Three different marketing compaigns were tested in multiple store locations across three different market sizes. As in the task described, these are the key variables: 
1. MarketID
2. MarketSize
3. LocationID
4. AgeOfStore
5. Promotion
6. Week
7. SalesInThousands

Considerations: 
- The data is "dirty", meaning it contains inconsistencies and errors that need to be addressed during the cleaning phase of the data. 
- This dataset only captures only a four-week period, so the trends and relationship can only be analyzed in this limeted timeframe.


## Methodology

To achieve the project objectives, this analysis will follow a structured methodology with the following steps:

1. Data Cleaning 
    - Identify and handle inconsistent values in the dataset.

2. Exploring the Data 
    - Summarize and visualize the data to understand distributions, trends, and relationships.
    - Compare average sales across different promotions, markets sizes and store ages
    - Investigate the impact of different factors

3. Promotion Effectiveness Analysis
    - Perform statistical tests (e.g. ANOVA tests) to determine if there are significant differences in sales performance among the three promotions. (as well as the different market sizes and age groups of stores)

4. Conclusion and Recommendations
    - Interpret the results of the analyses to identify the most effective promotion.

By following this methodology, this analysis ensures a thorough evaluation of the dataset, addressing data quality issues while uncovering meaningful patterns to support decision-making.

## Results

These are the following key insights from this analysis: 

- Promotion 1 and 3 are more effective than Promotion 2. However, there is no significant differnece between Promotion 1 and 3. Both can be used in the future. 

- The age of a store slightly influences the sales. Older stores (Age Group 21+) tend to experinece higher sales compared to newer ones. This suggests that factors that established stores have such as regular customer base or operational experinece possibly play a role in sales performance. 

- The factor market size was found to have no significant impact on sales performance. This implies that the effectiveness of the promotions and maybe other factors (that we didn't consider in this analysis) are relatively consistent between the three market sizes (small, medium, large).

## Usage

To use this python analysis for further exploration or replicate this analysis, you need to follow these steps: 

1. Clone this respository or download the "FastFood_Promotions_AnalysisCode.ipynb" file 
2. Please install the dependencies 
    - ensure to have python installed - the analysis uses Python 3.12.7 
    - you need the following python modules installed:
        - matplotlip 
        - scipy
        - seaborn
        - statsmodel
        - requests
        - pandas
3. Run the analysis
4. Explore the results and customize it if you want.
