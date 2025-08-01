# Carsales-Prediction
Predicted car purchases using ML algorithms. Models used like linear regression,SVM,KNN and random forest. Also used some data cleaning process before these preprocessing prediction techiques


Project Summary: Car Purchase Prediction

I began by loading the car_purchasing.csv dataset into a pandas DataFrame and conducted initial exploratory analysis, including viewing the data structure, shape, and column details.Then moved into data visualization and correlation analysis, identifying strong positive relationships between features such as 'age', 'annual Salary', 'net worth', and 'car purchase amount'. Scatter plots and histograms were used to confirm and visualize these trends.

Next,  performed data preprocessing: converting the 'gender' column from numeric to categorical values, grouping ages into ranges, and analyzing salary and purchase trends by age and gender. After rounding and categorizing the 'age' feature, we visualized average annual salary and maximum car purchase amount for each age group.

In the machine learning phase, I have selected 'age', 'annual Salary', and 'net worth' as input features (X) and 'car purchase amount' as the target (y).Then split the dataset into training and testing sets, scaled the data using StandardScaler, and evaluated four regression models: Linear Regression, Random Forest, Support Vector Regressor (SVR), and K-Nearest Neighbors (KNN). A custom evaluation function calculated MAE and RMSE for each model.

The final comparison revealed that the Linear Regression model on scaled data performed best, achieving the lowest error metrics among all models tested. Overall, the project successfully explored and modeled the dataset to predict car purchase amounts, highlighting the key financial factors influencing customer purchasing behavior.
