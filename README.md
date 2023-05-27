# Maven-Pizza-Challenge-Dashboard

For the Maven Pizza Challenge, you’ll be playing the role of a BI Consultant hired by Plato's Pizza, a Greek-inspired pizza place in New Jersey. You've been hired to help the restaurant use data to improve operations



I tried to answer some questions posed by Maven Analytics to be able to answer:

What days and times do we tend to be busiest?
How many pizzas are we making during peak periods?
What are our best and worst pizzas in terms of Revenue and Orders
What's our average order value?


About the dataset: This dataset contains 4 tables in CSV format

The Orders table contains the date & time that all table orders were placed
The Order Details table contains the different pizzas served with each order in the Orders table, and their quantities
The Pizzas table contains the size and price for each distinct pizza in the Order Details table, as well as its broader pizza type
The Pizza Types table contains details on the pizza types in the Pizzas table, including their name as it appears on the menu, the category it falls under, and its list of ingredients

Problem Approach:

1.	Data Integration and Transformation: The first step in the project involved connecting the Excel data to Power BI and using Power Query to transform the data,various data cleansing, shaping, and merging operations were performed to ensure the data was in the desired format for analysis.
2.	Data Modeling with Star Schema: To establish a robust data model, a star schema approach was adopted. The data was organized into dimension tables and fact tables, with clear identification of primary and foreign keys.
3.	Establishing Table Relationships: In order to build meaningful relationships between the tables, the appropriate connections were established based on the primary and foreign keys. 
4.	Creating Measures with DAX: To derive valuable insights from the data, measures were created using the Data Analysis Expressions (DAX) language. These measures involved aggregating and calculating key performance indicators (KPIs) and metrics that would be used in visualizations and reporting..
5.	Story Telling: Creating Visualizations, for deriving insights and answer queries of the Pizza store to improve the performance and sales using Order Performance over Quarter, Month and Day ,Revenue Performance over Quarter, Month and Day,pizza performance analysis: orders and revenue by pizza type.
