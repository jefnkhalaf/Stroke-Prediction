# Stroke Prediction
Jefn Alshammari & Abdulaziz Almass
## Abstract
This project aimed to predict stroke for people by analyzing a dataset found in Kaggle using different machine learning models(MLs) to help the medical staff to recongize those people with high risk of getting stroke in the future. The used dataset was trained and get X% accuracy as the highest value of the different used models.  

<!-- The data has been explored, cleaned and One-Hot-Encoding for some of the features such as "gender" ...etc.  -->

## Design

This project is one of the T5 Data Science BootCamp requirements. Data provided by Kaggle has been used in this project. The attribute "Stroke" is the label or target to be predicted in this project. This target is binary having either 1 or 0 as a value. The value of "1" means predicted with stroke and "0" means predicted without a stroke. This classifcation prediction will be deployed using various machine learning models and a comparison of these models is done to measure of performance for each model to find the one that fits with the selected dataset. All of the following models have been used and tested: Logistic Regression, K-Nearest Neighbors (KNN), Decision Tree,  Support-Vector Machines (SVM),Random Forest and XGBoost.  

## Data 

The dataset is available in ```.csv``` format. It consists of 5110 observations/data points with 12 attributes or features. From exploratory data analysis, the age feature has an important role in stroke prediction which most models deployed confirmed afterwards. Other features were not definately if they are important due to the imbalanced dataset that has been treated with Synthetic Minority Oversampling Technique (SMOTE). Another important feature of this project is the label of the stroke whether the person is predicted with a stroke or not.


***Models***

Logistic Regression, K-Nearest Neighbors (KNN), Decision Tree, Support-Vector Machines (SVM),Random Forest and XGBoost are trained to predict stroke. The Random Forest has the highiest accuracy.

***Models Evaluation and Selection***

The following metrics summarize the results of all ML models used in this project : 

|           Model Name           |  Accuracy  |    F1    |   Precision   |    Recall   |
| ------------------------------ | ---------- | -------- | ------------- | ----------- |
| Logistic without Scaling       |            |          |               |             |
| Logistic with Scaling          |            |          |               |             |
| Logistic with Scaling & Tuning |            |          |               |             |
| KNN with Scaling               |            |          |               |             |
| Decision Tree with Scaling     |            |          |               |             |
| SVM without Scaling            |            |          |               |             |
| SVM with Scaling               |            |          |               |             |
| Random Forest with Scaling     |            |          |               |             |
| XGBoost with Scaling           |            |          |               |             |
| XGBoost without Scaling        |            |          |               |             |

## Tools

- Pandas library for data frames
- Numpy for mathematical operations
- Matplotlib and Seaborn for plots
- SKlearn for modeling
- One-Hot-Encoding for categorical labeling

## Communication

The presentation show is provided [here](https://github.com/jefnkhalaf/Stroke-Prediction/edit/main/Final_Phase/Presentation.pdf), besides details are provided at the [readme](https://github.com/jefnkhalaf/Stroke-Prediction/blob/main/README.md) of the project.
for any enquiries, you can contact us via [Email]( mailto:jefnkhalaf@gmail.com)
