# Medical_Insurance_Cost_Prediction

Project Overview : The objective of this project is to develop a predictive model that can accurately estimate the medical insurance costs for individuals based on various factors. This will help insurance companies in pricing their policies more accurately and effectively.

Data Sources: Data was collected from the Kaggle.It is containing information about individuals, including features such as age, gender, BMI, smoking status, region, and number of children. The target variable is the medical insurance cost incurred by each individual.

Libraries : Pandas, Numpy, SK-learn (ML Models : Logistic regression, SVC, Decision tree classifier, GaussianNB)

EDA Observations:
>>There are no null vales present in dataset.
>>There are no class imbalancing Gender, both male and female have equal counts.
>>BMI feature is following normal distribution, where normal BMI ranging between 18.5 to 24.9.
>>Smoker feature contains Non-smoker=1064 people and Smoker=274 people.
>>Dataset containing residential area in the US, northeast, southeast, southwest, northwest. Al have same no of people.

Data Modeling: We have built different Predictive models like Linear regression(r2_score = 0.0.74), Support Vector regressor(r2_score = 0.21), DecisionTreeRegressor using Gridsearch-CV(r2_score = 0.83), RandomForest Regressor using Gridsearch-CV(r2_score = 0.86).Both model DecisionTreeRegressor using and RandomForest Regressor have almost same accuracy.

Model Selection : We have two model which are performing very well. we can choose based on factors like Accuracy & Interpretability.

>>Accuracy: If our main goal is to maximize accuracy and you have the computational resources to train and use a Random Forest model, then the Random Forest model might be the better choice since it generally provides better accuracy than a single Decision Tree.
>>Interpretability: Decision Trees are easier to interpret and visualize compared to Random Forests, which are essentially an ensemble of many Decision Trees. If interpretability is important for your application, we should go for the Decision Tree model.

Expected Outcome:
The project aims to develop a model that can accurately predict medical insurance costs for individuals, helping insurance companies in pricing their policies more competitively while ensuring fair and accurate estimates for policyholders.

