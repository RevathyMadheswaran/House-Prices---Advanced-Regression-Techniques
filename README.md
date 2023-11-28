# House-Prices---Advanced-Regression-Techniques
Its a Kaggle Project. We have to predict the SalePrice of houses using regression techniques.
It has "Train Data" with label and "Test Data" without label. And also with 80 independent variables.
We have to train our model using train data and predict the saleprice of test data.
I did all the Data pre-processing steps such as missing value treatment,outlier treatment and then feature engineering techniques.
Analyzed the data using Exploratory Data Analysis.
Then selected the important features using feature selection techniques to reduce the complexity of data and to improve the model performance.
Splitted the data into train and test for training and validating the model.
I used top 8 ML algorithms for training and validating like Linear Regression, Lasso, Random Forest, Stochastic Gradient Descent, Gradient Boosting, AdaBoost, XGBoost and SVM.
Random Forest, Gradient Boosting and XGBoost gives almost same accuracy.
Then i did Hyperparameter Tuning using GridSearch CV to improve the accuracy, but there is no improvement.
Finally, i predict the SalePrice of test data using xgboost and save the results in csv file.
