# HR Employee Attrition Prediction

## Overview

This project is a Machine Learning application that predicts whether an employee is likely to leave the company based on HR data. The project includes data preprocessing, exploratory data analysis (EDA), model training, evaluation, and deployment using Streamlit.

## Dataset Description

The dataset used in this project is the **IBM HR Analytics Employee Attrition & Performance Dataset**.

It contains information about employees, including:

### Employee Information
- Age
- Gender
- Marital Status
- Education Level
- Education Field
- Business Travel
- Department
- Job Role

### Job Information
- Job Level
- Job Satisfaction
- Job Involvement
- Job Environment Satisfaction
- Relationship Satisfaction
- Work-Life Balance
- Years At Company
- Years In Current Role
- Years Since Last Promotion
- Years With Current Manager

### Salary and Performance Information
- Monthly Income
- Percent Salary Hike
- Stock Option Level
- Performance Rating
- Over Time

### Target Variable
- **Attrition**
  - Yes → Employee left the company
  - No → Employee stayed in the company

---

## Features

- Data preprocessing
- Handling categorical and numerical features
- Exploratory Data Analysis (EDA)
- Feature encoding
- Machine Learning model training
- Employee attrition prediction
- Interactive Streamlit web application

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Streamlit
- Matplotlib
- Seaborn
- Joblib

---

## Project Structure

```text
HR-Employee-Attrition-Prediction/
│── app.py
│── HR_Attrition_Prediction.ipynb
│── model.pkl
│── requirements.txt
│── README.md
└── WA_Fn-UseC_-HR-Employee-Attrition.csv
```

---

## Environment Setup

Create a virtual environment:

```bash
python -m venv .venv
```

Activate the virtual environment:

### Windows

```bash
.venv\Scripts\activate
```

Install project requirements:

```bash
pip install -r requirements.txt
```

---

## Run the Application

```bash
streamlit run app.py
```

Open the URL provided by Streamlit in your browser.

---

## Model

The trained Machine Learning model is saved as:

```
model.pkl
```

The application loads this model and uses employee information to predict attrition.

---

## Results

The application provides a prediction showing whether an employee is likely to leave the company based on the entered HR information.

---

