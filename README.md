# NYC - Citywide Payroll Data
 Citywide Payroll Data (Fiscal Year)
Data is collected because of public interest in how the City’s budget is being spent on salary and overtime pay for all municipal employees.  
# Citywide_Payroll Analysis Fiscal Year 2014-2019
## Background
Data Source: https://www.kaggle.com/new-york-city/nyc-citywide-payroll-data

Data is input into the City's Personnel Management System (“PMS”) by the respective user Agencies.  
Each record represents the following statistics for every city employee: Agency, Last Name, First Name, Middle Initial, Agency Start Date, Work Location Borough, Job Title Description, Leave Status as of the close of the FY (June 30th), Base Salary, Pay Basis, Regular Hours Paid, Regular Gross Paid, Overtime Hours worked, Total Overtime Paid, and Total Other Compensation (i.e. lump sum and/or retro payments).  This data can be used to analyze how the City's financial resources are allocated and how much of the City's budget is being devoted to overtime.  
Increments of salary increases received over the course of any one fiscal year will not be reflected.  All that is captured, is the employee's final base and gross salary at the end of the fiscal year.




### Data Dictionary - Column Information
Column Name	Column Description	Term, Acronym, or Code Definitions	"Additional Notes 
(where applicable, include the  range of possible values, units of measure, how to interpret null/zero values, whether there are specific relationships between columns, and information on column source)"
### Payroll Description	The Payroll agency that the employee works for
Last Name. Last name of employee
First Name. First name of employee
Middle Initial. Middle initial of employee
Agency Start Date. Date which employee began working for their current agency
Work Location Borough. Borough of employee's primary work location
Title Description. Civil service title description of the employee
Leave Status as of Jun 30. Status of employee as of the close of the relevant fiscal year: Active, Ceased, or On Leave
Base Salary. Base Salary assigned to the employee. Base Salary represents the amount the job pays (not necessarily what was earned) and not including any other pay (differentials, lump sums, uniform allowance, meal allowance, retroactive pay increases, settlement amounts, etc) or overtime
Pay Basis. Lists whether the employee is paid on an hourly, per diem or annual basis
Regular Hours. Number of regular hours employee worked in the fiscal year. This does not include overtime hours
Regular Gross Paid. The amount paid to the employee for base salary during the fiscal year 		Regular gross paid represents actual base salary during reporting period, which is the portion of the person’s annual salary paid before deductions are calculated\withheld. This does not include overtime pay or other compensation and does not reflect the after tax amount or net pay.   Total gross pay is calculated by adding columns L, N and O.
OT Hours. Overtime Hours worked by employee in the fiscal year	OT= Overtime
Total OT Paid. Total overtime pay paid to the employee in the fiscal year	OT= Overtime
Total Other Pay. Includes any compensation in addition to gross salary and overtime pay, ie Differentials, lump sums, uniform allowance, meal allowance, retroactive pay increases, settlement amounts, and bonus pay, if applicable. Not every employee will have a value in this field.  For those employees with no other pay, earnings will be stated as $0

## Data Cleaning

Data transformation: Created data frame dropping the unnecessary data, Minor Data Munging to Re-Format the Data Frames, cleaned-up non-alpha numberic characters 

## Analysis and Visualizatons

Created a subset of data,to avoid negative values and zeros
Visualizations:
 - 15 Lowest paid employees in the city for the last 6 Fiscal Years
 - 15 highest paid employee
 - Top 15 Gross Pay by work location
 - 2019 Agencies with most employes
 - For values greater than 20K, calculated mean and median for regular gross pay
 - Top 10 Boroughs with Highest Average Gross Pay FY2019-2018-2017 & 2016
 - Top 10 Boroughs with Highest Average Gross Pay FY2018
 - Historgram Distribution for gross pay FY2016-2017-2018 & 2019
 - Distribution of Base Salary for Annual Employees making over 10,000
 - Distribution of Base Salary for Annual Employees making over 10,000 all Fiscal years graph
 - Distribution of Gross Pay in 2019

![1](https://github.com/jhenvi/NYC-Citywide-Payroll-Data/blob/master/Output/2019_Agencies_w_most%20employes.png)
![2](https://github.com/jhenvi/NYC-Citywide-Payroll-Data/blob/master/Output/Dist_BaseSalDistribution.png)
![3](https://github.com/jhenvi/NYC-Citywide-Payroll-Data/blob/master/Output/Dist_GrossPay.png)
![6](https://github.com/jhenvi/NYC-Citywide-Payroll-Data/blob/master/Output/Work_Location_Borough.png)
![7](https://github.com/jhenvi/NYC-Citywide-Payroll-Data/blob/master/Output/highest_Paid_employees.png)
![8](https://github.com/jhenvi/NYC-Citywide-Payroll-Data/blob/master/Output/lowest_Paid_employees.png)
![1](https://github.com/jhenvi/NYC-Citywide-Payroll-Data/blob/master/Output/Dist_Gross_Pay_2019.png)
