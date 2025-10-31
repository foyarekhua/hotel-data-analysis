# hotel-data-analysis
## Goal
Develop a database to analyze and visualize hotel booking data.
## Research questions
- Is our hotel revenue growing by year? It would be good to see the revenue by hotel
- should we increase our parking lot size
- what trends can we see in the data
## Summary (view the data in other files of this repo)
1. Take the data from excel and import it to mysql
2. There are tables of hotel data by year. Create a database and join those tables using SQL
3. Connect Power BI to the database
4. visualize the data
## key challenges and solutions
1. Encoding issue where there would be random characters before column names. **Fix**: `ALTER TABLE your_table CHANGE COLUMN 'ï»¿name' name VARCHAR(255)`;
2. Connecting MySQL to PowerBI. **Fix**: Download MySQL connector
## What I learned
- How to build and connect slicers to make dashboards interactive
- How to create a custom column in powerbi
- How to visualize data in powerbi
- How to use a line chart, donut chart and matrix in powerbi
## Why it matters
- This demonstrates my ability to work with real-world style data where I have to generate wanted information from other data (for example, calculating revenue)
- This also demonstrates my ability to show data in a visual and easy to understand way
