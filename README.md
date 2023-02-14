
# Financial Data Analysis with FRED API - USA Federal Reserve Economic Data

![Logo](https://miro.medium.com/max/727/1*ZTdpdH5Q1HPR5OO7PZIWpA.jpeg)

## What is FRED? 

Short for Federal Reserve Economic Data, FRED is an online database consisting of hundreds of thousands of economic data time series from scores of national, international, public, and private sources. FRED, created and maintained by the Research Department at the Federal Reserve Bank of St. Louis, goes far beyond simply providing data: It combines data with a powerful mix of tools that help the user understand, interact with, display, and disseminate the data. In essence, FRED helps users tell their data stories. The purpose of this article is to guide the potential (or current) FRED user through the various aspects and tools of the database.

## What is FRED API? 

The FRED® API is a web service that allows developers to write programs and build applications that retrieve economic data from the FRED® and ALFRED® websites hosted by the Economic Research Division of the Federal Reserve Bank of St. Louis. Requests can be customized according to data source, release, category, series, and other preferences.

## What is the purpose of this project?

The purpose of this project is to prepare financial data analysis by downloading macroeconomic data from the FRED API. The first part of the project focuses on providing an overview of the house market in the USA with 9 charts and 2 functions. Over time, we plan to expand the project to include different kinds of industries and functions. We aim to make our scripts easily adjustable with a parameters structure, making it usable for people who are not professionally involved with coding.

## Functions:

We have defined two functions - yoychange() and smayearly() - and applied them to datasets to visualize the change in specific periods.

### yoychange():

The yoychange() function takes four parameters - series_code, series_name, start_date, and end_date - and returns a line chart showing the percentage change of the series over the past 12 months or quarters please be careful on the period of your data. The chart also includes a bar chart showing the year-over-year change. This function is useful for visualizing the percentage change and year-over-year change of a specific series.

### smayearly():

The smayearly() function takes four parameters - series_code, series_name, start_date, and end_date - and returns a line chart showing the year-over-year change and yearly simple moving average of the series. This function is useful for visualizing the yearly trend of a specific series.


### We have applied some of these functions to 9 different datasets, which are:

* New Privately-Owned Housing Units Started
* New Privately-Owned Housing Units Authorized in Permit-Issuing Places
* S&P/Case-Shiller U.S. National Home Price Index
* New One Family Houses Sold
* Median Sales Price of Houses Sold for the United States
* Real Gross domestic product: Structures
* Non-farm Private Payroll Employment for Construction
* 30-Year Fixed Rate Mortgage Average in the United States
* Mortgage Delinquency Rate

We hope that this project will be helpful for people who are interested in analyzing macroeconomic data, especially for those who are not proficient in coding.









    
