# Sales_Analysis
I used Python Pandas & Python Matplotlib to analyze and answer business questions about 12 months worth of sales data. The data contains hundreds of thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc.

<img width="821" alt="截屏2020-09-27 下午8 08 50" src="https://user-images.githubusercontent.com/68720881/94379289-49cf9980-00fd-11eb-9611-87d2ab446f36.png">

## Data Cleaning
* Drop NaN values from DataFrame
* Removing rows based on a condition
* Change the type of columns (to_numeric, to_datetime, astype)
<img width="628" alt="截屏2020-09-27 下午7 51 05" src="https://user-images.githubusercontent.com/68720881/94378930-155ade00-00fb-11eb-8c16-ad7f98f9f2b9.png">

## Data Exploration
* What was the best month for sales? How much was earned that month?
* What city sold the most product?
* What time should we display advertisemens to maximize the likelihood of customer’s buying product?
* What products are most often sold together?
* What product sold the most? Why do you think it sold the most?

To answer these questions I walked through many different pandas & matplotlib methods. They include:

1. Concatenating multiple csvs together to create a new DataFrame (pd.concat)
2. Adding columns
3. Parsing cells as strings to make new columns (.str)
4. Using the .apply() method
5. Using groupby to perform aggregate analysis
6. Plotting bar charts and lines graphs to visualize our results
7. Labeling our graphs


<img width="382" alt="截屏2020-09-27 下午7 54 27" src="https://user-images.githubusercontent.com/68720881/94378959-4509e600-00fb-11eb-8fc9-5ef91eb2d15d.png"><img width="393" alt="截屏2020-09-27 下午8 01 10" src="https://user-images.githubusercontent.com/68720881/94379094-32dc7780-00fc-11eb-9fd2-2e00e72592c0.png"><img width="416" alt="截屏2020-09-27 下午8 06 11" src="https://user-images.githubusercontent.com/68720881/94379214-ec3b4d00-00fc-11eb-890e-1acc4d37d4bb.png"><img width="453" alt="截屏2020-09-27 下午8 02 16" src="https://user-images.githubusercontent.com/68720881/94379126-5a334480-00fc-11eb-8296-7967da2f6548.png">
