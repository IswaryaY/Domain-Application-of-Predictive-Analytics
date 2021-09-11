# PREDICTION OF SILICA IN IRON ORE USING MACHINE LEARNING TECHNIQUE
Mining seems to be a sector in which expanding performance and effectiveness has been essential for revenue growth, because tiny changes in returns, pace, as well as performance could have a substantial influence.The overall purpose of this research would be to use data to forecast what percentage of adulteration is present with in ore concentrate. Since this pollutant has always been monitored once an hour, estimating that how so much silica would be in the ore concentration could really help benefit the technicians by providing pre-stage data to do measures. It is a necessary consequence, the technicians will be likely to access appropriate measure in earlier stage (minimize imperfection, once absolutely required) thereby contributing to sustainable development for surroundings. The machine learning models helps as predictive analytics technique to forecast the quality of mining by predicting the percentage of silica present in the ore. In this research, Random forest Regressor is being implemented to experiment the prediction and the results are assessed by the metrics such as precision, recall, Root mean square, and other metrics with an R square value of 0.90(90%).

![N|Solid](https://www.pyramidanalytics.com/images/default-source/blog/pa-1.png?sfvrsn=1527f5c9_3)


## RESEARCH QUESTION
How effectively can the % of impurity of each ore be predicted to improve the Return of Investment (ROI) in mining industry?

## HYPOTHESIS
The impact of poor quality of the iron ore will not result in the reduction of return of investment (ROI)

## DATA COLLECTION

The Quality mining Prediction Dataset is collected from a mining industry, which is available as a CSV file form in Kaggle website. This is available for public access without any restrictions. This data is the process held in the period from March to September in the year of 2017. The dataset comprises of numerical variables, which is about 24 columns in total. The total rows of the data are about 736282. 


## MISSING VALUES
The missing values does not help to obtain the prediction at good level. The missing values in the attributes can be filled in two ways- one is by using mean or mode values and the other one is deleting the column which has missing values. In this dataset, there is no missing values present. The date column has ignored, because it has no dependence on the dependent Variable.

## MULTICOLLINEARITY
The correlation is the statistical mutual relationship between two variables. It will be between +1 to -1. The multicollinearity is the problem that if two independent variables have correlation with one another.

## FEATURE IMPORTANCE
The major concern involved in selecting the attributes, because the unnecessary attributes will bias the results to predict. The feature importance is the method to select the attributes which is indeed and appropriate to predict the dependent variable. It is calculated by getting scores for all the columns and the columns with high score will be selected to proceed with building the models. Because those columns will have higher effect on the building model.


## TECHNIQUE APPLIED
The machine learning has two types of problems such as classification and regression. The classification is the algorithm in which the dependent variable will have two or more categories, whereas regression is the problem where the dependent variable will be numerical values. This is the study used to predict the quality of ore by predicting the amount of silicae percentage.

Business forecasting frequently employs random forest algorithms to produce machine learning predictions and decision making. The random forest employs numerous decision trees to conduct a more comprehensive examination for the aggregated outcome of a single data collection process. Because of its simplicity and excellent accuracy, it is among the most used algorithms for regression issues such as forecasting continuous outcomes.

Evaluation metrics are the best way to evaluate the models. The regression problems are assessed by the evaluation metrics such as R square value, Root Mean Square Error (RMSE), Mean Absolute Error (MAE) and Mean Square Error (MSE).

![N|Solid](https://github.com/IswaryaYogeashwaran/Domain-Application-of-Predictive-Analytics/blob/main/DAPPicture1.png?raw=true)
