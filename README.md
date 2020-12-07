# Machine Learning Project 

In this project I´ve built different models based on different ML Algorithms to predict the price of diamonds based on data. 

## Data Cleaning

The first step before using any ML Algorithm is cleaning the dataset and adapting it to the algorithms we are going to use afterwards. This cleaning processes include handling missing data and turning categorical variables into numerical, since ML Algorithms do not perform well with this type of variables. 

In the data set provided, we did not have any missing values, so the cleaning was basically turning categorical variables into numerical using Ordinal encoding. Since we have to do this cleaning process before every model, I stored the code in a variable called clean_diamonds. 

I also built a variable called standard to standardrize the data for some ML algorithms that worsen there performance with different scales in the variables. 

## Models

The metric decided to check the performance of a model in this project is the Mean Squared Error. During the project I´ve tried different algorithms to find the model with the smallest Mean Squared Error. 

The different algorithms used are: 
    - KNN
    - Random Forest
    - Gradient Boosting 
    - XGBoost 
