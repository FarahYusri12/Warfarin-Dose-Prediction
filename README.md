# Warfarin Dose Prediction

## Introduction
This project aims to develop a linear regression model that have ability to predicts the optimal warfarin dose by utilized both clinical and genetic factors. The model serves as a proof-of-concept to signifies the technical skills in data preprocessing, regerssion modelling, and performace evaluation.

## Data
The dataset used in the project was obtained from the International Warfarin Pharmacogenetics Consortium (IWPC). The data includes patient's information such as age, gender, weight, height, warfarin dose and, CYP2C9 and VKORC1 genotypes.

## Analysis
In this project;

-Performed data prepocessing including the encoding of categorical features.

-Develop a linear regression model to predict the warfarin dose.

-Evaluated the model's performance by using metrics such as MAE, RMSE, and R2.

-Analyzed the relative importance of each feature including genetic and clinical factors in dose prediction.

## Key Findings
The model achieved an R2 score of 0.40, meaning it can explain 40% of the variablility in warfarin dosage.

The feaature importance analysis revealed that genetic factors such as CYP2C9 and VKORC1 are the most dominant determinants in dose prediction.

Some of the model's findings, such as the relationship between gender and dose, contradicted with the existing knowledge. Emphasizing the importance of crtically evaluating model outputs with domain expertise.
