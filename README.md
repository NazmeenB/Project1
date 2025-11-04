# Liver Disease Prediction Project

## Overview
This project aims to predict liver disease presence using patient health data. It demonstrates a full data science workflow from data loading and exploration to model building, evaluation, and deployment as an interactive web app. The project ends with a presentation summarizing the findings and results.

## Dataset
- **File:** project-data.csv  
- **Description:** Patient health metrics including demographic, biochemical, and clinical variables related to liver health.  
- **Size:** Approximately 600 records with 12 features including the target label indicating disease presence.

## Tools and Technologies
- **Python:** pandas, numpy, matplotlib, seaborn for data handling and visualization  
- **Scikit-learn:** for model training and evaluation  
- **Streamlit:** to build a user-friendly web app for deployment  
- **Jupyter Notebook:** for development and experimentation  
- **PowerPoint:** for slide deck summarizing work

## Steps
1. **Load Dataset:** Imported the CSV into Python using pandas for initial inspection.  
2. **Exploratory Data Analysis (EDA):** Explored key variables, distributions, missing values, and correlations. Visualized patterns and potential predictors.  
3. **Data Cleaning:** Handled missing values and outliers, encoded categorical variables, and standardized features.  
4. **Model Building:** Trained multiple machine learning models (e.g. Logistic Regression, Random Forest, XGBoost) to predict liver disease.  
5. **Model Evaluation and Selection:** Compared models based on accuracy, precision, recall, and ROC-AUC. Selected the best-performing model for deployment.  
6. **Deployment:** Developed an interactive Streamlit app that allows users to input patient data and receive real-time disease risk predictions.  
7. **Presentation:** Created a concise PPT summarizing methodologies, insights, model performance, and recommendations.

## Results
- Achieved a model accuracy of approximately 94% with the SVM Model.  
- Key features influencing predictions include category age, sex, albumia, alkaline_phosphatase, alanine_aminotransferase, aspartate_aminotransferase, bilirubin,cholinesterase, cholesterol, creatinina, gamma_glutamyl_transferase, protein.                                   .  
- The interactive app enables easy access to predictions, supporting clinical decision-making.
