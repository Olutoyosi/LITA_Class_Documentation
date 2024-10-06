# LITA_Class_Documentation

### Project Title : Data Analysis

### Project Overview
This project is aimed at me learning Data analysis as a skill, which is estabilished by Ladies in tech africa initiative, in this project i am able to learn how to sort,clean,analyze different types of data with the aim of helping a future employer to make informed decisions on their project/business.

### Data Sources
 The primary source of data used is Data LITA.csv and this is not an open source data, it was shared by the tutor as a learing data .

 ### Tools Used
 - Microsoft Excel [Download Here](https://www.microsoft.com)
    1. For Data Cleaning
    2. For Analysis
    3. For Visualization
 - SQL- Structured Query Language for Querying of Data
 - Github- for portfolio Building

###Data Cleaning and Preparations
In the initial phase of the Data cleaning and preparation, we perform the following action;
 1. Data loading and Inspection
 2. Handling missing variables
 3. Data Cleaning and Formatting

#Exploratory Data Analysis
EDA involved the exploring of the Data to answer some questions about the Data such as;
- What is the overall sales trend
- What product are top sellers
- What are the products on peak sales?

  ### Data Analysis
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
  
### Data Visualization

![11](https://github.com/user-attachments/assets/7e87e95f-46e2-459e-aed3-87ec42058e36)

