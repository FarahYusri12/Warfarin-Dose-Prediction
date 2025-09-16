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

## How To Run The Code

This project was developed and tested using **Google Colab**.  
Follow the steps below to reproduce the analysis:

1. Open the notebook in Google Colab:
 
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/FarahYusri12/Warfarin-Dose-Prediction/blob/main/Warfarin_dosing(ML).ipynb)


2. Download the dataset
   
   [Click here to download the dataset](https://github.com/FarahYusri12/Warfarin-Dose-Prediction/blob/main/Warfarin_gen_clinic.csv?raw=true&download=1)

   - The file will automatically be saved as **Warfarin_gen_clinic**
4. Upload the dataset:
   - Run the following cell in the notebook:
     ```python
     from google.colab import files
     uploaded = files.upload()
     ```
   - Choose the CSV file from your computer when prompted.

5. Run the remaining cells **step by step** after uploading the file.
   > ⚠️ Note: “Run All” will not work because the file upload requires manual input.

6. Outputs:
   - Preprocessed dataset
   - Regression model results
   - Feature importance graph
   - Visualizations of predicted vs actual doses


## Key Findings
The model achieved an R2 score of 0.46, meaning it can explain 46% of the variablility in warfarin dosage.

The feaature importance analysis revealed that genetic factor which is VKORC1 are the most dominant determinants in dose prediction.

Some of the model's findings, such as the relationship between gender and dose, contradicted with the existing knowledge. Emphasizing the importance of crtically evaluating model outputs with domain expertise.
