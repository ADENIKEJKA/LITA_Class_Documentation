# LITA_Class_Documentation

## Project Title: Analysis for Yearly Sales

[Project Overview](#project-overview)

[Data Sources](#data-sources)

[Tools Used](#tools-used)

[Data Cleaning and Preparations](#data-cleaning-and-preparations)

[Exploratory Data Analysis](#exploratory-data-analysis)

[Data Analysis](#data-analysis)

[Data Visualization](#data-visualization)

[Inferences](#inferences)

[Summary](#summary)

### Project Overview
---
The purpose of this data analysis project is to produce an understanding of this project's sales performance throughout the previous year. We want to obtain sufficient insights to make rational decisions by scrutinizing the different characteristics in the data we receive. This allows us to employ the insights to craft captivating narratives about our data and determine its optimal performance.

### Data Sources
---
The primary source of data used here is Data Sale.csv and this is an open source data that can be freely downloaded from an open source online such as kaggle or FRED or any other data repository site.

### Tools Used
---
- MIcrosoft Excel; [Download here](https://www.microsoft.com)
  1. For Data Cleaning
  2. Analysis
  3. Visualization
  
- SQL - Structured Query Language for Querying of Data
- GitHub for Portfolio building
- Power BI for Data cleaning, Analysis and Presentation

### Data Cleaning and Preparations
---
In the initial phase of Data cleaning and preparations, we performed the following actions;
1. Data loading and inspection
2. Handling missing variables
3. Data cleaning and formatting

### Exploratory Data Analysis
---
EDA involved the exploring of the Data to answer some questions about the Data such as;
- What is overall sales trend?
- Which product are top sellers?
- What are the products on peak sales?

### Data Analysis
---
This is where we include some basic lines of code or queries or even some of the DAX expressions used during the analysis;
```SQL
SELECT * FROM EMPLOYEE
WHERE Staffid = 'AB281'
```

```SELECT COUNT(Staffid) AS NumberOfEmployee FROM Salary```
```SQL
update Salary
set salary = 7056999.9994
where Staffid = 'AB401'
```

### Data Visualization

![Pivot table for Model by Revenue](https://github.com/user-attachments/assets/14ac9ca8-e360-4cde-b089-089022f65502)

![Pivot table for Top 10 Stores by Revenue](https://github.com/user-attachments/assets/ab2c9c1d-e926-4077-97fe-50d7071d530c)

![Pivot Graph for Revenue by Region](https://github.com/user-attachments/assets/d611dd43-4778-4f63-8b51-7a0d971f15c9)

![Pivot Graph for Revenue by Units sold](https://github.com/user-attachments/assets/31f2ab55-256a-4653-8283-c0c52627547b)

![Data Analysis with Power BI](https://github.com/user-attachments/assets/ff048a39-1fa5-4f10-a98f-1b427cb0b1ea)

![Current employees by age group and gender](https://github.com/user-attachments/assets/97a19a35-dcb7-43b3-b58a-16d8e15987dc)

### Inferences
---
#### Sales Analysis Inferences

1. Service Plans: - South-West: This region has made the most money from service plans, suggesting that both individuals and businesses have a high demand for upkeep and support services. This points to a potential opportunity to improve service offerings, possibly by implementing tiered programs that accommodate varying client needs.
   - North-East: Despite not having the greatest revenue, the region's small enterprises, in particular, are becoming more and more interested in service plans. Campaigns to raise awareness and engage in targeted marketing could increase subscriptions in this area.

2. Printer Sales:
   - North-East: The North-East has achieved the highest units sold in printer sales, suggesting a growing consumer base that prioritizes affordability. This indicates an opportunity to introduce entry-level models tailored to local needs.
   - South-West: "While the South-West does not have the highest unit sales, it shows a strong demand for higher-end printers, contributing significantly to revenue. Upselling features and services associated with premium products could enhance profitability in this region.
  
3. Parts:
   - South-West: Sales data indicates a well-established market for repairs and replacements, with the South-West accounting for a sizeable amount of parts income. Forging closer ties with regional distributors may help boost sales and optimize the supply chain.
   - North-East: Due in large part to growing machinery usage in nearby industries, the North-East shows a rising trend in parts sales. This implies room for expansion provided the logistical issues are resolved.

4. Copier Sales:
   - South-West: The South-West leads in copier sales revenue, driven by a high concentration of corporate offices and educational institutions. This suggests a robust market that could benefit from promotional packages or leasing options to attract more customers.
   - North-East: In the North-East, although unit sales are high, revenue remains lower due to lower price points. Focusing on the value proposition of copiers and enhancing product features could drive higher revenue in this region.
  
### Summary
---
- The South-West exhibits a strong market presence for service plans, parts, and copier sales, highlighting the need for enhanced service offerings and strategic marketing.
  
- The North-East, while leading in units sold for printers, presents an opportunity to improve revenue through targeted marketing and addressing logistical challenges in parts and service plans.

  These inferences can help shape regional strategies for product development, marketing, and sales initiatives.


