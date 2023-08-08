### Summary of Assignment

1. **Spark DataFrame Creation**: I successfully created a Spark DataFrame utilizing the given dataset.

2. **Temporary Table Formation**: I generated a temporary table using the original DataFrame to facilitate further operations.

3. **Queries Execution**:
   - **Four-Bedroom Houses**: I computed the average price for four-bedroom houses sold in each year, rounded to two decimal places.
   - **Three Bedrooms and Three Bathrooms**: I determined the average price for homes with three bedrooms and three bathrooms, rounded to two decimal places.
   - **Specific Criteria**: I calculated the average price for homes meeting certain criteria (three bedrooms, three bathrooms, two floors, and at least 2,000 square feet) for each year built, rounded to two decimal places.
   - **View Rating Query**: I derived the view rating for the average price of homes greater than or equal to $350,000, rounded to two decimal places, and recorded the run time for this query.

4. **Caching Implementation**:
   - **Cache Creation and Validation**: I created a cache of the temporary "home_sales" table and verified its correctness.
   - **Cached Query Execution**: I ran the query from the view rating query on the cached temporary table and computed the run time.

5. **Partitioning and Parquet Data Handling**:
   - **Partitioned Home Sales**: I partitioned the home sales dataset by the "date_built" field and read the formatted parquet data.
   - **Temporary Parquet Table Creation**: I made a temporary table of the parquet data to enable efficient querying.
   - **Parquet Query Execution**: I executed the view rating query on the parquet temporary table and computed the run time.

6. **Table Uncaching**: I successfully uncached the "home_sales" temporary table and verified the process.
