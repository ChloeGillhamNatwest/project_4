# Udacity_project_4

This project is taken from the kaggle competition asking players to use regression techniques to predict house prices in Ames, Iowa. 

https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques

This project explored the data to understand which features can be used in a predictive model, then it prepared the data, and tried three different regression techniques to model the sales price:

• Linear regression

• Random Forests

• Gradient boosted trees. 

#Data
The data provided for the competition consists of train and test datasets, however as the test data is used for submitting to the comptetition it does not contain and price information, it is not possible to evaluate model performance on it. As a result I only focused on the train dataset provided for the purposes of this exercise, and ignoring the test dataset.
This data can be found at the above kaggle link. I have not included it in this repo for size reasons. 
There is also a helpful data dictionary in the repository which gave some background information about features 

# Files:
Python script which also contains descriptions of each step, and a conclusion

# Libraries required 

•	Pandas

• Numpy

•	Math

•	Seaborn

•	Matplotlib

•	Sklearn


# Results
Using a gradient boosted model it was possible to predict the sales prices with 90.31% accuracy. This was the best model fitted out of the three discussed.

A full write up is in this blog post:
https://medium.com/@chloe.gillham/predicting-house-pries-in-ames-iowa-da6698f0bcea
