# Sales_Analysis
I used Python Pandas & Python Matplotlib to analyze and answer business questions about 12 months worth of sales data. The data contains hundreds of thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc.

### Data Cleaning
* Drop NaN values from DataFrame
* Removing rows based on a condition
* Change the type of columns (to_numeric, to_datetime, astype)

### Data Exploration
* What was the best month for sales? How much was earned that month?
* What city sold the most product?
* What time should we display advertisemens to maximize the likelihood of customer’s buying product?
* What products are most often sold together?
* What product sold the most? Why do you think it sold the most?

To answer these questions I walked through many different pandas & matplotlib methods. They include:

1. Concatenating multiple csvs together to create a new DataFrame (pd.concat)
2. Adding columns
Parsing cells as strings to make new columns (.str)
Using the .apply() method
Using groupby to perform aggregate analysis
Plotting bar charts and lines graphs to visualize our results
Labeling our graphs
