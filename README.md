# Wine Quality Prediction

**Overview**

The goal of this project is to predict wine quality scores (3–9) for wines based on its physicochemical properties.The dataset contains 6,497 wine samples with 11 physicochemical features and one target variable (quality). The data was split into training and test sets, with 1,293 samples used for testing.A Random Forest classifier was used to model the relationship between physicochemical properties and wine quality. In this project, we treat wine quality prediction as a multi-class classification problem, where each wine is assigned a discrete quality score. The model is evaluated on its ability to correctly classify wines into these quality scores.

**Data Set Information**

The dataset was downloaded from the UCI Machine Learning Repository.Kaggle source: https://www.kaggle.com/datasets/rajyellow46/wine-quality/data

**Data Description**

Attribute Information:

- fixed acidity: 4.0-16.0
- volatile acidity: 0.1-1.6
- citric acid:0.0-1.0 
- residual sugar:0.5-16.0
- chlorides: 0.01-0.65
- free sulfur dioxide: 1-300
- total sulfur dioxide: 6-450
- density:0.987-1.040
- pH: 1-14
- sulphates: 0.2-2.0
- alcohol: 8.0- 15.0
- quality (score between 0 and 10)
