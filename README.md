# Lab8

# K-Nearest Neighbors (KNN) Project

## Overview
This project applies the K-Nearest Neighbors (KNN) algorithm on a synthetic dataset to classify target classes based on multiple features.

The assignment involved completing missing code steps including data exploration, standardization, model training, evaluation, and selecting the best K value.

## Dataset Information
The dataset contains multiple numerical features and a target column:
- Feature variables (X)
- Target Class

## Tasks Performed

### 1. Data Exploration
- Loaded the dataset using pandas
- Explored the data using head() and pairplot visualization
- Used hue based on TARGET CLASS

### 2. Feature Scaling
- Imported StandardScaler from scikit-learn
- Applied standardization to ensure all features are on the same scale
- Converted scaled data back into a DataFrame

### 3. Train-Test Split
- Split dataset into training and testing sets using train_test_split

### 4. KNN Model Training
- Created KNN model with k=1 initially
- Fitted the model on training data

### 5. Predictions and Evaluation
Evaluated model using:
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)

### 6. Choosing Best K Value (Elbow Method)
- Tested multiple K values using a loop
- Recorded error rates
- Plotted error rate vs K value to select optimal K

### 7. Final Model
- Retrained model using best K value (K=30)
- Improved performance compared to initial model

## Results
- Initial model (K=1): lower accuracy and more errors
- Optimized model (K=30): improved accuracy (~84%) and better balance between precision and recall

## Libraries Used
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
