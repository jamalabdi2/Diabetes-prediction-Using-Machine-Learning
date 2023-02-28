# Diabetes Prediction using Machine Learning

This project aims to predict whether a person is diabetic or not based on certain features such as glucose level, blood pressure, body mass index, age, and other factors. It is achieved through various machine learning models such as Random Forest Classifier, SVM, K-Nearest Neighbors, and Logistic Regression.

# Dataset

The diabetes dataset is used in this project, which contains 768 rows and 9 columns. It is a binary classification problem where the outcome column indicates whether a person is diabetic or not. The dataset is loaded from the CSV file using the function load_diabetes_dataset.

# Preprocessing

The following preprocessing steps are applied to the dataset before building machine learning models:

1. Replacing the zero values in Glucose, BloodPressure, SkinThickness, Insulin, and BMI columns with their median.
2. Upsampling the minority class using SMOTETomek to balance the dataset.
3. Splitting the dataset into training and testing sets using the train_test_split function from scikit-learn.
4. Scaling the dataset using StandardScaler.

# Machine Learning Models

The following machine learning models are used to predict whether a person is diabetic or not:

1. Random Forest Classifier
2. SVM
3. K-Nearest Neighbors
4. Logistic Regression
5. Artificial Neural Network
The accuracy score, confusion matrix, and classification report are generated for each model.

# Libraries

The following libraries are used in this project:

1. numpy
2. pandas
3. seaborn
4. matplotlib
5. scikit-learn
6. imblearn
7. tensorflow

