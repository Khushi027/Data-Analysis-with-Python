# Data-Analysis-with-Python

For this project I have used Python Pandas & Python Matplotlib to analyze and answer business questions about 12 months’ worth of sales data. The data contains data about electronics store purchases by month, product type, cost, purchase address, etc.

I start with cleaning the data which included:
•	Drop NaN values from DataFrame
•	Removing rows based on a condition
•	Change the type of columns (to_numeric, to_datetime, astype)

After cleaning up the data, I move to the data exploration section. 
I have tried to answer following questions using the data:
•	What was the best month for sales? How much was earned that month?
•	What city sold the most product?
•	What time should we display advertisements to maximize the likelihood of customer’s buying product?
•	What products are most often sold together?
•	What product sold the most? Why do you think it sold the most?

To answer these questions, the methods used include:
•	Concatenating multiple CSV files to create a new DataFrame (pd.concat)
•	Adding columns
•	Parsing cells as strings to make new columns (.str)
•	Using  .apply() method
•	Using groupby to perform aggregate analysis
•	Plotting bar charts and lines graphs to visualize our results
•	Labeling our graphs

