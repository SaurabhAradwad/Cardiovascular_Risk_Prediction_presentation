# Cardiovascular_Risk_Prediction_presentation

Heart disease is a major health problem in India. According to the World Health Organization (WHO), cardiovascular diseases are the leading cause of death in India, accounting for more than 2.5 million deaths each year.

This classification case study will help us to understand important factors which contribute to heart related diseases. Supervised machine learning’s classification model we have created for the prediction of  whether the patient has a 10-year risk of developing coronary heart disease.

The given data set provides the patients’ information. It includes over 4,000 records and 15 attributes. Each attribute is a potential risk factor. There are both demographic, behavioural and medical risk factors.

Models Used for classification-
- Logistic Regression
- Random Forest
- XGBoost
- Support Vector Machine
The best performing model is Support Vector Machine algorithm.

## Problem Statement

Due to superiority in pattern recognition and classification when compared to other traditional statistical approaches, doctors and scientists alike have turned to machine learning (ML) techniques to develop screening tools.

In this project, we have used different Machine Learning techniques to predict whether a patient has a 10-year risk of developing coronary heart disease (CHD) on the Framingham, Massachusetts town dataset.

The classification goal is to predict whether the patient has 10-year risk of future coronary heart disease (CHD). The data set provides the patients’ information. It includes over 4,000 records and 15 attributes. Each attribute is a potential risk factor. There are both demographic, behavioural and medical risk factors. 

## Authors

- [@Aman Guleria](https://www.github.com/AMAN-GULERIA)
- [@Saurabh Aradwad](https://www.github.com/SaurabhAradwad)
- [@Rishika Rai](https://www.github.com/Rishika70)


## Referance Project Document

- [Dataprep Report](https://drive.google.com/file/d/1D-650REB2BUQgE2d7xqCAPME8SwMeyNE/view?usp=share_link)
- [Project Report](https://docs.google.com/document/d/1QSCDqAC_MoXteTYedrVYmjrzeFMzbv8gFpGrjTGKfPk/edit?usp=share_link)
- [Project Summary](https://docs.google.com/document/d/1wS36wU7TN42WnKXJh3SdA4bhYGQo70s0AYwveVTjZjU/edit?usp=share_link)
- [Colab Notebook ✔](https://colab.research.google.com/drive/1kJi6m8AbqvVqkcuwkOV0XToPvWQpVozx?usp=share_link)
- [Presentation PPt](https://docs.google.com/presentation/d/1IGQ2yNI4yTvQp8qBNndLPPeL_ZMeoanEaS1BqLJsGjQ/edit?usp=share_link)

## Data Summary

All columns and type of information stored in the csv file is as follows

Demographic 

- *sex* - male or female("M" or "F")
- *age* - age of the patient;(Continuous - Although the recorded ages have been truncated to whole numbers, the concept of age is continuous)
- *is_smoking* - whether or not the patient is a current smoker ("YES" or "NO")
- *cigsPerDay* - the number of cigarettes that the person smoked on average in one day.(can be considered continuous as one can have any number of cigarettes, even half a cigarette.) 

Medical(history)

- *BPMeds* - whether or not the patient was on blood pressure medication (Nominal)
- *prevalentStroke* - whether or not the patient had previously had a stroke (Nominal) 
- *prevalentHyp* - whether or not the patient was hypertensive (Nominal) 
- *diabetes* - whether or not the patient had diabetes (Nominal)

Medical(current)

- *totChol* - the longitude where the metre was disengaged
- *sysBP* - the latitude where the metre was  disengaged
- *diaBP* - This flag indicates whether the trip record was  held in vehicle memory before sending to the vendor because the vehicle did not have a connection to the server (Y=store and forward; N=not a store and forward trip)
- *BMI* - duration of the trip in seconds

Predict variable (desired target)
- *TenYearCHD* - 10 year risk of developing coronary heart disease (CHD) — (binary: “1”, means “There is a risk”, “0” means “There is no risk”). 

## Conclusions

- Risk of Cardiovascular heart disease is almost equal between smokers and non-smokers and the same goes with gender. It is pretty much the same for both male and females.
- Correlation obtained is very poor for this dataset but still due to tuned parameters and strong classification algorithms model efficiency obtained is about 93%.
- The top contributing features in predicting the ten year risk of developing Cardiovascular Heart Disease are 'age', 'totChol', 'sysBP', 'diaBP', 'BMI', 'heartRate', 'glucose'.
- The Support vector machine with the radial kernel is the best performing model in terms of accuracy and the F1 score and Its high AUC-score shows that it has a high true positive rate.
- Balancing the dataset by using the SMOTE technique helped in improving the models' sensitivity. 
- With more data & with more correlated features better models can be built.
