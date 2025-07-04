# Emotion Recognition Project

Author: Shahzaib Khan

This project is designed to analyze and classify emotions from textual data using machine learning techniques. The dataset used for this project is stored in `emotions_Dataset.xlsx`, and the main implementation is in the Jupyter Notebook file `main.ipynb`.

## Project Structure

- **emotions_Dataset.xlsx**: Contains the dataset used for training and testing the emotion recognition models.
- **main.ipynb**: The main code file where data preprocessing, feature extraction, model training, and evaluation are implemented.

## Features

1. **Data Preprocessing**:
   - Text data is cleaned and prepared for analysis.
   - Stop words in Urdu are removed using `CountVectorizer` and `TfidfVectorizer`.

2. **Feature Extraction**:
   - Bag of Words (BoW) approach using `CountVectorizer`.
   - TF-IDF method using `TfidfVectorizer`.

3. **Machine Learning Models**:
   - Various models are trained and evaluated for emotion classification, including:
     - Naive Bayes
     - Logistic Regression
     - Support Vector Machine (SVM)
     - Decision Tree
     - Random Forest Classifier
   - Hyperparameter tuning is performed for SVM and Random Forest models.

4. **Visualization**:
   - Accuracy of models is visualized using `plotly`.

## How to Run

1. Install the required Python packages:
   ```bash
   pip install pandas scikit-learn plotly seaborn matplotlib nltk
   ```
