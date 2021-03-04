# Bangalore-Home-Prices-Estimation
This model shows prices of houses in different areas in Bangalore and the model is trained using Logistic regression with the accuracy of 87%.

This data science project series walks through step by step process of how to build a real estate price prediction model. We will first build a model using sklearn and linear regression using banglore home prices dataset from kaggle.com. Second step would be to write a python flask server that uses the saved model to serve http requests. Third component is the  built in html, css and javascript that allows user to enter home square ft area, bedrooms etc and it will call python flask server to retrieve the predicted price. During model building we will cover almost all data science concepts such as data load and cleaning, outlier detection and removal, feature engineering, dimensionality reduction, gridsearchcv for hyperparameter tunning, k fold cross validation etc.

<img src='artifacts/BHP_website.png'>

## Requirements
* Python
* Numpy and Pandas for data cleaning
* Matplotlib for data visualization
* Sklearn for model building
* Jupyter notebook, visual studio code and pycharm as IDE
* Python flask for http server
* HTML/CSS/Javascript for UI
