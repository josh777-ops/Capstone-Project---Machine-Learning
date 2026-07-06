# Capstone-Project---Machine-Learning

# 🤖 Telco Customer Churn Prediction

## Overview

This project was completed as part of the **HyperionDev Data Science Bootcamp** and focuses on predicting customer churn using machine learning techniques. By analysing customer data from a telecommunications company, the project develops predictive models that identify customers who are likely to cancel their services, helping businesses improve customer retention strategies.

The project follows a complete machine learning workflow, including data inspection, preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and performance comparison.

---

## Project Objectives

The main objective of this project is to build and compare machine learning models capable of predicting customer churn.

The project includes:

* Loading and inspecting the dataset
* Cleaning and preprocessing data
* Feature engineering
* Exploratory Data Analysis (EDA)
* Data visualisation
* Feature scaling
* Building classification models
* Model evaluation and comparison
* Interpreting machine learning results

---

## Dataset

The project uses the **Telco Customer Churn** dataset, which contains customer demographic information, account details, service subscriptions, and billing data.

The target variable is:

* **Churn** (Yes/No)

Example features include:

* Gender
* Senior Citizen
* Partner
* Dependents
* Tenure
* Phone Service
* Internet Service
* Monthly Charges
* Total Charges
* Contract Type
* Payment Method

---

## Technologies Used

* Python 3
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Project Structure

```text
Telco-Customer-Churn/
│
├── telco_customer_churn.ipynb      # Main notebook
├── Telco-Customer-Churn.csv        # Dataset
├── README.md                       # Project documentation
└── images/                         # Optional charts/screenshots
```

---

## Data Preparation

The dataset was prepared by:

* Inspecting the dataset
* Identifying missing values
* Converting data types
* Removing unnecessary columns
* Encoding categorical variables
* Creating dummy variables
* Scaling numerical features using Min-Max Scaling
* Splitting the data into training and testing datasets

---

## Exploratory Data Analysis

The notebook explores customer behaviour through several visualisations, including:

* Correlation heatmap
* Tenure distribution
* Monthly Charges vs Total Charges scatter plot
* Customer churn comparison
* Box plots
* Feature relationship analysis

These visualisations help identify patterns associated with customer churn and support feature selection for predictive modelling.

---

## Machine Learning Models

### Logistic Regression

A Logistic Regression classifier was trained to establish a baseline prediction model.

The model was evaluated using:

* Accuracy
* Precision
* Recall
* Confusion Matrix

---

### Random Forest Classifier

A Random Forest classifier was trained using tuned hyperparameters, including:

* 2000 decision trees
* Bootstrap sampling
* Out-of-Bag (OOB) estimation
* Square root feature selection
* Maximum of 50 leaf nodes

The model was evaluated using:

* Accuracy
* Precision
* Recall
* Confusion Matrix
* Out-of-Bag Error
* Model comparison

---

## Model Evaluation

Model performance was assessed using several classification metrics:

* Accuracy Score
* Precision
* Recall
* Confusion Matrix
* Out-of-Bag (OOB) Error
* Model Comparison

These metrics provide insight into each model's ability to correctly identify customers who are likely to churn while minimising false predictions.

---

## Skills Demonstrated

* Data Cleaning
* Data Preprocessing
* Feature Engineering
* Exploratory Data Analysis (EDA)
* Data Visualisation
* Machine Learning
* Classification Models
* Logistic Regression
* Random Forest
* Model Evaluation
* Feature Scaling
* Python Programming

---

## Learning Outcomes

Through this project I gained practical experience in:

* Preparing real-world datasets for machine learning
* Selecting meaningful features
* Building supervised classification models
* Comparing machine learning algorithms
* Evaluating model performance using multiple metrics
* Interpreting confusion matrices, precision, and recall
* Applying data-driven decision-making techniques

---

## How to Run

Clone the repository:

```bash
git clone https://github.com/yourusername/telco-customer-churn.git
```

Navigate to the project directory:

```bash
cd telco-customer-churn
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
telco_customer_churn.ipynb
```

Run all notebook cells to reproduce the analysis.

---

## Future Improvements

Potential enhancements include:

* Hyperparameter optimisation using GridSearchCV
* Cross-validation
* Feature importance analysis
* ROC and Precision-Recall curves
* XGBoost and LightGBM models
* Handling class imbalance with SMOTE
* Model deployment using Flask or Streamlit
* Interactive dashboard for churn prediction

---

## Project Deliverables

* ✔️ Data cleaning and preprocessing
* ✔️ Exploratory Data Analysis (EDA)
* ✔️ Feature engineering
* ✔️ Logistic Regression model
* ✔️ Random Forest classifier
* ✔️ Model evaluation and comparison
* ✔️ Data visualisations
* ✔️ Well-documented Jupyter Notebook

---

## Author

Developed as part of the **HyperionDev Data Science Bootcamp** to demonstrate practical applications of machine learning, predictive analytics, and customer churn modelling.

---

## License

This project is intended for educational and portfolio purposes.
