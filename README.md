# Clunker-Car-Spotting

Executive Summary

Problem:
In the used car market, there is much uncertainty that can contribute to a bad buying experience for the customers. My work in the project is to look at the used car purchasing process and identify used cars that are likely to be bad purchases. Identifying the crappy cars before they end up on the website for sale can prevent the customers from purchasing bad cars in order to improve the customer experience. 

In the project, I built two models, Random Forest and XGboost, to find out the variables that can identify the crappy car in the market. 

Model Performance Summary & Interpretation:
1.	Comparing the random forest and xgboost in the analysis, the xgboost shows the highest area under the curve, roughly 77% higher than the random forest's 76%.

2.	The xgboost has slightly higher accuracy than the random forest. 

3.	The xgboost has a lower misclassification rate than random forest, indicating a better fit of the data. In addition, a lower mean of log loss shows a little error rate.

4.	Looking at the precision rate, how many are crappy cars in all the cars labeled as a bad buy. The xgboost has a better precision rate to label the right crappy cars.

5.	Looking at the recall rate, in all real crappy cars, how many have been identified. The xgboost has a higher recall rate to identify the most real bad buy of the crappy car.
