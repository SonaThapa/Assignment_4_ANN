### Assignment_4_ANN

## Breast Cancer Data Analysis and Streamlit App

Data preprocessing, feature selection, ANN model construction, and the development of a Streamlit app for breast cancer prediction are all part of this project.

##Setup:
1. python -m venv Name *create venv
2. Install requirements.txt *pip install -r requirements.txt
3. activate environment *source Name/Scripts/activate
4. streamlit run streamlit.py to launch the streamlit app
   
##Requirements
1. Python 3.x
2. Streamlit
3. scikit-learn
4. pandas
5. joblib

##Usage
Launch the local version of Streamlit by running the streamlit.py file.

##Dataset
The following information is included in the scikit-learn Breast Cancer dataset:

Thirty features, including area, perimeter, texture, mean radius, etc.
Two target classes:
0: Carcinogenic (malignant)
1: Non-cancerous (benign)

##Qualities
Data Preprocessing and Feature Selection
The project involves importing the breast cancer dataset, handling missing values, and using SelectKBest to choose the most relevant features.

ANN Model Construction and Assessment
The MLPClassifier from scikit-learn is used to build a neural network model. Grid Search Cross-Validation optimizes the model's hyperparameters to enhance performance.

Streamlit App for Predictions and User Interaction
Users can input feature values into an interactive web application that uses Streamlit to predict whether a tumor is benign or malignant.

##Project Structure
data_preparation.py: Loads and prepares the dataset.
feature_selection.py: Selects relevant features using SelectKBest.
model_selection.py: Uses Grid Search to tune the hyperparameters of the ANN model.
Breast_cancer_data.csv: The preprocessed dataset.
streamlit.py: Streamlit application for user interaction and predictions.

##Output

https://assignment4-ann-2k7sxi9nhe5j8p8hfe3ipq.streamlit.app/

## Preview
Here is a preview of the application:
![App Screenshot](assignment_4-ANN/preview/preview.png)

