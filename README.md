<h3>**Bank Churn Prediction with Machine Learning and Neural Networks**</h3>

This project demonstrates churn modeling using machine learning and neural network algorithms. The goal is to predict customer churn (whether a customer will exit or not) based on various customer features such as credit score, geography, gender, and balance. The dataset is sourced from a banking domain, and the analysis is structured into several well-defined stages: Exploratory Data Analysis (EDA), data preprocessing, model training, and comparison.

<h3>**Project Structure**</h3>
Exploratory Data Analysis (EDA):

Performed an in-depth analysis to understand the distribution of features and their relationship with churn.
Visualized churn distribution and feature correlations.


**Data Preprocessing:**

Encoded categorical variables like Gender and Geography using label encoding and one-hot encoding.
Scaled numerical features using StandardScaler for consistency.
Modeling and Evaluation:

**Built two models:**
  **Random Forest Classifier**: A robust ensemble model suitable for feature importance analysis and handling imbalanced data.
  **Neural Network:** A sequential deep learning model using dense layers for prediction.
  
**Evaluated both models based on:**
Confusion Matrix
Classification Report (Precision, Recall, F1-Score)
Accuracy Score
Compared model performance visually.


**Comparison of Models:**

Highlighted the accuracy differences between Random Forest and Neural Network using bar plots.
Technologies and Tools Used
Programming Language: Python
Libraries:
pandas, numpy: Data manipulation
matplotlib, seaborn: Visualization
scikit-learn: Preprocessing and machine learning
tensorflow: Neural network implementation
Environment: Google Colab (or local Jupyter Notebook)
