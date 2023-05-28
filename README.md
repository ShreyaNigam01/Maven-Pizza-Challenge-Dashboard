# Maven-Pizza-Challenge-Dashboard

For the Maven Pizza Challenge, you’ll be playing the role of a BI Consultant hired by Plato's Pizza, a Greek-inspired pizza place in New Jersey. You've been hired to help the restaurant use data to improve operations



I tried to answer some questions posed by Maven Analytics to be able to answer:

What days and times do we tend to be busiest?
How many pizzas are we making during peak periods?
What are our best and worst pizzas in terms of Revenue and Orders
What's our average order value?


About the dataset: 
This dataset contains 4 tables in CSV format
The Orders table contains the date & time that all table orders were placed
The Order Details table contains the different pizzas served with each order in the Orders table, and their quantities
The Pizzas table contains the size and price for each distinct pizza in the Order Details table, as well as its broader pizza type
The Pizza Types table contains details on the pizza types in the Pizzas table, including their name as it appears on the menu, the category it falls under, and its list of ingredients

Problem Approach:

1.	Data Integration and Transformation: The first step in the project involved connecting the Excel data to Power BI and using Power Query to transform the data,various data cleansing, shaping, and merging operations were performed to ensure the data was in the desired format for analysis.
2.	Data Modeling with Star Schema: To establish a robust data model, a star schema approach was adopted. The data was organized into dimension tables and fact tables, with clear identification of primary and foreign keys.
3.	Establishing Table Relationships: In order to build meaningful relationships between the tables, the appropriate connections were established based on the primary and foreign keys. 
4.	Creating Measures with DAX: To derive valuable insights from the data, measures were created using the Data Analysis Expressions (DAX) language. These measures involved aggregating and calculating key performance indicators (KPIs) and metrics that would be used in visualizations and reporting..
5.	Story Telling: Creating Visualizations, for deriving insights and answer queries of the Pizza store to improve the performance and sales using Order Performance over Quarter, Month and Day ,Revenue Performance over Quarter, Month and Day,Pizza performance analysis: orders and revenue by pizza type. Used KPIs, Line chart, Barchart, Column chart and  generated Heat map through conditional formatting.

Key Insights:
Orders
1.Total order is 21,350 in a year, Q3 has the highest amount of orders(5,437) and Q4 with lowest(5,118). July month has the highest number on order and October has lowest
2.Fridays get the most orders in the week, and Sundays gets the least.
3.The classic Deluxe is the most ordered pizza(2,329) and the Brie Carre is the least ordered(480)

Revenue ( $208,369.75) and Q4 has the lowest 
1.Total Revenue of $817,860 in a year. Q2 has the highest reveue of  $208,369.75 and Q4 has the lowest $ 199,124.05, July month recorded the highest Revenue and October records the lowest
2.Fridays have the highest revenue, Monday lowest.
3.On weekdays highest revenue genereting hours are 12pm-1pm ,on weekends it is 6pm-7pm. However, in entire week the highest revenue generating hour is 12pm-1pm from Monday to Friday
4.Average order Value(Total Revenue/Total order) is highest for November( $208,369.75) this might be due to festival season and lowest in August.
5.The Thai Chicken has generated the most revenue($43,434.25) and The Brie Carre has generated the least($11,588.50).

Pizza
1.The classic Deluxe is the most ordered pizza(2,329) and the Brie Carre is the least ordered(480)
2.The Thai Chicken has generated the most revenue($43,434.25) and The Brie Carre has generated the least($11,588.50).

