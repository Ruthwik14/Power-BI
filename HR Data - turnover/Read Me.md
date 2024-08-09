# Introduction to Power BI - Turnover Analysis

## Project Description:
This project serves as a post-class exercise to practice Power BI functionalities, focusing on analyzing turnover within a company. Participants are provided with a case study involving HR analytics, where data regarding employee turnover is analyzed across departments.

## Case Study Number & Title:
Analyzing turnover in a company

## Background Information:
A company, operational since January 2018, requires analysis of turnover across its departments. The HR analytics team aims to gain initial insights into turnover trends within the organization.

## Problem Statement/Business Objectives:
Generate initial insights on turnover within the company to inform decision-making processes.

## Data for Case Analysis:
Data is provided in an Excel file accessible via the following source link: [Employee Turnover Dashboard](https://chandoo.org/wp/employee-turnover-dashboard-powerbi/)

## Data Description:
- Name: Name of the employee
- Gender: Gender of the employee
- Department: Department of the employee
- Branch: Branch of the employee
- Date of Join: Joining date of the employee
- Date of Leaving: Leaving date of the employee
- Designation: Job role of the employee

## Project Tasks:
1. Merge the staff and leavers tables in Power Query Editor based on the column Name.
2. Create a new table named Calendar with dates ranging from 01/01/2018 to 02/28/2019 and establish a relationship between this table and the staff table.
3. Create the following measures using the staff table:
   - Joinee Count
   - Leaver Count
   - Total Staff to Date (derived from Joinee Count and Leaver Count)
   - Turnover% (calculated as Leaver Count divided by Joinee Count)
4. Develop an interactive dashboard with the following components:
   - Slicer for department selection
   - Line chart displaying Joinee Count and Leaver Count by Date (month level)
   - Line chart depicting Total Staff Count by Date (month level) with an optional forecast for the next 6 months
   - Stacked bar-chart illustrating Leaver Count by Gender and Branch
   - Table showcasing the Top 10 designations by Turnover%
   - Three multi-row cards displaying Joinee Count, Leaver Count, and Total Staff to Date:
     - Entire dataset timeline (01/01/2018-02/28/2019)
     - Last one month (analysis date: 02/28/2019)
     - Last three months (analysis date: 02/28/2019)

## Solution:
A solution dashboard is provided along with the dataset.

![Alt Text](https://github.com/Ruthwik14/Power-BI/blob/main/HR%20Data%20-%20turnover/POWER-BI%20DashBoard.jpg)

## Key Takeaways/Results:
Participants will gain proficiency in utilizing Power BI for data analysis, enabling them to extract meaningful insights from the provided dataset, which can inform strategic decision-making within the organization.
