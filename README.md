# Outlier_Removal
Part I : Outlier Removal Techniques<b>
1) Use Fish.csv to fit a basic Linear Regression Fit to predict the weight of the fish using remaining attributes.<br>
2) Use the Fish_Missing.csv dataset<br>
A.Perform basic EDA<br>
B.Identify columns with single value, if any<br>
C.Identify duplicate tuples and remove them, if any<br>
D.Do you have null values? If Yes :<br>
a)Strategy 1: using central tendencies of data for imputation: Use Mean, Median strategies to create different datasets (Note that you may use the entire dataset or species level imputation)Use describeto note the changes in the dataset attributes.Impute the label missing values as well using Mean/Median (unless you choose to drop the rows)<br>
b)Strategy 2: using KNN: Use KNNImputerfrom sklearn, to impute the missing values<br> 
•Perform Linear regression fit for weight prediction using the modified datasets. <br>
Compare and comment on the results. <br>
Part II: Demonstrate Outliers on Plots<b><br>
•Use the modified Fish_Modified.csv dataset.<br>
•Combine the three Length attributes into a single attribute<br>
•Visualize the dataset scatter by species using Matplotlib/Seaborn/Plotly<br>
•Identify outliers using various techniques<br>
•1.5 IQR for specific attribute, full dataset<br>
•(2.5 * std. deviation) for specific attribute, full dataset<br>
•1.5 IQR for specific attribute, species wise<br>
•(2.5 * std. deviation) for specific attribute, species wise<br>
•For each case, plot the data scatter with outliers <br>
•Comment on the observations made<br>
