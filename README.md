# LITA_Class_Documentation

## Project Title: Analysis for Yearly Sales

[Project Overview](#project-overview)

[Data Sources](#data-sources)

[Tools Used](#tools-used)

[Data Cleaning and Preparations](#data-cleaning-and-preparations)

[Exploratory Data Analysis](#exploratory-data-analysis)

[Data Analysis](#data-analysis)

Recommendations

Inferences

### Project Overview
---
The purpose of this data analysis project is to produce an understanding of this project's sales performance throughout the previous year. We want to obtain sufficient insights to make rational decisions by scrutinizing the different characteristics in the data we receive. This allows us to employ the insights to craft captivating narratives about our data and determine its optimal performance.

### Data Sources
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


