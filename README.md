# Music Store Analysis using PostgreSQL

This repository contains an analysis of music store data using PostgreSQL, aimed at gaining insights into various aspects of the music store's operations. The analysis covers customer behavior, sales trends, and inventory management. The data was extracted from the music store's database and organized into a series of SQL queries and scripts for comprehensive analysis.

## Introduction

In this analysis, we aim to explore the music store's database to understand customer preferences, top-selling products, revenue trends, and inventory management. The database includes tables for customers, invoices, tracks, albums, and genres.

## Database Schema

The database schema includes the following tables:

- `customers`: Contains customer information such as name, email, and country.
- `invoices`: Contains invoice details including customer ID, date, and total.
- `invoice_items`: Contains details about items in each invoice including track ID and quantity.
- `tracks`: Contains information about individual tracks including name, composer, and genre ID.
- `albums`: Contains album information including title and artist ID.
- `genres`: Contains genre information.

## Queries and Analysis

The analysis includes several SQL queries that provide insights into various aspects of the music store's operations:

1. **Top Selling Genres**: Identify the top-selling genres based on the number of tracks sold.
2. **Customer Buying Habits**: Determine the average number of invoices per customer and the average total spent per customer.
3. **Album vs. Individual Tracks**: Compare sales revenue from album purchases versus individual track purchases.
4. **Employee Sales Performance**: Evaluate the sales performance of each employee based on the total sales amount.
5. **Popular Tracks**: Find the most popular tracks by considering the number of times each track has been purchased.
6. **Sales by Country**: Analyze sales by country, including total revenue, average order value, and customer count.
7. **Inventory Management**: Examine inventory status by counting the number of tracks per album and identifying the tracks with the shortest supply.

## Usage

1. Clone the repository to your local machine.
2. Set up a PostgreSQL database and import the provided database dump.
3. Update the database connection details in the analysis scripts.
4. Execute the SQL scripts in the preferred order to perform the analysis.

## Results

The analysis results will provide insights into customer behavior, popular products, employee performance, and inventory management. Visualizations can be created using external tools for clearer understanding and presentation.

## Conclusion

By analyzing the music store's database using PostgreSQL, we have gained valuable insights into various aspects of the business. This analysis can guide decision-making processes related to inventory management, marketing strategies, and customer engagement.

Feel free to explore the provided SQL scripts and adapt the analysis to suit your specific business needs.

For any questions or suggestions, please contact vishalsharma3657@gmail.com
