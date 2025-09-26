Tutorial for wrangling and analyzing data

Intro: 
Have you ever wondered if you can predict the stock market? If you can predict the future, even? Of course, nobody knows for sure, and this tutorial is NOT meant for someone to perfectly predict when the stock market will increase, or decrease. However, by learning how to properly wrangle and analyze data, somebody can make an investment decision with a better understanding of these things. This tutorial is meant to teach people to properly wrnagle and orgaznie data in a way that they can glean information from it, allowing them to make educated decisions.

Step 1:
Choose your dataset. This can be a dataset of anything you're interested in learning more about. For this tutorial, we will be working with this dataset of stock market prices by day and month, and analyzing its seasonality. 



Read the dataset into your code with this:

import pandas as pd
df = pd.read_csv(file_path)

Great! Now that you've got it read in, you can start playing with it.

print(df.head()) allows you to see the first few rows of the dataset.

Step 2:
Wrnagle and clean the data. The dataset will inevitably have certtian things that you don't care about, or that you don't want to sue. You will have to remove certain rows and columns from the data, as well as certain parts that might have N/A or empty values in them. You will also have to perform some transformations. For this dataset, we will have to figure out what the days of the week are for each date in the dataset
Step 3: 
Perform EDA (Exploratory Data Analysis). Once you have your dataset, you want to visualize it. There are lots of different ways we can visualize it, so think about what way would make the most sense. Do you want a bar chart? Scatterplot? 
For this example, we will use a bar chart becuase it makes sense to use one to compare the stock market prices on each day of the week over a period of time. We can see what the average stock closing price is over a year's worth of Sundays, Mondays, etc.

Step 4:
What does it look like? Analyze what trends may be interesting or significant about your graphic, and data. For the purpose of our research, we will perform an ANOVA test to test each day of the week against every other day, seeing if there is a significant difference between one or more certain days, and the rest of the days of the week over the past year.

Step 5:

S&P Dow Jones Indices LLC, Dow Jones Industrial Average [DJIA], retrieved from FRED, Federal Reserve Bank of St. Louis; https://fred.stlouisfed.org/series/DJIA, September 25, 2025.

