# Bike Sales Analysis | Exploratory Data Analysis with Microsoft Excel

## 1. Project Overview

This project explores customer purchasing behaviour using a bike sales dataset containing demographic, socioeconomic and lifestyle information.

The analysis investigates the relationship between customer characteristics and bike purchasing decisions, with the aim of identifying patterns across different customer segments.

Using Microsoft Excel, I cleaned and prepared the dataset, performed exploratory data analysis, created PivotTables and developed an interactive dashboard to communicate key findings.

## 2. Business Problem

Understanding customer purchasing behaviour is important for businesses seeking to improve customer segmentation, identify potential markets and make informed marketing decisions.

The objective of this analysis was to investigate which customer groups were more likely to purchase bikes and whether factors such as age, gender, income, marital status, occupation and commuting distance were associated with purchasing behaviour.

## 3. Project Objectives

The analysis aimed to answer the following business questions:

- Which age group records the highest number of bike purchases?
- How does purchasing behaviour differ between male and female customers?
- Is there an association between customer income and bike purchases?
- Do single or married customers demonstrate higher purchasing rates?
- Which occupational groups have the highest bike purchasing rates?
- How does commuting distance relate to purchasing behaviour?

## 4. Dataset Description

The original dataset contained 1,026 customer records and 13 columns.

The working dataset contained 1,000 records following data preparation.

Key variables included:

| Variable | Description |
|---|---|
| Age | Customer's age |
| Gender | Customer's gender |
| Marital Status | Single or married |
| Income | Customer's annual income |
| Occupation | Customer's occupational category |
| Commute Distance | Distance between home and workplace |
| Education | Customer's education level |
| Region | Customer's geographical region |
| Purchased Bike | Whether the customer purchased a bike |

## 5. Tools and Technologies

**Microsoft Excel**

- Data cleaning and preparation
- Data transformation using Excel formulas
- IF functions for age categorisation
- PivotTables for data summarisation
- PivotCharts for visual analysis
- Interactive dashboard development

## 6. Data Preparation and Methodology

The analysis followed a structured data preparation and exploration process.

**Step 1: Data inspection and cleaning**

The original dataset was reviewed to understand its structure, identify duplicate records and prepare the data for analysis. The working dataset was reduced to 1,000 records.

**Step 2: Data transformation**

Categorical variables were standardised, including marital status and gender. An additional age category column was created using an IF formula to group customers into age brackets.

**Step 3: Exploratory data analysis**

PivotTables were used to summarise customer purchasing behaviour across demographic and socioeconomic categories.

**Step 4: Data visualisation**

PivotCharts were developed to compare purchasing and non-purchasing customers across selected variables.

**Step 5: Dashboard development**

The visualisations were organised into an Excel dashboard to present the analysis in a clear and accessible format.

## 7. Key Findings and Business Insights

The analysis revealed several patterns within the dataset.

**Age and purchasing behaviour**

Middle-aged customers recorded the highest purchasing rate at approximately 54.6%, compared with 35.5% among younger customers and 31.2% among older customers.

**Gender and purchasing behaviour**

Male customers accounted for slightly more purchases in absolute numbers. However, female customers recorded a marginally higher purchasing rate of 48.9%, compared with 47.4% for males.

**Income and purchasing behaviour**

Customers who purchased bikes had a higher average income ($57,962.58) than customers who did not purchase bikes ($54,874.76).

**Marital status**

Single customers recorded a higher purchasing rate of approximately 54.1%, compared with 42.9% among married customers.

**Occupation**

Professional customers recorded the highest purchasing rate among the occupational categories, at approximately 54.3%.

**Commuting distance**

Customers travelling between 2 and 5 miles recorded the highest purchasing rate at approximately 58.6%. Customers travelling more than 10 miles recorded the lowest rate, at approximately 29.7%.

## 8. Dashboard and Visualisations

The Excel dashboard presents comparisons across customer income, age groups and commuting distances.

Additional analysis of marital status and occupation supports the broader investigation of customer purchasing behaviour.

**Dashboard Preview**

![Bike Sales Dashboard](images/bike-sales-dashboard.png)

## 9. Conclusion

The exploratory analysis identified differences in bike purchasing behaviour across demographic and socioeconomic customer groups.

Middle-aged customers, single customers and customers within the professional occupational category recorded comparatively higher purchasing rates.

The findings also indicated an association between income and purchasing behaviour, while commuting distance revealed differences in purchasing rates across distance categories.

These insights demonstrate how exploratory data analysis can help businesses understand customer segments and support more informed marketing and business decisions.

The analysis describes patterns and associations within the dataset and does not establish causal relationships.

## 10. Project Files

- `Bike_Sales_Analysis.xlsx` – Excel workbook containing the dataset, working sheet, PivotTables and dashboard.
- `images/bike-sales-dashboard.png` – Dashboard screenshot.

## 11. Learning Reference and Acknowledgement

This project was completed as a practical data analytics learning exercise, drawing on the Bike Sales Analysis project by Alex The Analyst.

The project provided an opportunity to practise data cleaning, transformation, exploratory analysis and dashboard development using Microsoft Excel.

---

**Author:** Jessicah Mondlane  
**Tools:** Microsoft Excel | Data Analytics | Data Visualisation  
**Project Type:** Exploratory Data Analysis
