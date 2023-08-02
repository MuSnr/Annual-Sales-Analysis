# Annual-Sales-Analysis
This repository provides annual sales analysis with Python pandas. I use Python Pandas and Matplotlib to analyze and answer critical business questions  about 12 months' worth of data sales. The data contains hundreds of thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc.

I begin by cleaning the data. Tasks during this section include:
- Drop NaN values from DataFrame
- Removing rows based on a condition
- Change the type of columns (to_numeric, to_datetime, type)

Once I have cleaned up our data a bit, I move the data exploration section. In this section, I explore 5 high-level business questions related to our data:
- Which was the best month for sales? How much was earned that month?
- Which city sold the most product?
- What time should we display advertisements to maximize the likelihood of customers buying products?
- Which products are most often sold together?
- What product sold the most? Why do you think it sold the most?

To answer these questions I'll go through many different pandas & matplotlib methods. They include:
- Concatenating multiple csvs together to create a new DataFrame (pd.concat)
- Adding columns
- Parsing cells as strings to make new columns (.str)
- Using the .apply() method
- Using groupby to perform aggregate analysis
- Plotting bar charts and lines graphs to visualize our results
- Labeling our graphs
