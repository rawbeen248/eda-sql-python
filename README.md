# SQL and Python Data Analysis and Visualization Project on the Chinook Database

This project performs a comprehensive data analysis on the Chinook Database using SQL, Python, and data visualization techniques. The Chinook Database holds information about a music store. For a deeper understanding, it is divided into 11 tables namely: 'Employee', 'Customer', 'Invoice', 'InvoiceLine', 'Artist', 'Album', 'Track', 'Genre', 'MediaType', 'Playlist', and 'PlaylistTrack'.

## Objective

The objective of this project is to answer meaningful business-oriented questions about the company's operations. This includes information on sales, customers, employee performance, and more.

## Technologies

This project is implemented using SQL for database querying, Python for data processing and visualization, and Matplotlib for generating the graphs. SQLite was used for the database.

## Methodology

1. Inspect all tables in the database: SQL queries are written to fetch the contents of each table, display the first few rows, and understand the structure of the data.

2. Check for missing data: A Python function iterates over each table and column, checking for any missing values.

3. Answer business questions using SQL: 20 business-oriented questions are addressed, allowing for exploration of a variety of SQL queries, enhancing understanding and showcasing SQL skills.

4. Visualize the results: After querying the database, Python and Matplotlib are used to create visualizations that will help better understand the data and the findings.

## Questions Addressed

This project answers the following questions:

1. What is the total revenue per country?
2. Who are the top 5 customers by revenue?
3. What are the top 10 best selling tracks?
4. What percentage of total revenue does each country contribute?
5. What are the top 5 albums by sales?
6. What percentage of total sales does each genre represent?
7. Who are the top 3 employees by sales?
8. What is the sales data per year?
9. What is the sales data per month?
10. How many customers does each employee support?
11. What percentage of total sales does each media type represent?
12. How many playlists include each track?
13. What is the total time length of all tracks sold per genre?
14. What percentage of total revenue does each media type contribute?
15. What are the top 5 countries by invoice count?
16. What is the distribution of sales among the different billing cities?
17. How many invoices were there each year?
18. How many tracks are there in each playlist?
19. What is the average invoice total per country?
20. What is the average number of tracks per album?

## Repository Contents

* 'eda_sql_python.ipynb': Jupyter notebook containing all the SQL queries, data analysis steps, and visualizations.
* 'Chinook_Sqlite.sqlite': SQLite database file.
* 'README.md': This file, providing an overview of the project.

## How to Run

To run this project on your local machine, follow these steps:

1. **Clone the Repository**: First, clone this repository to your local machine using the following command in your terminal or command prompt:
```bash
git clone https://github.com/rawbeen248/eda-sql-python
```
2. **Navigate to the Cloned Directory**: Use the following command to go to the cloned directory:
```bash
cd eda-sql-python
```
3. **Install Required Python Libraries**: This project requires Python and some Python libraries. You can install the necessary libraries using the following command:
```bash
pip install pandas matplotlib sqlite3
```
4. **Open the Jupyter Notebook and run the cells**: Once the Jupyter notebook is open, you can run each cell by selecting the cell and clicking on 'Run' or using the shortcut Shift + Enter. The SQL queries will fetch data from the database and the Python codes will process and visualize the data.

Please note that the SQLite database file Chinook_Sqlite.sqlite should be in the same directory as the Jupyter notebook for the code to run properly.
