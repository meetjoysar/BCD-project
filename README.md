# BCD(Breast Cancer Detection using Various Machine Learning Algorithms)-project
This was the project made in collaboration with 3 of my friends for 4th semester in our collage.

The objective of this project is to identify breast cancer through the utilization of diverse machine learning algorithms. The study investigates several models, including logistic regression, decision tree, random forest, ridge logistic regression (ridge classifier), and support vector classifier. Furthermore, two distinct scaling techniques, standard scaler and min-max scaler, have been utilized for data preprocessing.

# Project Summary
Breast cancer poses a significant health risk to women globally, emphasizing the importance of early detection for better patient outcomes. Machine learning algorithms offer a promising approach to automate the detection process by analyzing pertinent features extracted from medical data.

The aim of this project is to assess and compare the effectiveness of various machine learning algorithms in detecting breast cancer. The algorithms employed are as follows:

1. Logistic Regression
2. Decision Tree
3. Random Forest
4. Ridge Logistic Regression (Ridge Classifier)
5. Support Vector Classifier

To enhance the performance of these models, two widely-used scaling techniques, Standard Scaler and Min-Max Scaler, have been implemented to normalize the input features. This normalization process aims to improve the accuracy and efficiency of the algorithms in detecting breast cancer.

# Dataset
<br />Here we took a dataset from kaggle with more than 30 features of patients consisting malignant or benign breast cancer, and we the help of various model we classified the tumor in those categories i.e. Malignant and Benign

# Execution
The project execution encompasses the following stages:
1. Data Preprocessing: The dataset undergoes preprocessing to address missing values, handle categorical variables, and scale the features utilizing the chosen scaling techniques, namely Standard Scaler and Min-Max Scaler.

2. Model Training: The preprocessed data is divided into training and testing sets. Each machine learning algorithm is trained on the training set, utilizing the scaled features.

3. Model Evaluation: Once trained, each model is assessed using the testing set. Evaluation metrics such as accuracy, precision, recall, and F1-score are employed. The performance of each algorithm is compared across the various scaling techniques.

4. Results and Discussion: The obtained results are analyzed, and the performance of each model and scaling technique is discussed. Areas with potential for improvement are also identified and highlighted.

# Result
The accuracy results for each combination of machine learning algorithms and scaling techniques are as follows:

- Logistic Regression with Standard Scaler: 95.61%
- Logistic Regression with Min-Max Scaler: 96.49%
- Decision Tree with Standard Scaler: 92.98%
- Decision Tree with Min-Max Scaler: 92.98%
- Random Forest with Standard Scaler: 97.37%
- Random Forest with Min-Max Scaler: 97.37%
- Ridge Logistic Regression with Standard Scaler: 94.74%
- Ridge Logistic Regression with Min-Max Scaler: 95.61%
- Support Vector Classifier with Standard Scaler: 98.25%
- Support Vector Classifier with Min-Max Scaler: 97.37%

# Conclusion
Within this project, we examined numerous machine learning algorithms with the aim of detecting breast cancer. The performance of each algorithm was assessed by employing two distinct scaling techniques. The results indicate that the Support Vector Classifier with Standard Scaler attained the highest level of accuracy. As a result, it can be inferred that this particular combination excels in breast cancer detection.

# Note:
<br />- A pdf has been uploaded where all our research work about our project is described and all the ouputs of our code.
<br />- The project report pdf is also attached where you will get the complete survey of our project
<br /> - Also the dataset used for this project has been attached as data.csv file
