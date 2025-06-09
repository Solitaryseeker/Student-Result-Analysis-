# Student Performance Analysis

This repository contains a Jupyter Notebook that analyzes student performance using a dataset with extended features.

## Contents

- `student.ipynb` — Main notebook for data preprocessing, visualization, and analysis.
- `Expanded_data_with_more_features.csv.csv` — The dataset used in the analysis.

## Dataset

The dataset includes various features that may affect student performance, such as demographic information, study time, and family background.

Make sure the dataset file is located in the same directory as the notebook to ensure correct execution.


# 📊 Student Performance Analysis

This project analyzes a dataset of student academic performance using Python and Jupyter Notebook. It explores how various factors such as study time, parental education, internet access, and more affect student grades.

---

## 📁 Files Included

- `student.ipynb` – Jupyter Notebook for data loading, cleaning, analysis, and visualization.
- `Expanded_data_with_more_features.csv.csv` – CSV file containing the student dataset with detailed attributes.

---

## 🎯 Objective

- Explore key factors influencing student academic performance.
- Visualize relationships between student features and grades.
- Optionally predict student outcomes using machine learning models.

---

## 🧠 Dataset Description

The dataset includes features grouped into the following categories:

- **Demographics**: Gender (`sex`), Age (`age`), Address type (`urban` or `rural`)
- **Family & Social**: Parent education, family size, family support, internet access
- **Schooling**: Study time, extra educational support, absences, failures
- **Performance**: Grades in subjects (e.g., `G1`, `G2`, `G3`)

---

## 📊 Data Analysis Process

### 1. Data Import and Overview
- Loaded the dataset using `pandas`
- Used `.head()`, `.info()` and `.describe()` to inspect data

### 2. Data Cleaning
- Checked and handled missing or inconsistent values
- Encoded categorical variables using LabelEncoder or OneHotEncoding

### 3. Exploratory Data Analysis (EDA)
- Analyzed distributions and trends in features
- Used `groupby()` and statistical summaries for feature comparison

### 4. Visualizations – Pie and Bar Charts

#### 🟠 Pie Charts

Used to visualize proportions in categorical features:

- **Gender Distribution**
  ```python
  data['sex'].value_counts().plot.pie(autopct='%1.1f%%', startangle=90)

### Bar Charts
Used to compare categories and their relation to grade 
