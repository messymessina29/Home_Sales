# Home_Sales
This challenge uses SparkSQL to analyze metrics about home sales data. Spark is used to read the home_sales csv into a df and then used to run SQL commands to analyze the average prices of homes sold based on different metrics like date_built, number of bedrooms and bathrooms, square footage, and view. This challenge also compares the runtimes of SQL commands using different methods of storing data such as uncached, cached, and partitioned data. The cached data proved to result in the fastest runtime of the SQL command.