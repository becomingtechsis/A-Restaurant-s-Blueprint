# A-Restaurant-s-Blueprint
[insert restaurant picture here]

## Objective
This project is to display my data cleaning, critical thinking and visualization.
The problem satatement is an imaginary case scenario I thought about after seeing the dataset.

## Introduction
The aim of this analysis is to help new restaurants in deciding their theme, menus, cuisine, cost, location etc. For maximum profit. It also aims at finding similarities between neighborhoods of Bangalore on the basis of food and audit. For this analysis report, I’ll be using Bangalore City as our report location. Bangalore City is a place with a very small population in the province of Karnataka, India which is located in the continent/region of Asia. [Attach bsuiness demand file link here]

### After thinking critically, five questions needs answers:
1. How familiar is the client's Restaurant Type in the Asia Food Market?
2. What are the Location options? 
3. What is the Average cost of an average asian resident?
4. Who are the Top competitors of the Restaurant type in the Asia Food Market?
5. What Business Facilities should be added in the startup planning to aid maximum profit?

## Data Sourcing
Ideally, one way to gather data for an analysis as this, is by using a survey. Or downloading certain data sets. 

## Dataset
In this case, I’ll be using the Zomato Restaurant data gotten from Kaggle. The dataset is a CSV[https://www.kaggle.com/datasets/himanshupoddar/zomato-bangalore-restaurants] file saved locally in a folder. This data set is a huge CSV file containing over 56000 rows and 17 columns.

## Data Transformation.
Cleaning up the data, I deleted unwanted columns like phone numbers, reviews, etc. Renamed columns like list(type) to Restaurant Type. 
- Emptied empty rows
- Formatted the data types. 
- For the average rating column, I extracted the column by delimiter to avoid getting blank output. Extracted by the “/” delimiter, I removed errors and adjusted the data type.

## Visualization.
Analysis was done using simple visuals since the tables had been properly cleaned.

## 1. Restuarant Type Familarity.
If I select Dine-out as a restaurant type, I’ll see then that the Bangalore people will spend around 1300 rupees as their average bill amount. 

## 2. Location SOptions. 
if I select Brookefield as my location, I can see the rest type available in the region. Seeing as there isn’t a dine out, desert, pub & bar. The avg bill amount for the Brookefoeld region is 401 Rupees. And the cusines available in the region are displayed in the word cloud. The avg rating for Brookefield is 3.38 and has a total vote of 19,000. Along with the top 10 competitors in the region.  
*Inserts picture*

## 3. Average Bill Amount
The average bill amount of an average Bangalore person is around 535 rupees. 
*inserts picture*

## 4. Facilities to Consider
When setting up a restaurant, one must provide adequate facilities for easy and efficient customer service. It could be table bookings either through an app or website. Or it could be placing orders online. For example;
For Dine-Out rest type, if you select table booking and select yes, the avg rating becomes 1,653 rupees. 
*insert book table image.
 But if they approach the restaurant directly, without booking a table, then they will spend around 536 rupees.
And If a customer books a table, the word cloud will show preferred cuisines for table reservations. The average bill amount, the votes, and top 10 restaurants offering the same service. Same applies for online orders.
*insert picture*

### 5. Top Competitors.
For Dine-Outs, the top 10 competiors can be seen in the bar chart below. 
Insert pic
With “Truffles” been the top competitor. If you click on it,
Insert pic
You'll see the avg bill amount been 900 rupees with 99,000 votes and 4.59 ratings.  


My goal is to provide value to the stakeholders and not just to build reports and dashboards.

