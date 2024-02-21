
# Parkinson Diseases

Parkinson diseases is a progressive nervous system disorder that effect movement leading to shaking, stiffness, and difficulty with walking, balance and coordination.

Parkinson's symptoms usually begin gradually and get worse over time.

# Parkinson's Disease Prediction Project

## Overview
This project aims to predict Parkinson's disease using machine learning techniques. Parkinson's disease is a neurodegenerative disorder that affects movement, causing tremors, stiffness, and difficulty with balance and coordination. Early detection of Parkinson's disease can lead to better management and treatment options for patients.

## Project Structure
1. **Data Preprocessing**: The dataset used for training the model is preprocessed to handle missing values, outliers, and feature scaling. Feature engineering techniques may also be applied to extract relevant information from the raw data.

2. **Data Splitting**: The preprocessed data is split into training and testing sets. The training set is used to train the machine learning model, while the testing set is used to evaluate its performance.

3. **Model Creation**: Support Vector Machine (SVM) is chosen as the predictive model for this project due to its effectiveness in classification tasks and its ability to handle complex datasets.

4. **Model Evaluation**: The trained SVM model is evaluated using various performance metrics such as accuracy, precision, recall, and F1-score. This helps assess the model's effectiveness in predicting Parkinson's disease.

5. **Data Standardization**: Standardization is applied to the features to ensure that they have a mean of 0 and a standard deviation of 1. This step is crucial for improving the performance of certain machine learning algorithms, including SVM.

6. **Predicting System**: Once the SVM model is trained and evaluated, a predicting system is created to allow users to input new data and obtain predictions regarding the presence or absence of Parkinson's disease.

## Usage
To use this project:
1. Clone the repository to your local machine.
2. Run the Jupyter notebook or Python script to execute each step of the project pipeline.
3. Follow the instructions provided in the notebook or script to preprocess the data, train the SVM model, evaluate its performance, and create the predicting system.
4. Input new data into the predicting system to obtain predictions for Parkinson's disease.

## Dependencies
- Python 3.x
- NumPy
- Pandas
- Scikit-learn
- Jupyter Notebook (optional)



## Conclusion
In conclusion, this project demonstrates the feasibility of using machine learning techniques to predict Parkinson's disease. By preprocessing the data, training an SVM model, and evaluating its performance, we can accurately classify patients based on their symptoms. Further research could explore additional features or alternative machine learning algorithms to improve prediction accuracy.
