# Health Insurance Premium Prediction

## Project Overview

This project predicts health insurance premiums using Machine Learning. By analyzing customer information such as age, gender, BMI, smoking status, number of children, and residential region, the model estimates the expected insurance charges.

The project demonstrates the complete Machine Learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and model evaluation.

---

## Objective

The objective of this project is to build a regression model that accurately predicts an individual's health insurance premium based on demographic and lifestyle factors.

---

## Dataset

**Dataset:** `insurance_prediction.csv`

### Features

| Feature | Description |
|---------|-------------|
| age | Age of the policy holder |
| sex | Gender (Male/Female) |
| bmi | Body Mass Index |
| children | Number of dependent children |
| smoker | Smoking status (Yes/No) |
| region | Residential region |
| charges | Health insurance premium (Target Variable) |

### Dataset Information

- Total Records: 1,338
- Total Features: 7
- Target Variable: `charges`

---

## Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## Project Workflow

### 1. Import Libraries

The required Python libraries are imported for data analysis, visualization, machine learning, and model evaluation.

### 2. Load Dataset

The insurance dataset is loaded into a Pandas DataFrame.

### 3. Data Exploration

The dataset is explored to understand its structure by checking:

- Shape of the dataset
- Data types
- Missing values
- Duplicate records
- Statistical summary

### 4. Exploratory Data Analysis (EDA)

The following analyses are performed:

- Age Distribution
- Gender Distribution
- BMI Distribution
- Smoking Status Distribution
- Region Distribution
- Children Distribution
- Correlation Heatmap
- Pair Plot
- Box Plots
- Histograms

### 5. Data Preprocessing

Data preprocessing includes:

- Removing duplicate records
- Encoding categorical variables
- Preparing the dataset for machine learning

### 6. Train-Test Split

The dataset is divided into:

- Training Set
- Testing Set

### 7. Model Building

Machine Learning Algorithm Used:

- Linear Regression

### 8. Model Evaluation

The model performance is evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

---

## Results

The Linear Regression model predicts health insurance premiums based on customer information.

The performance is evaluated using regression metrics:

- Lower MAE indicates better prediction accuracy.
- Lower MSE indicates fewer prediction errors.
- Higher R² Score indicates better model performance.

---

## Project Structure

```
Health_Insurance_Premium_Prediction/
│
├── Health_Insurance_Premium_Prediction.ipynb
├── insurance_prediction.csv
└── README.md
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Health-Insurance-Premium-Prediction.git
```

Install the required libraries:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

Run the notebook:

```bash
jupyter notebook
```

Open the notebook and execute all cells.

---

Thank you !!
This project is intended for educational and learning purposes.
````
