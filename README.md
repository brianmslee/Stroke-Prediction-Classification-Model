# Stroke Prediction Classification Model 

## Group Members: 
Brian Lee \
Yu-Hsi (Joy) Chen\
Ilkay Ates\
Roy Jiang\
Alexis Valdez

## Project Description:
This project will utilize healthcare data from stroke patients to gather extensive clinical data. The collected data will be anlyzed and build the machine learning model to understand which features (gender, age, hypertension, and etc) mainly determine stroke potential. The analysis will include the correlation between each features and targeted result (have stroke or not). The project will provide valuable insights for doctors, clinical studies, and the general public health on the effects and prevention of strokes. Pandas, Matplotlib, and PostgreSQL will be utilized to visualize the stroke predictions. 

## Questions to ask:
1. What Socioeconomic status of people will have a higher chance of strokes?
2. Will analyzing data reveal that strokes are affected by marriage?
3. Do smokers have a higher risk of having a stroke?
4. Is diet affecting likelihood  of having a stroke?
5. What age is it more expected?
6. Which feature in our dataset impact on the possibility of stroke? 

## Parameters to consider:
gender \
age \
hypertension \
heart_disease \
ever_married \
work_type \
Residence_type \
avg_glucose_level \
bmi \
smoking_status 


## Resources:
https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset

### Breakdown of Tasks:
1. Research potential data sources
2. Machine learning: \
  The data is cleaned, normalized, and standardized prior to modeling (from sql or spark) \
  Machine learning model building
3. Data Visualization: \
  Matplotlib \
  Tableau
  
## Creation of keras sequential model 
![image](https://user-images.githubusercontent.com/114372545/230539321-6720b32a-0602-4755-9830-35e70bdca451.png)

## Confusion Matrix and Classification Report 
![image](https://user-images.githubusercontent.com/114372545/230539437-34db007f-dd93-4f27-8bfc-5fabbba9014e.png)
![image](https://user-images.githubusercontent.com/114372545/230539492-ad92297a-9347-48c2-aeca-720939e71b8b.png)

## Feature Importance 
![image](https://user-images.githubusercontent.com/114372545/230539567-d86f06d1-eb12-4ebe-994b-5c29b4b855e6.png)

## Model Optimization by utilizing SMOTE for balanced classes
![image](https://user-images.githubusercontent.com/114372545/230539710-c04f971b-97a3-4d23-94a8-4b92959b49b6.png)
