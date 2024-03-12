# Home_Sales
## Module 22

### Instructions

1. Rename the `Home_Sales_starter_code.ipynb` file as `Home_Sales.ipynb`.
2. Import the necessary PySpark SQL functions for this assignment.
3. Read the `home_sales_revised.csv` data in the starter code into a Spark DataFrame.
4. Create a temporary table called `home_sales`.
5. Answer the following questions using SparkSQL:
    - What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.
    - What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? Round off your answer to two decimal places.
    - What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.
    - What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.
6. Cache your temporary table `home_sales`.
7. Check if your temporary table is cached.
8. Using the cached data, run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.
9. Partition by the "date_built" field on the formatted parquet home sales data.
10. Create a temporary table for the parquet data.
11. Run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.
12. Uncache the `home_sales` temporary table.
13. Verify that the `home_sales` temporary table is uncached using PySpark.
14. Download your `Home_Sales.ipynb` file and upload it into your "Home_Sales" GitHub repository.

### Support and Resources
Your instructional team will provide support during classes and office hours. You will also have access to learning assistants and tutors to help you with topics as needed. 
Make sure to take advantage of these resources as you collaborate with your partner on this project.
