# GLOBAL AUTOMOTIVE CAR SALES ANALYSIS PROJECT

This project involves analyzing car sales data to gain valuable insights into sales performance, customer demographics, and geographic trends. The project showcases my ability to perform data cleaning, transformation, and visualization using Power BI.

## DATA SOURCE

The raw data was downloaded from the [data.world website](https://data.world/). The dataset included various attributes related to car sales, such as brand, model, country, sale amount, resale amount, and 5-year depreciation percentage.


## DATA CLEANING AND TRANSFORMATION

To prepare the data for analysis, I performed several cleaning and transformation steps:

1. **Converted Data Types**: Ensured all columns had appropriate data types for analysis.
2. **Created Calculated Measures**: Categorized the age of customers into groups like early adults, late adults, and seniors.


## CALCULATED MEASURES

I created several calculated measures to facilitate deeper insights:

- Avg. Depreciation
- Avg. Sale Price
- Profit Margin
- Total Sales
- Resale Revenue
- Total No. of Sales

## DASHBOARD VISUALIZATION

The dashboard is divided into two separate pages for a comprehensive analysis:

### Page 1: Sales Overview

This page provides an overview of sales performance through various visuals:

- Avg. Depreciation by Brands (Table)
- Top 10 Selling Brands (Stacked Bar Chart)
- Sales Over Time (Line Chart)
- Total Revenue and Resale Revenue (Stacked Column Chart)
- Avg. Sales Price Over Time (Area Chart)
- No. of Sales of New vs. Old Cars (Stacked Bar Chart)
- **KPI Cards**: Total Revenue, Resale Revenue, Avg. Sale Price, Total No. of Sales, and Profit Margin.



### Page 2: Marketing Intelligence: Geographic and Demographic Insights

This page offers insights into customer demographics and geographic distribution:

- Global Car Sales Distribution (Map)
- Age Distribution of Buyers (Stacked Column Chart)
- Top 10 Performing Countries (Table)
- Gender Distribution of Car Purchases (Donut Chart)

## KEY INSIGHTS AND FINDINGS

- **Highest Depreciation**: Corbin has the highest depreciation percentage at 24%, while MG has the lowest at 1%.
- **Top Selling Brand**: Ford leads with a total sales revenue of $48 million, followed by Chevrolet and Dodge.
- **Total Profit Margin**: Across all brands, the total profit margin stands at $294.77 million.
- **Sales Variance**: The variance between new and old car sales is a mere 0.2k.
- **Sales Trends**: Sales soared from 2000 to 2002, maintained consistency up to 2020, then declined due to the pandemic.
- **Top Country**: China accounts for the highest sales at $102.3 million.
- **Gender Distribution**: The percentage of purchases made by males and females is almost equal, with a minor variance of 1.04%.

## CHALLENGES I FACED DURING THE PROJECT

1. **Date Column Data Type**:
   - **Issue**: The date column was initially text and caused errors when converted to a date.
   - **Solution**: Separated the day, month, and year into three columns based on `/`. Changed the data type of all columns to whole numbers, merged all three columns, and converted the resulting column to a date type.

2. **Values in Million Format**:
   - **Issue**: Converting values to the million format in the table visual.
   - **Solution**: Utilized online resources to convert values to millions under the "specific column" settings of the table visual.

## Conclusion

The insights derived from this car sales analysis dashboard provide a comprehensive view of the car sales landscape:

- **Target Countries**: With China accounting for the highest sales at $102.3 million, it stands out as a key market. Strategies could be tailored to further penetrate this market.
- **Customer Segments**: Sales data reveals that the percentage of car purchases made by males and females is almost equal. Marketing strategies should be designed to appeal to both genders equally.
- **Depreciation Trends**: Brands with low depreciation rates, like MG, could be highlighted to customers looking for long-term value.
- **Sales Trends Over Time**: The sales trend shows a peak from 2000 to 2002, with consistency up to 2020 and a decline due to the pandemic. Post-pandemic strategies could focus on revitalizing sales through targeted promotions.

This project demonstrates my proficiency in data cleaning, transformation, and visualization using Power BI, showcasing my ability to turn raw data into actionable insights that can drive key business decisions.
