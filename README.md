# HR-Salary-Prediction-Model
A linear regression model built using Python and scikit-learn to predict employee salaries based on experience, written test scores, and interview performance.
Problem Statement

The HR department wants to predict candidate salaries based on:

Years of experience

Written test score

Interview score

# Dataset

The dataset contains 8 records with:

Experience (years)

Test score (out of 10)

Interview score (out of 10)

Salary

# Approach

Data cleaning:

Converted text experience to numeric

Filled missing values using median

Feature-target separation

Linear regression model training

Model evaluation using R² score

Model Performance

R² Score: 0.9617

The model explains approximately 96% of the variance in salary within this dataset.

Note: Dataset size is small, so model may not generalize well.


# Predictions

Candidate 1:

2 years experience

9 test score

6 interview score

Predicted Salary: $53205.97

Candidate 2:

12 years experience

10 test score

10 interview score

Predicted Salary: $92002.18
