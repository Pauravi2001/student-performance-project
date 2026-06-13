# Student Academic Performance Prediction and Behavioral Analytics System

## Project Overview

This project analyzes student habits and predicts academic performance using Machine Learning techniques.

The objective is to understand how factors such as study hours, attendance, sleep patterns, internet quality, extracurricular participation, and lifestyle habits influence examination scores.

The project demonstrates a complete Data Science workflow, including:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Machine Learning Model Development
- Model Evaluation
- Feature Importance Analysis

---

## Objectives

- Analyze the relationship between student habits and academic performance.
- Identify the most influential factors affecting examination scores.
- Build predictive models for exam score prediction.
- Compare machine learning algorithms.
- Generate meaningful insights from educational data.

---

## Dataset

**Dataset Name:** Student Habits and Academic Performance Dataset

The dataset contains information about:

- Study Hours Per Day
- Attendance Percentage
- Sleep Hours
- Social Media Usage
- Internet Quality
- Diet Quality
- Extracurricular Participation
- Parental Education Level
- Part-Time Job Status
- Exam Score (Target Variable)

---

## Technologies Used

### Programming Language

- Python

### Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Pickle

### Development Environment

- Google Colab

---

## Project Structure

```text
student-performance-prediction/
│
├── Student_Performance_Prediction.ipynb
├── student_habits_performance.csv
├── cleaned_student_data.csv
├── random_forest_model.pkl
├── requirements.txt
└── README.md
```

---

## Project Workflow

### 1. Data Collection

- Upload dataset using Google Colab.
- Load data using Pandas.

### 2. Data Cleaning

- Remove duplicate records.
- Remove unnecessary columns such as `student_id`.
- Handle missing values.
- Verify data quality.

### 3. Exploratory Data Analysis (EDA)

Performed:

- Dataset overview
- Statistical summaries
- Distribution analysis
- Correlation analysis
- Data visualization

Visualizations include:

- Histograms
- Scatter Plots
- Correlation Heatmaps
- Feature Importance Graphs

### 4. Feature Engineering

- Encoding categorical variables using Label Encoding.
- Preparing data for machine learning algorithms.

### 5. Machine Learning

Implemented the following models:

#### Linear Regression

Used as a baseline regression model.

#### Random Forest Regressor

Used to improve prediction performance and analyze feature importance.

### 6. Model Evaluation

Evaluation metrics:

- Mean Absolute Error (MAE)
- R² Score

### 7. Feature Importance Analysis

Analyzed which factors contribute most significantly to student performance.

---

## Machine Learning Pipeline

```text
Dataset
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
Feature Engineering
   ↓
Train-Test Split
   ↓
Linear Regression
   ↓
Random Forest Regressor
   ↓
Model Evaluation
   ↓
Feature Importance Analysis
   ↓
Model Saving
```

---

## Results

Key observations from the analysis include:

- Study habits influence examination performance.
- Attendance shows a strong relationship with academic outcomes.
- Lifestyle factors contribute to score variation.
- Random Forest generally performs better than Linear Regression for this dataset.
- Feature importance analysis helps identify critical success factors.

---

## Model Saving

The trained Random Forest model is saved using Python's Pickle module.

Example:

```python
import pickle

with open("random_forest_model.pkl", "wb") as f:
    pickle.dump(model, f)
```

This allows the trained model to be reused without retraining.

---

## How to Run the Project

### Step 1

Open Google Colab.

### Step 2

Upload:

- `Student_Performance_Prediction.ipynb`
- `student_habits_performance.csv`

### Step 3

Run all notebook cells sequentially.

### Step 4

Upload the dataset when prompted.

### Step 5

Enter the target column name:

```text
exam_score
```

### Step 6

Review:

- Data Cleaning Results
- EDA Visualizations
- Model Performance
- Feature Importance Analysis

---

## Future Improvements

Possible extensions:

- Hyperparameter Tuning
- Cross Validation
- Additional Regression Models
- Streamlit Web Application
- Flask Deployment
- Student Performance Dashboard
- Real-Time Prediction System

---

## Learning Outcomes

This project helped develop practical experience in:

- Python Programming
- Data Cleaning
- Data Visualization
- Exploratory Data Analysis
- Feature Engineering
- Machine Learning
- Model Evaluation
- GitHub Documentation

---

## Author

**Pauravi Tawde**

- Interested in Machine Learning, Data Science, and AI Applications
