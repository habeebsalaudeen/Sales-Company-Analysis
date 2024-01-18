# Sales Company Analysis

![Salesmarket](https://github.com/habeebsalaudeen/Sales-Company-Analysis/assets/97491265/a6955e73-c5c8-4dfb-b905-25071998bdf9)

## Introduction
This is a Power BI on sales analysis of an imaginary company called **Sales Company**.
The project is to analyze and derive insights to answer crucial questions and help the company make data driven 
decisions.
**_Disclaimer_** : All datasets and reports do not represent any company, institution or country, but just a 
dummy datasets to demonstrate capabilities of Power BI.

## Problem Statement
1. Highest generated revenue by months, year, segment, region and category.
2. Revenue forecast for the next 2 years
3. Revenue month on month variance by month
4. Revenue same period last year by segment, month.

## Skills / Concepts Demonstrated
- Data Modeling and Relationships
- DAX (Data Analysis Expressions)
- Aggregation Techniques
- Forecasting 

- Comparative Analysis
- Filters and Slicers
- Buttons

## Modelling
In constructing our sales analysis model in Power BI, I took a hands-on approach, personally deriving and connecting 
various components to ensure a comprehensive and tailored solution. 

![ModeView](https://github.com/habeebsalaudeen/Sales-Company-Analysis/assets/97491265/e1102430-4fd3-4cf4-a091-1e5482fd57f1)


The model is a star schema.
There are 5 dimension tables and 1 fact table with a seperated Dax measures table containing all the dax measures. The dimension are all joined to the fact table with a one-to-many relationship.

## Visualization:

The report comprises 2 pages:
1. Sales report 1
2. Sales report 2

You can interact with the report {here} 
(https://app.powerbi.com/groups/me/reports/c3696476-6521-4525-9d6d-87e5931e4a1f/ReportSection6ef62836a704e2300032?experience=power-bi)

### Sales report 1 visual
In this Power BI sales analysis, I skillfully crafted a dynamic and comprehensive model. I implemented advanced measures, forecasting models for two years, and insightful analyses such as revenue comparisons to the same period last year and month-on-month variations.
![Sales_Report_1](https://github.com/habeebsalaudeen/Sales-Company-Analysis/assets/97491265/a79f644e-15bf-48b6-b1ed-71846cefd721)

### Sales report 2 visual
The use of slicers and filters allows for interactive exploration, and judicious application of various charts, including stacked bar, clustered column, donut, ribbon, matrix, and waterfall charts, ensures a visually compelling representation of total revenue, forecasting insights, and category-wise performance across regions. This analysis not only provides detailed segment-level insights but also allows users to navigate and discern trends effortlessly, making it a powerful tool for strategic decision-making.
![Sales_Report_2](https://github.com/habeebsalaudeen/Sales-Company-Analysis/assets/97491265/00273e11-8562-4ae2-a345-750fd8a4d728)

## Conclusion and Recommendation
The insight generated from the report shows:
- The highest generated revenue by Month, Same period last year, Month on month revenue = (NOVEMBER)
- The highest generated revenue by Year = (2017)
- Revenue Forecast shown from 2017-2018
- The highest generated revenue by Segment = (CONSUMER)
- The highest generated revenue by REGION = (SOUTH)
- The highest generated revenue by Category = (TECHNOLOGY)
