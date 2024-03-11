# Data-Analysis-for-Skilharvest
This is a documentation about my learning and progress with skilharvest. Let's dive into the analysis together😙

## Documentation Outline
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools Used](#tools-used)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Power Bi Query Used](#power-bi-query-used)
- [Result/Findings](#result-findings)

## Project Overview

This Data Analysis project emphasis to derive meaningful insight from the HR Data. By carefully analyzing the different parameters in this data to gather enough and adequate insight and observations to make a concise and reasonable decisions which then prompt us to tell a compelling and captivating stories around the data insights gotten and to know the performance from our data.

## Data Sources
The primary source of this Data that is used is HR Data that was given to us by our instructor .

## Tools Used
- Ms Excel for Fetching of data

- Microsoft Power Bi for cleaning of data and for reporting.

## Exploratory Data Analysis

Exploratory Data Analysis is an approach in data analysis that involves summarizing and visualizing data to understand its main characteristics, uncover patterns, and identify potential relationships between variables such as;

- What is the Employee count in the organization?
- What is the sum of attrition in the organization?
- Which department experience more attrition?
- What education qualification experienes the most attrtion?
- what is the Rate of attrition in the organization?
- 
## Power Bi Query Used

To find the Sum of Attrition, I used a conditional formatting to create a measure for the Attrition. The code is below;
```
If Attrition equals Yes then 1
Else
   0
```
To find the Current Employee, I created a Measure using the DAX function. The code is below;
```
SUM('HR data'[Employee Count])-SUM('HR data'[Attrition Count])
```
To find the Rate of Attrition, I created a Measure using the DAX function. The code is below;
```
SUM('HR data'[Attrition Count])/SUM('HR data'[Employee Count])
```

![DASH](https://github.com/Ellamina19/Data-Analysis-for-Skilharvest/blob/main/HR%20REPORT.jpg)
  ## Result/Findings
  From our Analysis, we derived the following insight:

-  The HR Employee count

- The Sum of Attrition

- The Sum of current Employee

- Rate of Attrition

- The Average age of Attrition

- Attrition count by Education

- Attrition By Department

- Attrition By Age and Gender

- Attrition Count By Education and Business Travel

- Average Age of Attrition 
