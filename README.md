# LITA-Class_HR-Data

## Project Title: LITA Human Resource Data

## Outline

### Project Overview
---
This project, which was part of the training conducted during the LITA Data Analysis class, presents the attrition rates of employee in an organization, The goal of the project was to address the issues of employee's attritons from the organization. Despite the organization"s activities of training, providing for and maintaining their staff, employees keep leaving the organization to other places. The analysis includes deriving various objectives, to understand better the underlying issues and to propose actionable recommendations that would reduce employee attritions from the organization.

### Data Sources
---
Data used for this project was an excel data provided by the facilitators.

## Data Description
---
The dataset includes the following fields:
1. Attrition: The Column tells us if the employees are still in the organization or not
2. Age Band: This shows the age groups of all the employees in the organization
3. Department : Department pf Employees
4. Gender: Gender of employees
5. Education Field:  
Product Category: C

### Tools used
---
-  Microsoft Excel [Download Here](https://www.microsoftexcel.com)
     1. For Data Input
     2. For Analysis
     3. For Data Cleaning
     4. For Data visualization
-  Microsoft Power BI [Download Here](https://www.microsoftpowerbi.com)
     1. For Data Transformation
     2. Data modelling
     3. To Create reports and dashboards that are collections of visuals.
     4. To Create maps, charts and graphs.
-  GitHub [Download Here](https://www.github.com)
     1. For Portfolio Building
  
### Data Cleaning and preparation
---
During the initial phase of the data entry, the folowing actions were performed
     1. Data import from Excel
     2. Data Transformation
     3. Data Cleaning and Structuring
     4. Data Formatting

### Data Analysis
---
Some of the code used to analysed the data are:
```Excel
VLOOKUP(lookup_value,table_array,col_index-number,[range_lookup])
LEFT(text,[num_char])
```
```Power BI
Attrition Rate = SUM('HR data'[Attrition Count]) /SUM('HR data'[Employee Count])
Average Age = AVERAGE('HR data'[Age])
Age Sort = Table.TransformColumnTypes(#"Added Conditional Column5",{{"Job Satisfaction rating", type text}})
```

### Data Visualization
---
