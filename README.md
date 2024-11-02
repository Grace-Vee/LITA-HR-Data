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
    5. Education Field: Educational field of employees
    6. Job Role: Employee"s Job roles
    7. Marital Status: Marital Status of staff\
    8. Employee Counts: Total Employee Counts
    9. Job Level: Job Level
    10. Attrition Counts: Cunts of thpse leaving the Organization
    11. Attrition rates: rates at which they are leaving
    12. Work Life Balance: 

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
     1.  Data quality was ensured by correcting any spelling errors, removing duplicate entries, and addressing 
         missing values.
     2.  Standardization: Used find and replace to standardize certain fields
     3.  Data import from Excel
     
### Data Transformation:
---
Data was transformed to thoroughly clean, remove issues with data and increase column quality, column distribution and profile to 100%
     1. Data Types and Formatting: Ensured all data fields were assigned the correct data types, with numerical fields formatted as currencies where appropriate, and date fields set to 
        date format.
     2. Created New Columns: Added a new column to categorize transaction using conditional column formatting, IF function and custom column
.
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
![HR visual](https://github.com/user-attachments/assets/56df56c3-2cb4-4086-b3b4-354ba93a4502)

![HR 2](https://github.com/user-attachments/assets/6ae7ef91-1a42-4711-acb4-7273c9db4fbd)

### Tables
---
![HR Table](https://github.com/user-attachments/assets/b4a58802-bda2-488a-9c9f-90586451143c)

### Insights
---
The visual showed that:
 1. Average age of Staff in the company is 37 years, which shows that the organization have more younger staff than the elderly ones
 2. A total of 237 employees, which is 16% of the total employees, left the company over time. This shows that the organization lost 16% of their staff, in which resources like time 
    and money were spent training. For such an amount of employee to leave the organization showed that they were greately disastisfied with the organization's policies of handling 
    their staff. This explanation goes in line with the visuals, which showed that out of the 237 employee attrition count, a total of 66 employees were very desatisfied with their 
    jobs and 46 employees were desatisfied wit their jobs. This could be the reason why they left the organization
 4. Attrition count by gender showed that a total of 150 male and 87 female left the organization during the period, probably because the organization's policies favousr the 
    females than the males, 
 5. Attrition based on Department showed that the attrition rate was highest in Life Science department, which had a total of 89 staff that left the company, followed by the Medical 
    department with a total of 63 attrition counts. Human resource had the lowest attrition rate, with a count of 7 employee who left the organization.
 6. Laboratory Technicians had the higest counts of very desatisfaction rates, probably the reason why the Life science and medical field had the hihest attrition rate compared to 
     other department.
 7. Attrition based on age groups showed that age group 25-34 had the highest attrition count, which showed that the younger people were more desatisfied with the organizational 
    policies

### Recommendations
---
The followings were recommended based on findings from the Data Annalysis, which enabled us took informed decisions such as:
 1. Policies should be ammended: The Organization should amend their policies to favour all age groups and gender. The Executives should work on providing extracurricular activities 
    like fitness coach or even work in line with a fitness centre where their staff could enrol at a cheap rate for weekly fitness training, which would encourage more younger age 
    groups to be satisfied and have great work like balance. All genders and age groups should be consider when allocating benefits or incentives

2. Sisters Companies should be researched: The HR department should work on researching on how other sister's companies with similar goals and objectives treats their employees, so 
   they can work on satisfying their staff

3. Budget shoul be allocated to departments based on activities they have in line to do, this would reduce the number of unsatisfied staff by departments
4. All departments should be treated fairly
 
 ### Thank You
