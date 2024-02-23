
# PIMA Diabetics Prediction Project

## Overview
This project focuses on predicting the likelihood of diabetes in individuals based on various health indicators. It utilizes machine learning techniques to analyze the PIMA Indians Diabetes dataset and build a predictive model.

## Project Structure
- `diabetes.csv`: Dataset containing health information of individuals, including attributes like pregnancies, glucose levels, blood pressure, skin thickness, insulin levels, BMI, diabetes pedigree function, and age.
- `main.ipynb`: Jupyter Notebook containing the Python code for data analysis, preprocessing, model training, evaluation, and prediction.
- `diabetics_model.sav`: Saved machine learning model using pickle for future use.

## Libraries Used
- `pandas`: For data manipulation and analysis.
- `numpy`: For numerical computations.
- `scikit-learn (sklearn)`: For machine learning tasks, including preprocessing, model selection, and evaluation.

## Project Workflow
1. **Data Collection and Analysis**: The dataset is loaded and analyzed to understand its structure, statistical measures, missing values, and distribution of classes.
2. **Data Preprocessing**: Data is preprocessed by handling missing values, standardizing numerical features, and splitting into training and testing sets.
3. **Model Training**: A Support Vector Machine (SVM) classifier with a linear kernel is trained on the standardized data.
4. **Model Evaluation**: The trained model is evaluated on both training and testing data to assess its performance using accuracy score.
5. **Prediction System**: A prediction system is created to predict diabetes status for new input data.
6. **Model Saving and Loading**: The trained model is saved for future use and loaded for making predictions on new instances.

## Key Findings
1. The dataset comprises essential health attributes such as pregnancies, glucose levels, blood pressure, skin thickness, insulin levels, BMI, diabetes pedigree function, and age.
2. Through exploratory data analysis, we observed variations in these attributes among individuals with and without diabetes, highlighting their significance in disease prediction.
3. Preprocessing steps, including handling missing values, standardizing numerical features, and splitting the data into training and testing sets, were crucial for model training and evaluation.
4. We trained a Support Vector Machine (SVM) classifier with a linear kernel on the standardized data, achieving respectable accuracy scores on both training and testing datasets.
5. A prediction system was developed to classify new instances into diabetic and non-diabetic categories, enabling proactive health management and intervention.

## Usage
1. Ensure Python and required libraries are installed.
2. Clone the repository and navigate to the project directory.
3. Run `main.ipynb` in a Jupyter Notebook environment for detailed analysis and model training.
4. Utilize `diabetics_model.sav` to make predictions on new data points.


## Conclusion
In this project, we embarked on a journey to build a predictive model for identifying the likelihood of diabetes in individuals based on various health indicators. By leveraging machine learning techniques and the PIMA Indians Diabetes dataset, we gained insights into the factors influencing diabetes and developed a robust prediction system.
