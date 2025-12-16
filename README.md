# US-Sales-Data-Analysis

1. In this project, I am analyzing a sales dataset of electronic items in the US market.
2. Data is picked from Kaggle and includes 186k rows and 6 columns
3. Important libraries used are Pandas for analysis and matplotlib for visualization.


We start by merging different data files into one and then cleaning our data. Tasks during this section include:
- Concatenating multiple CSVs together to create a new DataFrame named all_data_copy.csv (using pd.concat)
- Drop NaN values from DataFrame
- Removing rows based on a condition
- Change the type of columns (to_numeric, to_datetime, astype)

Once we have cleaned up our data a bit, we move to the data exploration section. In this section, we explore 4 high-level business questions related to our data:
- What was the best month for sales? How much was earned that month?
- What city sold the most product?
- What time should we display advertisements to maximize the likelihood of customers buying the product?
- What product sold the most? Why do you think it sold the most?

To answer these questions, we walk through many different pandas & matplotlib methods. They include:
- Adding different columns as per the requirements
- Parsing cells as strings to make new columns (.str)
- Using the .apply() method
- Taking up each question one by one and analysing data with pandas and plotting graphs to visualize it.
- Using groupby to perform aggregate analysis
- Plotting bar charts and line graphs to visualize our results
- Printing the insight at the end of the notebook gathered by analyzing the data.
