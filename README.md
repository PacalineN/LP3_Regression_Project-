# A Time Series Forecasting Model to Enhance Store Sales Prediction for Favorita 
![image](https://th.bing.com/th/id/OIP.EZeP9vSGOADD1MSdiDctcgHaE7?rs=1&pid=ImgDetMain)

### Project Description
The objective of this project is to evaluate and project a store's sales using time series data from Corporation Favorita, a large grocery retailer with its headquarters located in Ecuador.
The goal is to build a model that can accurately predict future sales utilizing the thousands of products that are sold at various Favorita locations. This model will help the store's management establish strategies for inventory and sales.
As part of this study, we will use historical analysis to construct models, develop scientific hypotheses based on time-stamped historical data, and use those models to guide future strategic decision-making and observations. We would like to help Favorita Corporation's management obtain some insights from their data in order to improve operations and eventually sales.
### Methodology

IBM claims that the Cross-Industry Standard Process for Data Mining, or CRISP-DM, is a tried-and-true method for directing your data mining endeavors.
-  As a methodology, it provides explanations of the standard project stages, the tasks associated with each phase, and the connections between these tasks.  
  ## CRISP-DM serves as a process model that summarizes the data mining life cycle.
  The CRISP-DMThe six stages of the data mining lifecycle are as follows:
1. Business Understanding
2. Data Understanding
3. Data Preparation
4. Modeling
5. Evaluation
6. Deployment

## Business Understanding
By gaining deeper insight into long-term sales trends, this project aims to boost sales. Recognize past incidents, their impact on sales, corrective actions that can be taken, and, if required, the next course of action. In an attempt to provide some predictions, this study looks at a number of regression techniques.

Hypothesis:The store's sales are influenced by a number of variables, including the day of the week, the season, special offers, and other outside variables. We are able to forecast the store's future sales with accuracy by examining these variables and developing a time series forecasting model.
**Null Hypothesis (H0)**:The promotional activities ,oil prices , and holidays do not have a significant impact on store sales for Corporation Favorita.
**Alternative Hypothesis (H1)** : The promotional activities The promotional activities ,oil prices , and holidays  have a significant impact on store sales for Corporation Favorita.
## **Analytical Questions**
1. Is the train dataset complete (has all the required dates)?
2. Which dates have the lowest and highest sales for each year?
3. Did the earthquake impact sales?
4. Are certain groups of stores selling more products? (Cluster, city, state, type)
5. Are sales affected by promotions, oil prices and holidays?
6. What analysis can we get from the date and its extractable features?
7. What is the difference between RMSLE, RMSE, MSE (or why is the MAE greater than all of them?)
## The data set includes information about : 
* The training data, comprising time series of features store_nbr, family, and onpromotion as well as the target sales.
* store_nbr identifies the store at which the products are sold.
* family identifies the type of product sold.
* sales gives the total sales for a product family at a particular store at a given date. Fractional values are possible since products can be * * sold in fractional units (1.5 kg of cheese, for instance, as opposed to 1 bag of chips).
* onpromotion gives the total number of items in a product family that were being promoted at a store at a given date.
* the column names of oil dataset t includes information about the daily price of oil .
* the column names of holidays events data Index(['date', 'type', 'locale', 'locale_name', 'description', 'transferred'], dtype='object')
* the column names of stores data Index(['store_nbr', 'city', 'state', 'type', 'cluster'], dtype='object')
* the column names of sample submission  data Index(['store_nbr', 'city', 'state', 'type', 'cluster'], dtype='object')
* the column names of test data Index(['id', 'date', 'store_nbr', 'family', 'onpromotion'], dtype='object')
* the column names of train data Index(['id', 'date', 'store_nbr', 'family', 'sales', 'onpromotion'], dtype='object')
* the column names of stores data Index(['date', 'store_nbr', 'transactions'], dtype='object')

