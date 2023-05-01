# Tech-Salary-Prediction

# The Project:
This project attempts to use machine learning algorithms to predict an induviduals salary based on variables such as their experience, their company, how long they have been working at the company and more. In this repo you will find linear ression, random forest regrssion, and deep learning machine learning models and the comparision of the models. 

# Data
-Type: CSV
-Input: 
    -Vairables: 'company', 'level', 'title', 'totalyearlycompensation', 'location',
       'yearsofexperience', 'yearsatcompany', 'tag', 'basesalary',
       'stockgrantvalue', 'bonus', 'gender', 'otherdetails', 'cityid', 'dmaid',
       'rowNumber', 'Masters_Degree', 'Bachelors_Degree', 'Doctorate_Degree',
       'Highschool', 'Some_College', 'Race_Asian', 'Race_White',
       'Race_Two_Or_More', 'Race_Black', 'Race_Hispanic', 'Race', 'Education'
       
    Columns: 62641 


# The Data Set
- The Data is collegected from Kaggle and is then preprocessed. The null values were removed and the data set was cleaned by removing any outlieres from each variable. Then data transformation was taken place, making sure the dataset had the proper columns, changing the variables into binarys. This file also contains some data modeling and a small attempt at a linear regression model. 

# Standard Scalar and Normalization of DataSets
- This notebook contains the original data and is encoded and normalized. Using the RandomForest Regressor, the model analyzed the scaled data and gave us an output of what vairables the dataset is most affected by. As supposed to handpicking variables I thought were important, I let the model pick

# Salary Prediction based on Linear Regression
- This file contains a salary prediction using linear regression and three different models of linear regression. The first one is of the dataset from 'The Data Set', next is the 'Standard Scalar and Normalization', and the third model is created using the pre trained data sets also made in that same file. 

# Deep Neural Network (DNN)
- This folder is the start of developing a DNN 
This website has the code I based this notebook off. 
- https://towardsdatascience.com/deep-neural-networks-for-regression-problems-81321897ca33

# Salary Prediction Random Forest Regressor
- This file contains a salary prediction using random forest regression 



