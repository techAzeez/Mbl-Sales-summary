# Project Name: Mbl-data-summary

By Azeez Adewale
----
# Introduction:
Marbel Home & kitchen wares is into the business of selling home and kitchen gadgets, delivering nationwide in Nigeria. The business is taking a proactive step to a sustainable and increased growth in future, it therefore, desires to make best use of the little data captured over a period of one year to make informed marketing decision. 

Note: The store name is not real name. 

----
# Project Goals: Problem Statement
To better understand the sales performance of the products and the customers of Marbel Home & Kitchen wares, to see the best possible ways to make more sales.

This will help us: 
* Identify top-selling products and locations.
*	Identify the value customers.
*	Create a targeted marketing campaign that will appeal to customers.

**Key Questions:**

*	Top 10 selling products
*	Top 10 categories
*	Top 10 locations
*	Gender
*	Profit by months
*	Profit by days
*	Total Orders
*	Revenue
*	Net Profit
*	Percentage Profit
*	Number Of customers
*	Number of returning customers
*	Number of new customers


----
# Data Sourcing: 
Data was captured in an excel file as customers made there order and the sales were closed, this happened largely through one of the stores social media handle, though lately the store launched a website, sales are gradually picking up from there. 
Data of the customers, products and orders were captured in the customers, products and orders table respectively.
Going forward sales data will be exported from the ecommerce website and processed for analysis. 


----
# Data Transformation:
The dataset had to go through a thorough data cleaning process, like we all know human error are most likely in data entry, so there were anomalies in the dataset. Poor date formatting, missing data, outliers to mention a few, were part of the anomalies I had to correct. As for the poor date formatting I had to use the TEXT TO COLUMN option to split the date entry and used the DATE formula to put them in the right format (yyyy-mm-dd).
For the missing data I had to seek clarification from the originators of the data and that helped a lot in filling the missing data with the right ones.
Some outliers were detected after I carried out EDA on some of the metrics using the MIN, MAX function.
I used the VLOOKUP function to flatten the orders table to merge some fields from the customers and products table into the orders table as it is my fact table.
I used the IF and COUNTIFS functions to get the number of repeat customers the business had over the period of one year.
And I was able to also format the fields to the right data type.


----
# Findings & Insights
**Top 10 selling products** 

![top10products](https://user-images.githubusercontent.com/108735886/182164032-173ddc6b-a573-4ccc-af00-99d2e9b9accb.png)


*	There over 300 products listed on Marbel store online. 
*	Total sales from the top 10 products is over 12 million naira which make up 37% of the total revenue. 
*	This indicates the viability of these products.

**Top 10 selling Category**

![top10category](https://user-images.githubusercontent.com/108735886/182164086-d8df14f0-01fb-4925-8bd2-f2b425800442.png)


*	There are about 27 categories of products listed online by Marble Marketplace.
*	Sales from these top 10 categories make up 92% percent of the total revenue.
*	This indicates the viability of products under these categories.

**Top 10 selling Locations**

![top10states](https://user-images.githubusercontent.com/108735886/182164133-0b37318c-0123-41d9-9f4e-073f4c5fad12.png)


*	Marbel marketplace have a location reach of about 30 states. 
*	Sales in the 10 states account for 89% of the total revenue.
*	This indicates the locations of the businesses potential customers.

**Revenue By Gender**

![RevenueByGender](https://user-images.githubusercontent.com/108735886/182164184-cf82f368-a530-4cff-80d7-a0f85a77880e.png)


*	The customers are mostly female.

**Revenue By Months**

![RevenueByMonths](https://user-images.githubusercontent.com/108735886/182164227-561f53bb-9b54-484f-947e-db16f53ee828.png)


*	The business experienced increase and decrease in revenue through different months.
*	This indicates a likely negative revenue growth rate.

**Revenue By Days**

![RevenueByDays](https://user-images.githubusercontent.com/108735886/182164263-3b4d9d8c-fdc1-4146-b641-3531062648fc.png)


*	Sales were high mostly during the week.
*	Sales were high from Monday - Friday and declined on Saturday.
*	Sales was at the peak on Tuesday.


----
# Summary Findings

*	Most of the customer’s order from Lagos, Abuja, Osun, Delta, Rivers, Oyo, Ogun, Ibadan, Kwara and Edo state. 
*	There are 463 customers, part of which 205 are repeat buyers and 258 are new buyers.
*	This is indeed an asset for the business as about 44% of its customer base are repeat buyers.
*	Also the customer base keeps expanding as more new buyers are gained over time.
*	Based on research a good customer retention rate is between 20% - 40% and the business has over 40%. 
*	The customers are mostly female just 2% of the customers are male.
*	A small number of items had great impact on revenue. 



----
# Recommendations

**Product recommendations:**

 The 80/20 rule says 80% of outcomes comes from 20% causes.
 In Marbel marketplace case just about 2.5% of the products brought about 37% of the total revenue. 
 
*	A larger percentage of Advert campaign budget should be designated for the top 10 products as they are the best selling products.
*	More products should be explored from the top 10 categories for advert campaign sponsor.
*	Contents which appeal majorly to the female gender should be written to promote the top 10 products and products under the top 10 categories as they make the bulk of the bestselling products.

**Marketing recommendations:**

Although revenue growth rate seem to be negative, but the customer retention rate means great asset to the business.
And as we can see the business still made 35% profit margin.

*	Advert Campaign of new products should be targeted at the repeat customers, because they are already willing to buy over and over again.
*	Loyalty programs should be put in place in order to reward repeat customers, to keep them and make them want to buy more and also convert new buyers to repeat buyers.
*	An efficient after sales support should also be in place for both existing and new customers.
*	The business can seek referrals from the existing customers as they are already ambassadors of the business.
*	The business can seek reviews from the existing customers and run them as campaigns to build trust in the new customers and gain more of new customers. 
*	The campaign should target the locations from the above listed top 10 locations.
*	The advert contents should appeal the female gender as they make up 98% of the businesses customers. 
*	Advert campaigns should be more active during Mondays through Fridays unlike the weekends.


