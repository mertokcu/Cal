# Linear-Prediction-Quality-Analysis-and-T-Test-on-California-Housing-Prices-Data-Set

Part 0: Preparations
Load the data set you chose and explore its theme, columns and rows.
Calculate the mean, median and standard variation for each (at least ) numerical column.

Part 1: Linear Regression

Choose 3 columns that appear to make sense to compute the missing target value
Compute correlations between all agreed columns and the target column.
Take the column of the 3 with the highest correlation to your target and build a linear
model with it, using the smf.ols()-function.

Make a scatter plot of explanatory and target column and plot the line of your linear model.
Check if you model is reasonable:

• Look at the R²-value
• Plot the residuals against the explanatory variable. Any pattern?
• Plot the histogram of residuals. Do they follow a normal distribution?

Now include the other two columns in a multivariate linear regression. Make a new model,
explaining the target by column1 + column2 + column3.

• Did the R² get better? How much?
• Are the residuals still behaving nicely? Make the two plots again.

Part 2: t-test
Choose 2 groups of at least 100 data points where you would like to explore the difference
on two different columns.
Subselect your dataframe into those two distinct groups.
Calculate the mean, median and standard deviation for each numerical column again for
each group separated.
From the new datasets, choose the first column and do a two sample-t-test to compare
the means.
Are they significantly different (by a confidence interval of 95%)?
Do the same for the other column.
