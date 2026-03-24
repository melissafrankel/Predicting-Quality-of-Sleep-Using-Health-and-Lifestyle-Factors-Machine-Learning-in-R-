## Predicting Quality of Sleep Using Health and Lifestyle Factors (Machine Learning in R)
Built an end-to-end ML pipeline to predict **Quality of Sleep** and identify key lifestyle drivers using R, achieving ~0.326 RMSE on test data.

## View Full Project
[Full Project](https://rpubs.com/melissafrankel/1413578)

## View Codebook
[Codebook](https://github.com/melissafrankel/Predicting-Quality-of-Sleep-Using-Health-and-Lifestyle-Factors-Machine-Learning-in-R-/blob/main/sleep_health%20and_lifestyle_codebook.txt)

## Overview
The goal of this project is to identify key drivers of sleep quality and evaluate whether making changes in lifestyle or health factors can meaningfully improve it. 

Key Questions: 
- Are some individuals predisposed to obtaining higher quality sleep?
- Are there lifestyle changes that can be made to induce better sleep quality?
- Is Quality of Sleep strongly associated with Sleep Duration?

## Dataset 
- Source: Kaggle Sleep Health and Lifestyle Dataset
  This dataset was obtained from Kaggle and is used for educational and portfolio purposes.
- Response Variable:
  -  Quality of Sleep (numeric)
- Predictor Variables:
  - Gender (categorical/binary)
  - Age (numeric)
  - Occupation (categorical)
  - Sleep Duration (numeric)
  - Physical Activity Level (numeric)
  - Stress Level (numeric)
  - BMI Category (categorical)
  - Blood Pressure (numeric)
  - Heart Rate (numeric)
  - Daily Steps (numeric)
  - Sleep Disorder (categorical)
- Observation Variable:
  - Person ID (identifier)
## Methodology 
- Cleaned and prepared data
- Split data into training/testing sets (70/30, stratified)
- Applied 5-fold cross-validation
- Created a Recipe
- Trained and compared multiple regression models (Linear Regression, Elastic Net Regression, Decision Tree, Random Forest, Boosted Trees)
- Evaluated performance using RMSE
- Tested the two best models on the testing data to determine which model was better


## Results
The Random Forest model predicted **Quality of Sleep** the best and identified the most important predictor as **Stress Level** 
