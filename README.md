# DenguAI
Predicting the total number of Dengue cases in the cities San Juan and Iquitos based on the given dataset

## Description
Goal is to predict the total_cases label for each (city, year, weekofyear) in the test set. There are two cities, San Juan and Iquitos, with test data for each city spanning 5 and 3 years respectively. 

### Metric of measure - MAE

### Following is a summary of predictions done using different algorithms

* Linear Regression Model for SJ:  23.372312994769963
* Linear Regression Model for IQ:  6.796203990035329


* Ridge Regression Model for SJ:  23.558182161402772
* Ridge Regression Model for IQ:  6.796151741906554


* Lasso Regression Model for SJ:  23.362136041111135
* Lasso Regression Model for IQ:  6.786984405731608


* Random Forest Regressor Model for SJ:  23.778794282543068
* Random Forest Regressor Model for IQ:  6.534216646685393


* Decision Tree Regressor Model for SJ:  23.46479761859979
* Decision Tree Regressor Model for IQ:  6.350630816064368


* Gradient Boosting Regressor Model for SJ:  23.744933179041322
* Gradient Boosting Regressor Model for IQ:  6.744875532183025

##### The minium MAE that could be achieved the averaging the models is 25.5313
