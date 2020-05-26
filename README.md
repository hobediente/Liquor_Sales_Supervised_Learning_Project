# Liquor Sales Supervised Learning Project

Identify trends in Luxco Inc's liquor sales for Iowa. 

How well a liquor distributor prevents stockouts, optimizes distribution, and effectively advertizes can make or break thier success. The purpose of this project is to identify trends for Luxco Inc's liquor sales in Iowa that are critical to operating optimally. 
 
<img src="https://github.com/hobediente/Liquor_Sales_Supervised_Learning_Project/blob/master/LuxcoLogo-ad-1020x372.png"width="740" height="300"></img>

# DATA:

The data for this project is sourced from two places
1) Iowa Liqour Sales - Google BigQuery (https://console.cloud.google.com/marketplace/details/iowa-department-of-commerce/iowa-liquor-sales) - Each observation is an invoice for a liqour sale that contains geographic, vendor, and sale item(s) information.

2) Iowa Population Demographics - Iowa Government Website (https://data.iowa.gov/) - Each observation contains County-level demographic and education information.

# DATA ANALYSIS:

# 1. Exploratory Analysis:
In this step the relationships between sales (in dollars) and other features are explored and visualized.

# 2. Modeling Sales:
In this step the unique dataset I put together is used to predict yearly sales per county in Iowa using data from the previous year.


-----------------------------------------------------------------------------------------------------------

# Exploratory Analysis
- I divide the analysis into the following parts:

**A) Yearly Analysis**: Sales per category, sales per county, sales per bottle volume

**B) Monthly Analysis**: Total sales, sales per category

**C) Identifying Customer Base**: Analyzing relationship between population demographics and sales per county. 

**D) Predicting Sales**: Using demographic and sales data from 2017 to predict yearly sales per county for 2018.

# A) Yearly Analysis :
**Step 1 : Selecting the data**

The following steps are preformed using Google BigQuery
- Identify top distributers in Iowa Liquor Sales dataset
- Audit top distributers by the variety of alcohol they sell
- Select a top distributer that sells a wide variety of alcohol -- Luxico Inc-- and subset data for years 2017-2018

### Conclusion: Luxico Inc is the second largest distributer in Iowa, and sells 34 different categories of alcohol. 

# A) Yearly Analysis :
**Step 2 : Exploring the data**

The following steps are preformed using pandas functionalities
- Examine volume of liqour sold in gallons grouped by category
- Examine volume of liquor sold in gallons grouped by county
- Examine volume of liquor sold in gallons grouped by bottle size 

# A) Yearly Analysis :
**Step 3 : Visualizing the data**

In this step, I visualize the previous findings using plotly.express 

<img src="https://github.com/hobediente/Liquor_Sales_Supervised_Learning_Project/blob/master/Images/Gallons_per_Category.png"></img>

### Conclusion: American Vodkas account for nearly half of all sales

<img src="https://github.com/hobediente/Liquor_Sales_Supervised_Learning_Project/blob/master/Images/Gallons_per_County.png"></img>

### Conclusion: Ten out of ninety-nine counties account for over sixty percent of sales

<img src="https://github.com/hobediente/Liquor_Sales_Supervised_Learning_Project/blob/master/Images/Gallons_per_Bottle_Size.png"></img>

### Conclusion: 1750ml, 1000ml, and 750ml the dominate size of bottles sold

# B) Monthly Analysis :
**Step 1 : Exploring the data**

In this step, I preformed the following using pandas functionalities
- Examine total sales per month
- Examine total sales per month by category of alcohol 


# B) Monthly Analysis :
**Step 2 : Visualizing the data**

In this step, I visualized the previous findings using seaborn

<img src="https://github.com/hobediente/Liquor_Sales_Supervised_Learning_Project/blob/master/Images/2017_Sales_Over_Time.png" width="600" height="300"></img>

<img src="https://github.com/hobediente/Liquor_Sales_Supervised_Learning_Project/blob/master/Images/2018_Sales_Over_Time.png" width="600" height="300"></img>

### Conclusion: Sales appear to spike in even numbered months and fall in odd numbered months.

<img src="https://github.com/hobediente/Liquor_Sales_Supervised_Learning_Project/blob/master/Images/2017_Category_Sales.png" width="740" height="300"></img>

<img src="https://github.com/hobediente/Liquor_Sales_Supervised_Learning_Project/blob/master/Images/2018_Category_Sales.png" width="740" height="300"></img>

### Conclusion: Certain categories of alcohol appear to be seasonaly ordered i.e. mixto tequila, while others show more consistency. 

# C) Identifying Customer Base** :
**Step 1 : Exploring the data**

In this step, I preformed the following using pandas functionalities
- Examine the percentage of educated population over 25 per county
- Examine the percentage of population between 18 and 24 by county

# C) Identifying Customer Base** :
**Step 2 : Visualizing the data**

In this step, I visualized the previous findings using ploty.express

<img src="https://github.com/hobediente/.png"></img>

### Conclusion: Sales appear to spike in even numbered months and fall in odd numbered months.

<img src="https://github.com/hobediente/.png"></img>

### Conclusion: Certain categories of alcohol appear to be seasonaly ordered i.e. mixto tequila, while others show more 

# D) Predicting Sales** :

In this step, I preformed the following to prepare the data for modeling 
- 

# Modeling Sales
