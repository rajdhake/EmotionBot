# EmotionBot

## Overview
This is a Streamlit web application designed to identify six human emotions: Joy, Fear, Anger, Love, Sadness, and Surprise. The app leverages machine learning and deep learning models that have been trained on preprocessed text data.

## Requirements
Make sure you have the required packages installed:
```bash
pip install scikit-learn==1.3.2
pip install streamlit numpy nltk
pip install tensorflow==2.15.0
## Usage
# Model and Files
The app uses the following saved files:

logistic_regresion.pkl: Pickle file containing the logistic regression model.
tfidf_vectorizer.pkl: Pickle file containing the TF-IDF vectorizer.
label_encoder.pkl: Pickle file containing the label encoder.
## Functionality
Enter text in the input box.
Click the "Predict" button to see the predicted emotion and probability.
Feel free to modify the app, improve the model, or add more features based on your needs.

# Credits
This app is created by Raj Dhake

# License
This project is licensed under the MIT License 
