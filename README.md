# Insurance-Charges-Prediction-using-Linear-Regression
This project demonstrates an end-to-end machine learning workflow to predict individual medical insurance charges based on demographic and lifestyle factors.          
Medical insurance charges can vary greatly based on age, BMI, smoking habits, and more. Predicting charges using regression models can help:                       

1.Insurance companies set premium rates                                                                                                                            

2.Individuals estimate future costs                                                                                                                                

3.Analysts identify key cost-driving factors                                                                                                                       

The data set used in this project is publicly availabel and can be downloaded from Kaggle.It contains the following features:
age(Age of the insured), sex(Gender:male or female), bmi(Body mass index), children(Number of dependents), smoker(Smoking status:yes/no), region(Region of residence), charges(medical charges which is the target in this case)                                                                                               

Exploratory Data Analysis:
EDA was conducted using:

1.Histograms for distributions

2.Boxplots to compare charges by groups (smoker, sex, region)

3.Pairplots to examine relationships

4.Correlation heatmap to quantify linear relationships

Key Insights:

1.Smokers have significantly higher charges

2.Age and BMI positively correlate with charges

3.Region and sex have minimal impact

Linear Regression model was selected as teh baseline model:

1. Preprocessing: Encoding categorical features (sex, smoker, region)

2. Splitting data: 80% training, 20% testing

3. Training with LinearRegression from scikit-learn

4. Evaluating performance

Evaluation: The model explains about 78% of the variation in medical charges. Most predictions are within $4,000-$5,000 of the actual value.   

Smoker status is by far the most influential factor.
