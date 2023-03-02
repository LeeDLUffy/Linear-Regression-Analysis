# Linear-Regression-Analysis
To perform EDA on the insurance dataset, we can start by:

1.Import the dataset and loading it into a pandas dataframe.

2.Understanding the variables:

age: age of policyholder
sex: gender of policyholder (male/female)
bmi: Body Mass Index
children: number of children/dependents covered by insurance policy
smoker: whether the policyholder smokes or not (yes/no)
region: the geographical region in which the policyholder resides
charges: medical cost charged by the insurance company


3.Data Summary:

Get the number of observations, columns and data types
Get the summary statistics of each column


4.Data Visualization:

Plot histograms and boxplots of each column to understand the distribution of each variable
Use scatter plots and violin plots to understand the relationship between two variables
Use bar plots, count plots, and pie charts to visualize categorical variables


5.Outlier detection:

Use boxplots and scatter plots to detect and analyze outliers


6.Handle Missing Values:

Check the presence of missing values in the dataset
If any, fill the missing values with the mean or median, depending on the distribution of the data.


By following these steps, we will get a good understanding of the data and be able to draw meaningful insights from the insurance dataset.


To evaluate a linear regression model, you can use the Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and Mean Squared Error (MSE) metrics. These metrics provide an indication of how well the model fits the data, and they quantify the difference between the predicted values and the actual values in the target variable.


In this code the following steps were taken to do the linear regression analysis:

-I first split the data into target (y) and predictors (X)
-Converted categorical variables to one-hot encoded variables
-Fitted a linear regression model
-Made predictions on the test data
-Finally, i calculated evaluation metrics to obtain the MAE,RMSE and MSE
