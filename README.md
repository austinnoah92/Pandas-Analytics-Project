EXPLORATORY DATA ANALYSIS (EDA) FOR COMPANY XYZ

Company XYZ owns a supermarket chain across the country. Each major branch located in 3 cities across the country recorded sales information for 3 months, to help the company understand sales trends and determine its growth, as the rise of supermarkets competition is seen to increase.

The data folder contains datasets from three different branches; Lagos, Abuja and Port Harcourt. Each data file from the branches contains the same attribute information and see below the attribute description. 


Description

Invoice ID: Customer Identification number 

Branch: Supermarket Branch across the country (A, B, C)
A - Lagos Branch
B - Abuja Branch
C - Port Harcourt Branch

City: Supermarket Location

Customer Type: Type of customers, Members - Returning customer with membership card, Normal - Customer without membership (could be returning, first-time or walk-in customer)

Gender: Customer Gender Information

Product line: Product categorization groups - Electronic accessories, Fashion accessories, Food and beverages, Health and beauty, Home and lifestyle, Sports and travel

Unit Price: Price of each product in Naira

Quantity: Number of products purchased by customer

Tax: 5% tax fee for customer buying

Total: Total price including tax

Date: Date of purchase (Supermarket Record available from January 2019 to March 2019)

Time: Purchase time (Supermarket Hours - 10am to 9pm)

Payment: Payment used by customer for purchase (3 methods are available – Cash, Card and Epay)

COGS: Cost of goods sold

Gross margin percentage: Gross margin percentage

Gross income: Gross income

Rating: Customer Satisfaction rating on their overall shopping experience (On a scale of 1 to 10)

# Project Steps

To better understand the data, the following processes were carried out:

Loaded the dataset and merged the three dataset as one for easier manipulation

Checked the shape of the dataset to get a glimpse of its number of features and observations

Did a statistical summary of the numerical features to understand measure of central tendency and dispersion of the dataset

Ascertained if there exist missing values and looked through the info of the dataset, another broader way to checck for null values and datatypes

Converted the datatype of Date and Time Features to datetime datatype

Extracted Day, Month Year and Hour, Minute from Date and Time cocncurrently creating new features for the result

Identified unique data in the categorical columns

Aggregation of data using particular columns

Visualisations


# Insights

From Dataset

Dataset comprises of 5000 observations and 17 features where 7 are categorical and the rest, numerical
There are no missing value and the numerical data didnt have any inconsiquentailities so there was no need for data cleaning.
The avearge unit price regardless of product line is 20041.9668, with the lowest being 3628.8 and the maximum price 35985.6. Rating on the average (using median value incase of outliers), regardless of the product line, is 7 out of 10. This shows that customers are satisfied with the Supermarket's product, although it can get better.
On average 5 units of each item are sold with an average gross margin percentage of 4.7%

From the Analysis

At the Abuja branch, the payment types usage were almost at par with Epay used slightly above others. However, Lagos branch experienced more of Epay means of payment while Portharcourt experienced more of cash.

Immediately following the first point is that Cash was aggresively utilized more for Electronic accesories, in fact, it is in this product line that cash was used the most.

Highest sales was accounted for by Home and lifestyle and the lowest Fashion accessories.

The supermarket had its highest gross income, (NGN 9477317.7) from the Portharcourt branch and the lowest from the Abuja branch (NGN 9102657.6).

Across board, Epay was often used as Cash while Card method was the least used. 

Abuja had the lowest product rating on the average at about 6.7/10 while the others were at 7/10.

Females accounted for most quantites sold per product line. Infact, 83% of the product line were dominated  by females. However, surprisngly, Health and beauty had more quantity bought by males than females. Quiet suprising because its generally a strong hold for females.


# Future Work

Much work has been carried out, but predictive models should be implemented to undertsand customer buying behaviours using customer segmentation for better targeting. Also, causal analysis should be carried out on the features to better undertand features that are important for insight generation into the way sales are. This could help the supermarket do come up with better pricing strategies alongside inventory strategies to meet customer needs.

# Standout Section

Between January and March (the only months recorded in the dataset), only Health and bueaty alongside Electronic accessories product lines had an increasing sales, others either had decreasing sales like Food and beverages or flunctuating sales like Food and beverages.

Highest sales is recorded between 6pm and 7pm while the lowest at 8pm. However, worthy of note is that, between 4pm - 6pm, sales are low, but between 6pm and 7pm, sales accelerate non-stop until 7pm.


# Executive Summary.

Include your Executive Summary document in your repository.




