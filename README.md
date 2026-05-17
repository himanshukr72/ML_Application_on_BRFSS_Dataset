# ML_Application_on_BRFSS_Dataset
# BRFSS Health Risk & Disease Prediction Analysis

## Overview

This project focuses on exploratory data analysis, feature engineering, and disease risk prediction using the **Behavioral Risk Factor Surveillance System (BRFSS)** dataset. The analysis aims to identify major lifestyle, demographic, and health-related factors associated with chronic diseases using machine learning and statistical analysis techniques.

The project utilizes the **2015 BRFSS Dataset**, a large-scale health survey dataset collected by the Centers for Disease Control and Prevention (CDC). The dataset contains self-reported information regarding health conditions, lifestyle habits, demographics, and preventive health practices from adults across the United States.

The notebook includes:

* Data preprocessing and cleaning
* Missing value analysis
* Exploratory Data Analysis (EDA)
* Correlation analysis
* Disease prevalence visualization
* Feature selection
* Machine learning model building
* Performance evaluation using classification metrics

---

# Dataset Information

## BRFSS Dataset

The project is implemented using the **BRFSS (Behavioral Risk Factor Surveillance System)** dataset.

### About BRFSS

The Behavioral Risk Factor Surveillance System is one of the world's largest continuously conducted health surveys. It is administered annually by the CDC to collect information about:

* Chronic health conditions
* Behavioral risk factors
* Preventive health practices
* Lifestyle habits
* Mental and physical health indicators

### Dataset Used

* **Year:** 2015
* **Source:** CDC BRFSS Public Health Dataset
* **Data Type:** Structured survey dataset
* **Format:** CSV

### Key Features Used

The project includes demographic and health-related attributes such as:

| Feature    | Description               |
| ---------- | ------------------------- |
| `_AGE80`   | Age group                 |
| `SEX`      | Gender                    |
| `_BMI5`    | Body Mass Index           |
| `SMOKE100` | Smoking history           |
| `_SMOKER3` | Smoking status            |
| `DRNKANY5` | Alcohol consumption       |
| `_TOTINDA` | Physical activity         |
| `HLTHPLN1` | Health insurance coverage |
| `CHECKUP1` | Medical checkup frequency |
| `SLEPTIM1` | Sleep duration            |
| `MENTHLTH` | Mental health status      |
| `PHYSHLTH` | Physical health status    |

### Disease Variables Analyzed

The project investigates several chronic diseases and conditions:

* Heart Attack (`CVDINFR4`)
* Coronary Heart Disease (`CVDCRHD4`)
* Stroke (`CVDSTRK3`)
* Skin Cancer (`CHCSCNCR`)
* Other Cancer (`CHCOCNCR`)
* COPD (`CHCCOPD1`)
* Arthritis (`HAVARTH3`)
* Depression (`ADDEPEV2`)
* Kidney Disease (`CHCKIDNY`)
* Diabetes (`DIABETE3`)
* Asthma (`ASTHMA3`)

---

# Project Workflow

## 1. Data Collection

The BRFSS 2015 survey dataset is loaded using Pandas and sampled for efficient analysis.

## 2. Data Preprocessing

Data cleaning operations include:

* Handling missing values
* Selecting important variables
* Mapping categorical disease labels
* Filtering relevant health indicators

## 3. Exploratory Data Analysis

EDA techniques used in this project:

* Missing value visualization
* Statistical summaries
* Disease prevalence analysis
* Correlation heatmaps
* Distribution analysis
* Comparative visualizations

## 4. Feature Engineering

Important demographic and lifestyle variables are selected to study disease relationships and predictive behavior.

## 5. Machine Learning

Machine learning algorithms are applied to predict disease occurrence using selected risk factors.

### Algorithms Used

* Random Forest Classifier

### Evaluation Metrics

* Accuracy
* Confusion Matrix
* ROC-AUC Score
* Classification Report

---

# Technologies & Libraries Used

## Programming Language

* Python

## Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Missingno
* Scikit-learn

---

# Visualizations Included

The project contains several visual and statistical analyses such as:

* Missing data plots
* Correlation heatmaps
* Disease prevalence charts
* Age distribution analysis
* Comparative health-risk visualizations

These visualizations help understand patterns between lifestyle behaviors and chronic diseases.

---

# Objectives of the Project

The primary objectives of this project are:

1. Analyze public health trends using BRFSS data.
2. Identify important risk factors associated with chronic diseases.
3. Study relationships between lifestyle behaviors and health conditions.
4. Build predictive models for disease classification.
5. Visualize disease prevalence and health indicators.

---

# Project Structure

```bash
├── Project.ipynb
├── README.md
├── dataset/
│   └── 2015.csv
├── visualizations/
├── outputs/
└── requirements.txt
```

---

# How to Run the Project

## Clone the Repository

```bash
git clone https://github.com/your-username/your-repository-name.git
cd your-repository-name
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

## Run the Notebook

```bash
jupyter notebook
```

Open the notebook and execute the cells sequentially.

---

# Results & Insights

The analysis demonstrates that factors such as:

* Smoking habits
* Obesity (BMI)
* Physical inactivity
* Poor mental health
* Sleep duration
* Age

have strong associations with multiple chronic diseases.

The machine learning model successfully identifies patterns in health-related behavior and disease occurrence using BRFSS survey data.

---

# Future Improvements

Potential future enhancements include:

* Applying deep learning models
* Multi-disease prediction systems
* Real-time health risk dashboards
* Advanced feature selection techniques
* Handling class imbalance using SMOTE
* Cross-validation and hyperparameter tuning

---

# Applications

This project can be useful for:

* Public health research
* Disease surveillance
* Preventive healthcare systems
* Healthcare analytics
* Medical data science projects
* Academic research and dissertations

