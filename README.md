# Retail-Sales-Prediction
# Problem Statement-
Rossmann operates over 3,000 drug stores in 7 European countries. Currently, Rossmann store managers are tasked with predicting their daily sales for up to six weeks in advance. Store sales are influenced by many factors, including promotions, competition, school and state holidays, seasonality, and locality. With thousands of individual managers predicting sales based on their unique circumstances, the accuracy of results can be quite varied. You are provided with historical sales data for 1,115 Rossmann stores. The task is to forecast the "Sales" column for the test set. Note that some stores in the dataset were temporarily closed for refurbishment.
# Business Problem
The interest in a product continues to change occasionally. No business can work on its monetary growth without assessing client interest and future demand of items precisely. Sales forecasting refers to the process of estimating demand for or sales of a particular product over a specific period of time. This project involves solving a real-world business problem of sales forecasting and building up a machine learning model for the same.

Our goal here is to forecast the sales for six weeks for each store and find out the factors influencing it and recommend ways in order to improve the numbers.

# Approach
* Data Collection and Preprocessing - Importing important libraries and modules -Data loading- Data Cleaning - Missing Data Handling - Merging the Datasets
* Exploratory Data Analysis - Hypotheses - Categorical Features - Continuous Features - EDA Conclusion and Validating Hypotheses
* Feature Selection and Outlier Detection - Feature Engineering - Outlier Detection and Treatment,multicolinearity and one hot coding
* Model implimentation -Tranforming data, Train Test Split - linear regression-lasso-elastic net - Decision Tree -Decisin tree hyperparameter tunning- Random Forest Model - Random Forest Hyperparameter Tuning - Random Forest Feature Importance
* Conclusion and Recommendations
# Challenges
* Handling and understanding large amount of data.(1017209 number of records and 18 number of fields )

* Columns with improper data type and wrong values.

* Combining, creating and removing columns.

* Records containing more than 50% of nan values and replacing it with substitutes.

* Removing and replacing outliers from dependent and independent variables. Reducing skewness from the variables.

* Feature selections for ML Model.

* Converting columns with categorical variables to integer type and scaling numerical variables for regression models.

* Performing and choosing right kind of model.
● The major challenge would be the
computational time and RAM needed to
work upon such a dataset in a cloud
environment.
# Conclusion

* Businesses use sales forecasts to determine what revenue they will be generating in a particular timespan to empower themselves with powerful and strategic business plans. Important decisions such as budgets, hiring, incentives, goals, acquisitions and various other growth plans are affected by the revenue the company is going to make in the coming months and for these plans to be as effective as they are planned to be it is important for these forecasts to also be as good.

* The work here forecasts the sales of the various Rossmann stores across Europe for the recent six weeks and compares the results from the models developed with the actual sales values.

* Some important conclusions drawn from the analysis are as follows:

* There were more sales on Monday, probably because shops generally remain closed on Sundays which had the lowest sales in a week. This validates the hypothesis about this feature.

* The positive effect of promotion on Customers and Sales is observable. Most stores have competition distance within the range of 0 to 10 kms and had more sales than stores far away probably indicating competition in busy locations vs remote locations.

* Store type B though being few in number had the highest sales average. The reasons include all three kinds of assortments specially assortment level b which is only available at type b stores and being open on sundays as well.

* Random Forest hyperparameter Tuning Model gave the best results(with R2:0.970376) and only slightly improvement was seen from the basic random forest model(with R2:0.970366) which indicates that all the trends and patterns that could be captured by these models without overfitting were done and maximum level of performance achievable by the model was achieved. we finally came to the conclusion that Random Forest Regression Tuned model have higher performance (with R2 :0.970376) among the other models, as Random Forest Regression can handle large datasets efficiently and it's algorithm provides a higher level of accuracy in predicting outcomes over any other regression algorithm
