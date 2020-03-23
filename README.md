# Liquor Sales Supervised Learning Project

Identify trends in Luxco Inc's liquor sales for Iowa. 

How well a liquor distributor prevents stockouts, optimizes distribution, and effectively advertizes can make or break thier success. The purpose of this project is to identify trends for Luxco Inc's liquor sales in Iowa that are critical to operating optimally. 

# DATA:

There are two sources of data in my project
1) Iowa Liqour Sales
2) Iowa Population Demographics

# DATA ANALYSIS:

# 1 : Exploratory Analysis:
This includes using the liquor sales dataset to visualze the relationships between sales (in dollars) and other features.

# 2 : Modeling Sales:
This includes using both datasets to predict yearly sales per county in Iowa using data from the previous year.


-----------------------------------------------------------------------------------------------------------

# Analysis 1 - Exploratory Analysis
- I divide the analysis into the following parts:

**A) Yearly Analysis**: sales per category, sales per county, sales per bottle volume

**B) Monthly Analysis**: total sales, sales per category

**C) Identifying Customer Base**: Analyzing relationship between population demographics and sales per county. 

**D) Predicting Sales**: Using demographic and sales data from 2017 to predict yearly sales per county for 2018.

# A) Yearly Analysis :
**Step 1 : Identifying the data**
In this step, I preformed the following using Google BigQuery
- Identify top distributers in Iowa Liquor Sales dataset, and audit the variety of alcohol each sells. 
- Filter dataset by a top distributer that selles a wide variety of alcohol -- Luxico Inc-- and year -- 2017-2018.

# Conclusion: Luxico Inc is the second largest distributer in Iowa, and sells 34 different categories of alcohol. 

# A) Yearly Analysis :
**Step 2 : Exploring the data**
In this step, I preformed the following using pandas functionalities
- Examine volume of liqour sold in gallons grouped by category
- Examine volume of liquor sold in gallons grouped by county
- Examine volume of liquor sold in gallons grouped by bottle size 

# A) Yearly Analysis :
**Step 3 : Visualizing the data**
In this step, I visualized the previous findings using plotly.express 

<img src="https://github.com/hobediente/.png"></img>

# Conclusion: American Vodkas account for nearly half of all sales

<img src="https://github.com/hobediente/.png"></img>

# Conclusion: Ten out of ninety-nine counties account for over sixty percent of sales

<img src="https://github.com/hobediente/.png"></img>

# Conclusion: 1750ml, 1000ml, and 750ml the dominate size of bottles sold

# B) Monthly Analysis :
**Step 1 : Exploring the data**
In this step, I preformed the following using pandas functionalities
- Examine total sales per month
- Examine total sales per month by category of alcohol 


# B) Monthly Analysis :
**Step 2 : Visualizing the data**
In this step, I visualized the previous findings using seaborn

<img src="https://github.com/hobediente/.png"></img>

# Conclusion: Sales appear to spike in even numbered months and fall in odd numbered months.

<img src="https://github.com/hobediente/.png"></img>

# Conclusion: Certain categories of alcohol appear to be seasonaly ordered i.e. mixto tequila, while others show more consistency. 

# C) Identifying Customer Base** :
**Step 1 : Exploring the data**
In this step, I preformed the following using pandas functionalities
- Examine the percentage of educated population over 25 per county
- Examine the percentage of population between 18 and 24 by county

# C) Identifying Customer Base** :
**Step 2 : Visualizing the data**
In this step, I visualized the previous findings using ploty.express

<img src="https://github.com/hobediente/.png"></img>

# Conclusion: Sales appear to spike in even numbered months and fall in odd numbered months.

<img src="https://github.com/hobediente/.png"></img>

# Conclusion: Certain categories of alcohol appear to be seasonaly ordered i.e. mixto tequila, while others show more 

**D) Predicting Sales**:
In this step, I preformed the following to prepare the data for modeling 
- 

# Analysis 2 - Modeling Sales
