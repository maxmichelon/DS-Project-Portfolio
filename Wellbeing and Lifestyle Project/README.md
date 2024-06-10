Wellbeing and Lifestyle Project
Overview
This project is based on the Wellbeing and Lifestyle dataset from Kaggle. The primary objectives were to preprocess the dataset, build and train various machine learning models, and perform comprehensive data analysis with visualizations to gain insights into different aspects of wellbeing and lifestyle.

Objectives
Preprocess the dataset in Python
Design and implement various machine learning models
Evaluate and compare model performance
Perform data analysis and create visualizations
Skills Utilized
Data preprocessing
Machine learning (Logistic Regression, Support Vector Machine, Decision Tree, Random Forest, Neural Network)
Python
Data visualization
Data Preprocessing
The dataset was cleaned and preprocessed using Python. The key steps included:

Dropping unnecessary columns
Handling missing values
One-hot encoding categorical variables
Scaling numerical features
Splitting the data into training, validation, and test sets
Machine Learning Models
Several machine learning models were built and trained using the preprocessed data:

Logistic Regression

Used to predict the gender of survey respondents.
Achieved training accuracy of 66.70% and validation accuracy of 66.51%.
Support Vector Machine (SVM)

Used to predict the gender of survey respondents.
Achieved training accuracy of 66.70% and validation accuracy of 66.66%.
Decision Tree

Used to predict the age group of survey respondents.
Achieved training accuracy of 99.97%, validation accuracy of 38.06%, and test accuracy of 38.84%.
Random Forest

Used to predict the age group of survey respondents.
Achieved training accuracy of 99.97%, validation accuracy of 48.01%, and test accuracy of 48.20%.
Neural Network

Used to predict the work-life balance score of survey respondents.
Achieved average training RMSE of 0.0861, validation RMSE of 0.0882, and test RMSE of 0.0687.
Analysis and Visualizations
Various analyses were conducted on the data, and visualizations were created to highlight key insights:

Gender prediction using Logistic Regression and SVM
Age group prediction using Decision Tree and Random Forest
Work-life balance score prediction using Neural Network
Sample Visualizations
Confusion matrix for Logistic Regression and SVM
Confusion matrix for Decision Tree and Random Forest
Training and validation loss for Neural Network
Usage
To run the project, you need to have the following installed:

Python 3.x
pandas
scikit-learn
matplotlib
seaborn
TensorFlow
Files
proj3_data_preprocess.ipynb: Contains the data preprocessing steps.
proj3_machine_learning.ipynb: Contains the implementation of various machine learning models.
proj3_report.txt: Contains the project report and detailed analysis.
Conclusion
The results across different machine learning techniques varied significantly, highlighting the importance of model selection and tuning in predictive accuracy. Logistic Regression and SVM displayed more stable performances, indicating better generalization capability. Decision Trees and Random Forests showed overfitting, while the Neural Network's MSE values indicated slight overfitting but more consistent performance.

