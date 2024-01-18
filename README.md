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
- Forecasting Models
- Comparative Analysis
- Filters and Slicers
- Buttons

## Modelling
In constructing our sales analysis model in Power BI, I took a hands-on approach, personally deriving and connecting 
various components to ensure a comprehensive and tailored solution. 

![ModeView](https://github.com/habeebsalaudeen/Sales-Company-Analysis/assets/97491265/e1102430-4fd3-4cf4-a091-1e5482fd57f1)


The model is a star schema.
There are 5 dimensuion tables and 1 fact table with a seperated Dax measures table containing all the dax measures. The dimension are all joined to the fact table with a one-to-many relationship.

