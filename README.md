# Create-an-Analytical-Dataset
Blending  and formatting the  data and dealing with outliers.

# Data
* p2-2010-pawdacity-monthly-sales.csv 
->  This file contains all of the monthly sales for all Pawdacity stores for 2010.

* p2-partially-parsed-wy-web-scrape.csv 
-> This is a partially parsed data file that can be used for population numbers.

* p2-wy-453910-naics-data.csv 
-> NAICS data on the sales of all competitor stores where total sales is equal to 12 months of sales

* p2-wy-demographic-data.csv 
-> This file contains demographic data for each city and county in Wyoming.

# The Business Problem
Pawdacity is a leading pet store chain in Wyoming with 13 stores throughout the state. This year, Pawdacity would like to expand and open a 14th store. Your manager has asked you to perform an analysis to recommend the city for Pawdacity’s newest store, based on predicted yearly sales.

Your first step in predicting yearly sales is to first format and blend together data from different datasets and deal with outliers.

Your manager has given you the following information to work with:

* The monthly sales data for all of the Pawdacity stores for the year 2010.
* NAICS data on the most current sales of all competitor stores where total sales is equal to 12 months of sales.
* A partially parsed data file that can be used for population numbers.
* Demographic data (Households with individuals under 18, Land Area, Population Density, and Total Families) for each city and county in the state of Wyoming. For people who are unfamiliar with the US city system, a state contains counties and counties contains one or more cities.

# Steps to Success
-> Step 1: Business and Data Understanding
Your project should include a description of the key business decisions that need to be made.

-> Step 2: Building the Training Set
To properly build the model, and select predictor variables, create a dataset with the following columns:

* City
* 2010 Census Population
* Total Pawdacity Sales
* Households with Under 18
* Land Area
* Population Density
* Total Families
