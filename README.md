# python_final
The final project for python data analytics

For the final project, we will be finding a dataset to work with to demonstrate our ability to use Python in data analytics. First we’ll find a publicly available dataset from a reputable source. Then we’ll "Ingest the data” by importing it into Python. Then we’ll clean the data and document the cleaning steps in our code. Then we’ll manipulate the data to prepare it for analysis with operations like sorting, filtering, grouping, merging, or reshaping the data. Then we’ll visualize the data using Matplotlib or Seaborn to make appropriate charts. After all of that we’ll conduct our statistical analysis with descriptive statistics, correlation analysis, and/or distribution analysis. This README file will be used to document our project and code in addition to inline comments.

The dataset I chose is a collection of crocodiles observed in the wild over a period of about 20 years. Each line represents a single observation of a crocodile, and includes things like the observation date, weight, and length of the crocodile.

I used this dataset in a previous project using Excel, but was unable to use the observation dates due to a formatting issue with the CSV. So this project seeks to revisit the data with a focus on trends over time.

After completing the project I began to think that the observations might not be indicative of the true populations of crocodiles because they don't seem to follow the patterns I would expect to see when comparing endangered and non-endangered species counts. So while I can't say that this project successfully portrays trends in crocodile populations around the world, it was at least a good exercise in exploring data with Python.

This is the breakdown by conservation status (the graph that made me question if this data correlates to true population counts)
![](https://github.com/MattJorgensen95/python_final/blob/main/Conservation%20Status%20Counts.png?raw=true)

This is a regression model and scatter plot of the critically endangered species
![](https://github.com/MattJorgensen95/python_final/blob/main/Regression.png?raw=true)

This is the total counts of crocodiles each year
![](https://github.com/MattJorgensen95/python_final/blob/main/Total.png?raw=true)

This is a graph showing 5 year increments of critically endangered species' observations
![](https://github.com/MattJorgensen95/python_final/blob/main/FiveYear.png?raw=true)
