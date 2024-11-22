### Assignment_4_ANN

## Breast Cancer Data Analysis and Streamlit App

Data preprocessing, feature selection, ANN model construction, and the development of a Streamlit app for breast cancer prediction are all part of this project.
Setup: *python -m venv Name *create venv
Install requirements.txt *pip install -r requirements.txt *activate environment *source Name/Scripts/activate
streamlit run streamlit.py to launch the streamlit app
Conditions
Streamlit scikit-learn pandas joblib for Python 3.x
Use
Launch the local version of Streamlit: ( run streamlit.py on streamlit
The dataset
## The following information is included in the scikit-learn Breast Cancer dataset:
Thirty features, including area, perimeter, texture, mean radius, etc.

Two target classes:
0: Carcinogenic (malignant)
1. Non-cancerous (benign)
## Qualities
Data Preprocessing and Feature Selection: The project entails importing the dataset on breast cancer, dealing with missing values, and utilizing SelectKBest to choose the most pertinent features.

* ANN Model Construction and Assessment: MLPClassifier from sklearn is used to construct a neural network model. Grid Search Cross-Validation is used to optimize the model's hyperparameters in order to enhance performance.
Streamlit App for Predictions and User Interaction: Users can enter feature values into an interactive web application that uses Streamlit to forecast if a tumor is benign or malignant.
The project structure includes the following scripts: data_preparation.py, which loads and prepares the dataset; feature_selection.py, which selects features; and model_selection.py, which uses Grid Search to adjust the ANN model hyperparameters.The ANN model's creation and training script
Breast cancer data.csv is a preprocessed dataset, and streamlit.py is a Streamlit application for user interaction and predictions.
Output
Output
=======
https://assignment4-ann-2k7sxi9nhe5j8p8hfe3ipq.streamlit.app/

