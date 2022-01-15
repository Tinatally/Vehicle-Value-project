# Vehicle-Value-project
About the project: Rusty Bargain used car sales service is developing an app to attract new customers. In that app, you can quickly find out the market value of your car. You have access to historical data: technical specifications, trim versions, and prices. You need to build the model to determine the value. 

Rusty Bargain is interested in:
- the quality of the prediction;
- the speed of the prediction;
- the time required for training

1. Train different models with various hyperparameters and to compare gradient boosting methods with random forest, decision tree, and linear regression.
2. Analyze the speed and quality of the models.
3. Use the RMSE metric to evaluate the models.

Summary Results: 
|| model | RMSE |Time |CPU Total time|
|--|---|---|---|---|
|1|Linear Regression | 3694.39 |0.010|269ms|
|2|Decision Tree | 2387.10 |0.014|10.8s|
|3|Random Forest | 2328.84| 0.007|11min 12s|
|4|XGBoost| 1725.45 |0.006 |min 27s|
|5|CatBoost| 2189.89| 0.006 |5min 14s|
|6|Light GBM | 1740.53 | 0.007 |45.1 s|

Bases on our interest, the model that performed best was LightGBM which took 45.1s of CPU time to train with Linear regression preforming poorly. 
