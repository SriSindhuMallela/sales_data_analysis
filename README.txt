Background Information:
 
Python Pandas & Python Matplotlib to analyse and answer business questions about 12 months worth of sales data. The data contains hundreds of thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc.

We commence with a process of discovery to gain a deeper understanding of our data. Tasks within this phase encompass:
Shape of Data
Dtypes of Data
NaN values
Data discovery using describe()


Then cleaning our data. Tasks during this section include:
Drop NaN values from DataFrame
Removing rows based on a condition
Change the type of columns (to_numeric, to_datetime, astype)

Once we have cleaned up our data, we move the data exploration section. In this section we explore 4 high level business questions related to our data:
What was the best month for sales? How much was earned that month?
What city sold the most?
What time should we display advertisements to maximise the likelihood of customer’s buying a product?
What products are most often sold together?


To answer these questions we walk through many different pandas & matplotlib methods. They include:
Concatenating multiple csvs together to create a new DataFrame (pd.concat)
Adding columns
Parsing cells as strings to make new columns (.str)
Using the .apply() method
Using groupby to perform aggregate analysis
Plotting bar charts to visualise our results



