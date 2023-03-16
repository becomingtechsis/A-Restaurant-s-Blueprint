# A-Restaurant-s-Blueprint
![](https://github.com/becomingtechsis/A-Restaurant-s-Blueprint/blob/main/bg.jpeg)

## Objective
This project is to display my data cleaning, critical thinking and visualization skills.
- The [problem satatement](https://github.com/becomingtechsis/A-Restaurant-s-Blueprint/blob/main/zomato%20business%20demand.docx) is an imaginary case scenario I thought about after seeing the dataset.

## Introduction
The aim of this analysis is to help new restaurants in deciding their theme, menus, cuisine, cost, location etc. For maximum profit. It also aims at finding similarities between neighborhoods of Bangalore on the basis of food and audit. For this analysis report, I’ll be using Bangalore City as our report location. Bangalore City is a place with a very small population in the province of Karnataka, India which is located in the continent/region of Asia. 

### After thinking critically, five questions needs answers:
1. How familiar is the client's Restaurant Type in Bangalore Food Market?
2. What are the Location options in Bangalore city? 
3. What is the Average cost of an average Bangalore resident?
4. Who are the Top competitors of the Restaurant type in the Bangalore Food Market?
5. What Business Facilities should be added in the startup planning to aid maximum profit?

## Data Sourcing
Ideally, one way to gather data for an analysis as this, is by using a survey. Or downloading certain data sets. 

## Dataset
In this case, I’ll be using the Zomato Restaurant data gotten from Kaggle. The dataset is a [CSV](https://www.kaggle.com/datasets/himanshupoddar/zomato-bangalore-restaurants) file saved locally in a folder. This data set is a huge CSV file containing over 56000 rows and 17 columns.

## Data Transformation.
Cleaning up the data, I deleted unwanted columns like phone numbers, reviews, etc. Renamed columns like list(type) to Restaurant Type. 
- Emptied empty rows
- Formatted the data types. 
- For the average rating column, I extracted the column by delimiter to avoid getting blank output. Extracted by the “/” delimiter, I removed errors and adjusted the data type.

# 1. Restuarant Type Familarity.
Since the client's Restuarant type is a fast food company. If I select Dine-out as a restaurant type, I’ll see then that the Bangalore people will spend around 536 rupees as their average bill amount. And the avg rating for a Dine-out restaurant type is 3.53. With a total vote of 99,600.

![](https://github.com/becomingtechsis/A-Restaurant-s-Blueprint/blob/main/dine_out.png)

# 2. Location Options. 
if I select Brookefield as my location, I can see the restaurant types available in that region. The avg bill amount for Brookefoeld is 401 Rupees. Meaning an avg Brookfield resident is likely to spend 401 Rupees. The cusines available in Brookefield are displayed in the word cloud. The Avg rating for Brookefield is 3.38 and has a total vote of 19,000. Along with the top 10 competitors in the region.  

![](https://github.com/becomingtechsis/A-Restaurant-s-Blueprint/blob/main/location.png)

I would advise to settle for a location with either the highest rating, or the highest vote.


# 3. Average Bill Amount
The Average bill amount of an Average Bangalore person is around 535 rupees. 
![](https://github.com/becomingtechsis/A-Restaurant-s-Blueprint/blob/main/avg_bill_amt.png)

# 4. Business Facilities.
Another avenue of getting maximum profit is by putting certain facilities in place. It could be table bookings either through an app or website. Or it could be placing orders online. For example;
For a Dine-Out restaurant type, if you select table booking, the Avg bill amount becomes 1,653 Rupees. With over 1,000,000 votes and an Avg rating of 4.17.

![](https://github.com/becomingtechsis/A-Restaurant-s-Blueprint/blob/main/facility.png)

 But if they approach the restaurant directly, without booking a table, then they will spend around 536 rupees. As seen above
And If a customer books a table, the word cloud will show preferred cuisines for table reservations. 

# 5. Top Competitors.
For Dine-Outs, the top 10 competiors can be seen in the bar chart below. 

![](https://github.com/becomingtechsis/A-Restaurant-s-Blueprint/blob/main/top%2010.png)

With “Truffles” been the top competitor. If you click on Truffle,

![](https://github.com/becomingtechsis/A-Restaurant-s-Blueprint/blob/main/truffle.png)


The avg bill amount becomes 900 rupees with 99,000 votes and 4.59 ratings.  





