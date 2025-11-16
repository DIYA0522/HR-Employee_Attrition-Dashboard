## 📊 HR Employee Attrition Dashboard (Power BI)

Dataset: IBM HR Employee Attrition (Kaggle)

## 📝 Overview

This project explores employee attrition patterns using the IBM HR dataset.
The dashboard highlights key HR KPIs and visualizes factors contributing to employee turnover, helping HR teams identify high-risk employee groups and improve retention strategies.

## 📷 Dashboard Preview

![HR Attrition Dashboard](dashboard/IBM_HR_Analysis_Dashboard.jpg)

## 🎯 Project Objectives

 - Identify key factors contributing to employee attrition.
 - Analyze workforce demographics to uncover trends.
 - Measure attrition rate using dynamic KPIs.
 - Segment employees by age, salary, education, and tenure.
 - Highlight job roles with high dissatisfaction or attrition.
 - Provide insights to support HR retention strategies.

## 🧹 Data Cleaning & Preparation

 - Performed in Power Query / Power BI:
 - Added AttritionCount column using conditional logic (Yes → 1, No → 0)
 - Created AgeGroup column using custom bins
 - Created SalarySlab column using custom column logic
 - Checked and corrected datatypes
 - Removed/handled missing values
 - Added DAX measures for KPIs including Attrition Rate

## 📊 Key Metrics (KPIs)

 - Total Employees
 - Total Attrition
 - Attrition Rate
 - Average Age
 - Average Salary
 - Average Tenure (years with the company)

## 📈 Visuals in the Dashboard
Employee Attrition Analysis

 - Attrition by Education
 - Attrition by Salary Slab
 - Attrition by Age Group
 - Attrition by Gender
 - Attrition by Years at Company
 - Attrition by Job Role
 - Job Satisfaction Analysis
    Job Satisfaction by Job Role (using sum of AttritionCount)

 - Filters / Slicers
    Department (applies to the full dashboard)

## 📌 Key Insights Summary

 - Younger employees (lower age groups) show higher attrition.
 - Lower salary slabs have significantly higher churn.
 - Job roles such as Sales and Lab Technicians show higher attrition rates.
 - Employees with fewer years at the company (low tenure) tend to leave more often.
 - Job satisfaction is directly linked to attrition levels.
 - Differences across departments suggest the need for department-specific retention efforts.

## 🛠️ Tools Used

 - Power BI Desktop
 - Power Query Editor
 - DAX (Data Analysis Expressions)
 - Kaggle Dataset

 ## 📥 How to Use This Project

 - Download or clone this repository
 - Open telecom_churn.pbix using Power BI Desktop
 - Explore dashboard pages, slicers, and visuals
 - Experiment with filters to analyze different customer segments

## 👩‍💻 Author

## Diya Philip

## Aspiring Data Analyst skilled in Power BI, SQL, and Excel.
