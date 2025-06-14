### Heart Attack Analysis And Prediction

# Heart Attack Analysis And Prediction
GitHub Repository for work done as part of captstone project Professional Certificate in Machine Learning and Artificial Intelligence - Oct 2024

# Heart Attack Analysis And Prediction

**Contents**


 * [Introduction](#Introduction)
 * [How to use the files in this repository?](#how-to-use-the-files-in-this-repository)
 * [Conclusion](#Conclusion)


 
## Introduction
What is Heart Attack?

![Heart_attack_Intro](https://github.com/user-attachments/assets/3a4e885c-6beb-4453-9bf6-2ed6e173278c)

* The medical name of heart attack is “Myocardial infarction”.
* Heart attack in short; It is the occlusion of the vessel by plaque-like lesions filled with cholesterol and fat.
* The lesion is called abnormal conditions that occur in the organs where the disease is located.
* As a result of the blockage, the blood flow is completely cut off and a heart attack that can lead to death occurs.

How does a heart attack occur?
* The heart is a powerful pump that pumps blood throughout the body 60-80 times per minute at rest.
* While meeting the blood needs of the whole body, it also needs to be fed and taken blood.
* These vessels that feed the heart itself are called coronary arteries. Coronary insufficiency occurs when there is a disruption in the circulation of the coronary arteries.
* The cases of coronary insufficiency vary according to the type, degree and location of the stenosis in the coronary vessels.
* While some patients may have chest pain that occurs only during physical activity and is relieved by rest, sometimes a heart attack may occur as a result of sudden occlusion of the vessels, starting with severe chest pain and leading to sudden death.

## How to use the files in this repository?

The notebooks are grouped into the following categories:
 * ``data`` – heart_attack_prediction_dataset.csv data file from Kaggle Machine Learning dataset repository used in the notebooks
 * ``images`` – Image files used in Notebook and Project Description
 * ``notebook`` – Heart_attack_Predictions

## Conclusion

* Within the scope of the project, we first made the data set ready for Exploratory Data Analysis(EDA)
* We performed Exploratory Data Analysis(EDA).
* We analyzed numerical and categorical variables within the scope of univariate analysis by using Distplot and Pie Chart graphics.
* Within the scope of bivariate analysis, we analyzed the variables among each other using FacetGrid, Count Plot, Pair Plot, Swarm plot, Box plot, and Heatmap graphics.
* We made the data set ready for the model. In this context, we struggled with missing and outlier values.
* We used four different algorithms in the model phase.
* We got 87% accuracy and 88% AUC with the Logistic Regression model.
* We got 83% accuracy and 85% AUC with the Decision Tree Model.
* We got 83% accuracy and 89% AUC with the Support Vector Classifier Model. And we got 90.3% accuracy and 93% AUC with the Random Forest Classifier Model.
* When all these model outputs are evaluated, we prefer the model we created with the Random Forest Algorithm, which gives the best results

