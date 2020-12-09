# hyperparameter-db-project-ds16
hyperparameter-db-project-ds19 created by GitHub Classroom
AI Skunkworks Project - Hyperparameters Database
Background
Hyperparameter is a parameter from a prior distribution, it captures the prior belief before data is observed.
In any machine learning algorithms, these parameters need to be initialized before training a model. Hyperparameters are important because
they directly control the behaviour of the training algorithm and have a significant impact on the performance of the model is being 
trained.
“A good choice of hyperparameters can really make an algorithm shine”.
Choosing good hyperparameters gives two benefits: - Efficiently search the space of possible hyperparameters and Easy to manage a large
set of experiments for hyperparameter tuning.

Objectives:
The goal of this skunkworks project is to find the best hyperparameters for the model and create a database by running
millions of hyperparameter values, over thousands of datasets
The objective is to create a database which has algorithms, tools and data that allows users to choose hyperparameters that
maximize the predictive power of their respective models.

Our main aim is to find proper hyperparameter with proper tuning for our dataset which would help the database team in modelling the database schema in an efficient way. We would create H2O models for this dataset for getting proper hyperparameters.To find the best, most important hyperparameters across different models across different runtimes is the maim moto of this project.
Using H2o - H2O is an open source, distributed in-memory machine learning platform with linear scalability. 
H2O supports the most widely used statistical & machine learning algorithms and also has an AutoML functionality.

Using H2o, the json files are generated for 300, 500, 1000, 1500 and 2000 seconds and on summing up all the hyperparameters of the 
particular algorithms into csv files we are trying to predict the best and the most important hyperparameters for both GLM and GBM 
algorithms respectively.

Problems to be addressed:
•	Choosing correct models and their hyperparameters is going to be tedious task.
•	Having H20 to run series of models in comparatively shorter time

Potential Pitfalls:
•	Usage of wrong metrics
•	Too few hyperparameters
•	Identifying the dataset problem accurately and the range of algorithms that can be applied to those models

Data Sources:
•	Kaggle

















