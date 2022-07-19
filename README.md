# CTC_prediction_using_Linear_Regression

CTC/Salary prediction is required  now-a-days for a company to offer above average or average salaries to employeer, fresher or HR.

Here there are 7 features to predict the CTC/Salary namely college tier, role, city, previous CTC, previous job changes, graduation marks and Experience.
As the dataset has categorical values in it so, it is converted into numerical values using dummies function of pandas module.
Preprocessing is then applied to check missing values and to normalize the numerical dataframe which is benificial for Linear Regression model.
Normalize dataframe is then trained by applying Linear Regression on it.
Evaluation of model is carried out using MSE(Mean squared Error) after normalizing the test data.

![image](https://user-images.githubusercontent.com/92297330/179768192-b6721c15-5757-49e5-abcc-28e793966840.png)


Image of MSE calculation
