# LITA_Class_Documentation

### Project Title : Data Analysis
---
[Project Overview](#project-overview)

[Data Sources](#data-sources)

[Tools Used](#tools-used)

[Data Cleaning and Preparations](#data-cleaning-and-preparations)

[Exploratory Data Analysis](#exploratory-data-analysis)

[Data Analysis](#data-analysis)

[Data Visualization](#data-visualization)

### Project Overview
---
This project is aimed at me learning Data analysis as a skill, which is estabilished by Ladies in tech africa initiative, in this project i am able to learn how to sort,clean,analyze different types of data with the aim of helping a future employer to make informed decisions on their project/business.

### Data Sources
---
 The primary source of data used is Data LITA.csv and this is not an open source data, it was shared by the tutor as a learing data .

 ### Tools Used
 ---
 - Microsoft Excel [Download Here](https://www.microsoft.com)
    1. For Data Cleaning
    2. For Analysis
    3. For Visualization
 - SQL- Structured Query Language for Querying of Data [Download Here](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16)
 - Github- for portfolio Building [Download Here](https://github.com)

### Data Cleaning and Preparations
---
In the initial phase of the Data cleaning and preparation, we perform the following action;
 1. Data loading and Inspection
 2. Handling missing variables
 3. Data Cleaning and Formatting

### Exploratory Data Analysis
---
EDA involved the exploring of the Data to answer some questions about the Data such as;
- What is the overall sales trend
- What product are top sellers
- What are the products on peak sales?

  ### Data Analysis
  ---
  This is where we include some basic lines of code or queries or even some of the DAX expressions used during analysis;

  ```SQL
  ALTER TABLE EMPLOYEE
  ADD AGE AS DATEDIFF(YEAR, Date_of_Birth, Hiredate) -
   CASE
       WHEN MONTH(Hiredate) < month(Date_of_birth)
	   OR (MONTH(Hiredate) = month(Date_of_birth)
	   AND DAY(Hiredate) < DAY(Date_of_birth))
	THEN 1
	ELSE 0
  END
  ```
![Untitled](https://github.com/user-attachments/assets/476c4c1f-bdeb-43ab-9a56-2e7e477214aa)

![11](https://github.com/user-attachments/assets/9f7e1edd-1250-4c65-a283-e95d9b10eccb)

### Data Visualization
---



✈️
⛹️‍♀️

|Heading 1|Heading 2|Heading 3|
|---------|---------|---------|
|Table 1|Table 2|Table 3|
