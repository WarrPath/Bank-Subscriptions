# Bank-Subscriptions
ML models used to predict bank customers subscribing to long-term deposit accounts based on varying demographic information.

# About Dataset
A Portuguese Bank found that many of their customers are not investing in long term deposit accounts. The bank would like to identify customers that have a higher chance of subscribing for a long term deposit account and focus their marketing efforts on such customers.
You can find more information and download the dataset here: https://archive.ics.uci.edu/dataset/222/bank+marketing

# Data Analysis
Check for null/missing or duplicate values.
View data types and counts of the target variable.

View statistical information on the numerical data:
	Avg Age = 41
	Ave Deposit Amount = $1362.27
	Min Deposit Amount = -$8019
	Max Deposit Amount = $102127

Blue Collar, Management, and Technicians contacted most.
Married people contacted most.
Secondary/high school contacted most.
Most contact in the month of May and summer months.
Retired, married, and college graduates have the highest average balance.
Age 84 has the highest average balance - likely from an outlier.
	
# Data Preprocessing
Encode/transform categorical data into numeric labels so the model can read and use the data.

# Machine Learning
Determine which machine learning model best predicts whether a customer will subscribe to a long term deposit account or not.
