# Students Grade Predictions

### About
This project involves predicting the final grades of students there are numerous features that were eventually prunned to a few to ensure that only relevant features gets feed into the Machine Learning model.

### Features/Factors Considered/Independent Variable
The Features include everything ranging family size, parent's income, romantic life, availanility of internet services to first term and second term grade (G1 and G2)

### Labels/Outcome/Dependent Variable
The label in question here is the G3 or final grades of the students.

### Models
Two Main models were used in this project.

Linear Regression
Random Forest Regression

### Files Description
school_grades_dataset.csv - The Dataset used for this project gotten from kaggle https://www.kaggle.com/dipam7/student-grade-prediction
LabelBinarizedSGP.csv - The Dataset that has been filtered through the Label Binarizer algorithm to turn all columns that contains words into numerics.
LabelEncodedSGP.csv - The Dataset that has been filtered through the Label Encoder algorithm to turn the binarized columns into ones and zeroes
Student Grade Prediction using Random Forest Regressor.ipynb - Code for using Random Forest Regressor algorithm to predict the final grades.
Students Grades Prediction using linear regression.ipynb - Code for using Linear Regression algorithm to predict the final grades.

