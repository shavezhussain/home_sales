# House_Sales

**Summary:** Using knowledge of SparkSQL, determine key metrics about home sales data. Then, use Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

**Results:** 

*What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places?*

<img width="234" alt="Screenshot 2023-10-17 at 5 41 10 PM" src="https://github.com/amaramh10/House_Sales/assets/131200333/925cedf7-9e56-4820-92c1-6e2e16cb6e68">

*What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places?*

<img width="234" alt="Screenshot 2023-10-17 at 5 42 05 PM" src="https://github.com/amaramh10/House_Sales/assets/131200333/899d0bdc-8b8d-444d-9f29-4825630e4e0f">


*What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.*

<img width="233" alt="Screenshot 2023-10-17 at 6 25 01 PM" src="https://github.com/amaramh10/House_Sales/assets/131200333/b3dd3dd5-eb4f-49d4-a8c7-65756d8b3ebc">


*What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.*

<img width="245" alt="Screenshot 2023-10-17 at 5 42 27 PM" src="https://github.com/amaramh10/House_Sales/assets/131200333/1e42750d-3042-4eaf-acd2-06ffaff3cd5f">


*Using the cached data, run the query that filters out the view ratings with average price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.*

<img width="243" alt="Screenshot 2023-10-17 at 5 43 17 PM" src="https://github.com/amaramh10/House_Sales/assets/131200333/f86f6bb6-8ef6-425e-813a-f04ef6adbb05">


*Run the query that filters out the view ratings with average price of greater than or eqaul to $350,000 with the parquet DataFrame. Round your average to two decimal places. Determine the runtime and compare it to the cached version.*

<img width="239" alt="Screenshot 2023-10-17 at 5 44 02 PM" src="https://github.com/amaramh10/House_Sales/assets/131200333/98b00d6c-1515-4d28-ae1e-216eae4b50f8">


**Conclusion:**

Both the partitioned and cached data's runtime took longer than the original data set. 





