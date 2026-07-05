# Power-BI-week-2-assignment
# The objectives
- were to anlyse the data for the company to come up with clear insights and recommendations.
- To be able to be able to calculate the total gross profit of the company.
- To determine the total units sold based on the various categories like the car make, region, sales rep and the branch and the region.
- To find out the top performing car make and model.
- Identifying the top performing customers by revenue.
- Finding out the relationship between the discount and the revenue.
- Finding out the top performing sales representatives.
 # How you imported the data into Aiven
-  After cleaning the public jcars data and creating the necessary dashboards. Using the already existing PostgreSQL sevice in Aiven, connection was achieved through
   host,database name,username,port and password provided in the Aiven service dashboard.
-  DBeaver was used to import the jcars document to the PostgreSQL database.
 - Once the import was complete, SQL queries were executed to confirm that all records had been loaded successfully and to perform additional data validation checks.    The imported data was then ready for analysis and visualization in Power BI.
# How you connected power BI to the database
- Open Power BI Desktop and select Get Data.
- Choose PostgreSQL Database as the data source.
- Enter the Server (host name and port) and Database name provided by Aiven.
- Click OK and enter the PostgreSQL authentication credentials (username and password).
- Load the data into Power BI
# The measures and calculations you created
- DATEDIFF() It was used to prepare the lead time.
- sum() was used to calculate the total units sold and total revenue
- Average() was used to calculate the average ratings
- Trim and Clean was used to get rid of the extra spaces.
- New measures created were; Total revenue, Total units sold, Average rating, Gross Profit and margin etc
# The visuals included in your dashboard
- slicers
- Donut chart
- Line Chart
- Cards
- KPIS
- Stacked Bar Chart
- Clustered Bar chart
  # Your key insights & Your recommendations
- One of the business recommendation that i can share is that some of the branches for example the Kisumu Branch, Main Branch and Nairobi yard can be closed this   is because the gross margin and gross profit are not breaking even. This indicates that there are losses that are being made. Closing down the branches or  merging them can result to better allocation of resources.
- The company should improve more on their marketing and inventory on the best performing cars to boost the sales.
- The focus should be on the highly demanded cars.
- Some of the most returned cars like Toyota Harrier that has had 16 returned and Fit that has had 21 returned can be kept out of the yard for some time until   their problem is resolved. The return rate can cause a bad reputation to the company.
- Their is no relationship between the discount and the revenue as they don't affect the overall performance of the various branches.
- Toyota has the most units sold which is 121.
- Instagram is the top lead source.
- The dealers are the top customer type with the highest revenue.

  
