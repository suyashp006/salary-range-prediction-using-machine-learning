# Salary Range Prediction Using Machine Learning

## Project Overview

This project predicts salary ranges for job postings using machine learning techniques. The objective is to estimate both minimum and maximum salary values based on job-related attributes such as title, category, experience level, location, and job description characteristics.

---

## Business Problem

Organizations and job portals often require accurate salary estimation to:

- Improve hiring decisions
- Maintain competitive compensation structures
- Increase transparency in recruitment
- Support workforce planning

This project automates salary range prediction using historical job posting data.

---

## Dataset

Dataset: NYC Job Postings Dataset

Features include:

- Job Title
- Job Category
- Career Level
- Employment Type
- Location
- Job Description
- Salary Information

Target Variables:

- Minimum Salary
- Maximum Salary

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost
- LightGBM
- Joblib

---

## Project Workflow

### Data Cleaning

- Handled missing values
- Renamed columns
- Selected relevant features

### Feature Engineering

Created:

- Salary Midpoint
- Salary Range
- Description Length
- Number of Skills
- Seniority Category

### Exploratory Data Analysis

Performed:

- Salary Distribution Analysis
- Top Paying Categories Analysis
- Salary by Seniority Analysis
- Correlation Study

### Data Preprocessing

Applied:

- One-Hot Encoding
- Feature Transformation
- Train-Test Split

### Model Development

Built separate models for:

#### Minimum Salary Prediction

- Gradient Boosting Models
- Hyperparameter Tuning using RandomizedSearchCV

#### Maximum Salary Prediction

- Gradient Boosting Models
- Hyperparameter Optimization

### Model Evaluation

Metrics:

- RMSE
- MAE
- R² Score

### Feature Importance Analysis

Used Permutation Importance to identify key salary drivers.

### Model Deployment Preparation

Saved trained models using Joblib.

---

## Key Insights

- Job category significantly influences salary levels.
- Senior positions receive substantially higher compensation.
- Description complexity and skill requirements impact salary predictions.
- Boosting algorithms provide strong predictive performance.

---

## Results

Models were evaluated using:

- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)
- R² Score

Both minimum and maximum salary models demonstrated reliable prediction capability.

---

## Future Improvements

- Deploy using Streamlit
- Integrate live job posting APIs
- Build salary recommendation engine
- Implement deep learning approaches

---

## Author

Suyash Patil

Data Analytics & AI Professional
