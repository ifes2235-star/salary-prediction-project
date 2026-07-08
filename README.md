
# Salary Prediction Project

## Overview

This project uses Machine Learning to predict employee salaries based on factors such as job title, years of experience, education level, industry, and number of skills. The goal is to analyze salary trends and build a predictive model that estimates salaries from employee-related features.

## Dataset

The dataset contains the following features:

* **job_title** – Employee's job role
* **experience_years** – Years of work experience
* **education_level** – Highest educational qualification
* **skills_count** – Number of technical/professional skills
* **industry** – Industry sector
* **salary** – Target variable (employee salary)

## Project Workflow

1. Import required libraries.
2. Load and inspect the dataset.
3. Clean missing values and duplicates.
4. Perform Exploratory Data Analysis (EDA).
5. Encode categorical variables.
6. Split the dataset into training and testing sets.
7. Train a Machine Learning model.
8. Evaluate model performance.
9. Make salary predictions.

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

## Results

The model was trained to predict salaries using employee characteristics. Model performance was evaluated using appropriate regression metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R² Score.

## Repository Structure

```
salary-prediction-project/
│── Salary_Prediction.ipynb
│── salary_dataset.csv
│── README.md
│── requirements.txt
```

## How to Run

1. Clone the repository.
2. Install the required libraries:

   ```
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook.
4. Run all cells to reproduce the analysis and predictions.

## Future Improvements

* Test additional machine learning algorithms.
* Perform hyperparameter tuning.
* Deploy the model as a web application.
* Use larger and more diverse datasets.

## Author

**Solomon Joseph**

This project was developed as part of a Machine Learning and Data Analysis learning journey to demonstrate data preprocessing, exploratory data analysis, model building, and salary prediction using Python.
