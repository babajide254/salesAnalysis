# Project Overview
This sales analysis describes the different activities in a sales company including the profit, loss, sale trends, highest product and lowest product sales
## Project Title
Slae analysis of products in tesco
### Aims and Objectives
- Highlight significat sale trends
- Spot patterns affecting sales projection
- Provide strategic suggestion for future sales
- Improve sales outcome over time
### Data Source
The data used was collected from tesco stores across London
### Tools Used
Microsoft Excel, Power BI, Python
### Data Cleaning/preparation
- An empty column was dropped
- Null values were removed
- From the age column, the mean values were used to replace the null values
- Non-numeric values were removed from sales column to allow aggregation of the sales column
### Exploratory data analysis
- The lowest/highest selling tesco store was identified
- The lowest/highest selling product was also identified
- The day with the lowest/highest sales was determined
- The age group with the highest/lowest purchase
- The gender with the highest/lowest purchase
- Poor/best perfoming sales Tesco store
### Data Analysis
This is an example code used in the project:
```
Python
sales.drop('link', axis = 1, inplace=True)
```
### Results
#### The results showed the following;
- Tesco store in South London recorded the highest sales while Tesco store in North London recorded the lowest sales
- The day with the lowest sales is monday while the day with the highest sales is Sunday
