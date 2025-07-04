# PIZZA-SALES-INSIGHT

## TABLE OF CONTENTS
- [Data_Overview](#data-overview)
- [Content](#content)
- [Data_Sources](#data-sources)
- [Observations_During_Data_Cleaning_and_Preparation](#observations-during-data-cleaning-and-preparation)
- [Findings](#findings)
- [Recommendation](#recommendations)
- [References](#references)

## DATA OVERVIEW
This Pizza sales analysis was conducted for the period from January to December 2015, focusing on Pizza sales to understand customer preferences, with a total of 48,620 pizza orders. This Analysis was done with the Excel Data Analysis Tool.
The Following Insights were analyzed; These are:
- Sales Trends: Here, the peak order times for pizza were ascertained, and days with the highest numbers of orders.
- Popular Products: The most ordered pizza, the most popular pizza size, and the most popular pizza by category were analyzed.
- Revenue Analysis: The highest revenue-generating pizza was identified, the average order value was calculated, and the revenue comparison between pizza categories.
- Customer Preferences: This is where the customer's preference based on vegetarian and non-vegetarian was analyzed.
- Order Patterns: Here, sales were analyzed based on how often customers order more than one pizza at a time.
- Pricing Insights: The price range of the pizzas sold was identified, and the unit prices of pizzas across different sizes and categories were evaluated.
- Finally, time-based insight was assessed, where the  periods with unusually high or low sales were investigated.

## CONTENT
The dataset comprises the following;
48,612 rows and 12 columns.
In the 12 columns, we have the following headers;
- a. Pizza ID: This is the number of the Pizza
- b. Order ID: This has to do with the order number of the pizza sold.
- c. Pizza name ID: This is how the pizzas are coded based on their names
- d. Quantity: This is the column where the number of pizzas sold at that time is inputted.
- e. Order date: This is the column for the date when the pizza was sold.
- f. Order time: This is the column to indicate the period the pizza was sold.
- g. Unit Price: This is the selling price for each pizza sold.
- h. Total Price: This is the column for the total pizzas sold in quantity over a particular period.
- i. Pizza Size: This is the size of the pizza sold; they are classified as Medium(as “M”), Large (as “L”), and Small (as “S”).
- J. Pizza Category: This has to do with how the pizzas are categorized based on ( Chicken, Classic, Supreme, and Veggie).
- k. Pizza Ingredients: This column has to do with the ingredients used in making the pizza sold.
- l. Pizza Name: These are the names of how pizzas are named.

## DATA SOURCES
The data is an Excel file, and it is a practical dataset.

##  OBSERVATIONS DURING DATA CLEANING AND PREPARATION:
The Analysis tool used to evaluate and analyze this dataset is 	Excel.
* From the original dataset collected, we had 48,621 rows and 12 	columns.
* The column for Order date was divided into the following: Order days(Days of the week),
  Order month(Month of the year in words) and order year.
* A new column was created to indicate vegetarian and non-vegetarian customers.
* The Non-vegetarian customers are identified with the intake of beef, meat, and chicken.
* Due to the changes made, the number of columns has increased to 16 from 12.
* The Engine in Excel that was used to transform this data to a proper analyzable dataset is the Power Query Editor.


## FINDINGS
#### - HIGHEST SALES PER GROUP
  * Peak Order Time for Pizza: 12 PM
  * Most Ordered Pizza by Category: Classic with 30% orders
  * Most Ordered Pizza by Name: The Classic Deluxe Pizza
  * Customer's Preference: Vegetarian
  * Highest Ordered Days: Friday with 16%
  * Highest Pizza Size : Large(L)
  * Revenue by Category: Classic Pizza with ₦220,053.10
  * Revenue by Pizza Name: The Thai chicken Pizza with ₦43,434
  * Period with unusually High sales: August 12PM noon (with Classic Pizza)

#### - LOWEST SALES PER GROUP
  * Least Order Time for Pizza: 9 AM
  * Least Ordered Pizza by Category: Chicken Pizza with 22%
  * Least Ordered Pizza by Name: The Brie Carre Pizza
  * Customer's Preference: Non-Vegetarian
  * Least ordered days: Sunday with 12%
  * Least Pizza size Ordered : XXL (Extra extra Large)
  * Lower Revenue by Category: Veggie Pizza ₦193,690.45
  * Lower Revenue by Pizza Name : The Brie Carre Pizza
  * Period with unusually Low sales: 9AM to 10AM in October, July, June,April,March, February and November.
    

















