# 🏥 Healthcare Data Cleaning & Exploratory Data Analysis (EDA) in Python

> Transforming messy healthcare records into reliable, analysis-ready data to support better healthcare operations, patient management, and business decision-making.

---

## 📌 Project Overview

Healthcare organizations often struggle with inconsistent patient records, missing values, duplicate entries, incorrect data formats, and unstructured billing information. Poor data quality can lead to inaccurate reporting and ineffective decision-making.

This project demonstrates a complete **Healthcare Data Cleaning and Exploratory Data Analysis (EDA)** workflow using Python. The objective was to improve data quality, prepare the dataset for analysis, and uncover meaningful insights related to patient demographics, medical conditions, hospital admissions, and billing patterns.

---

## 📂 Dataset Description

The dataset contains patient-level healthcare records with demographic, medical, admission, and billing information.

### Key Attributes

| Column             | Description                        |
| ------------------ | ---------------------------------- |
| Patient ID         | Unique identifier for each patient |
| Name               | Patient name                       |
| Age                | Patient age                        |
| Gender             | Gender information                 |
| Blood Type         | Blood group of the patient         |
| Medical Condition  | Diagnosed medical condition        |
| Date of Admission  | Hospital admission date            |
| Discharge Date     | Patient discharge date             |
| Doctor             | Assigned doctor                    |
| Hospital           | Hospital name                      |
| Insurance Provider | Insurance company information      |
| Billing Amount     | Total treatment cost               |
| Admission Type     | Emergency, Urgent, Elective, etc.  |
| Medication         | Prescribed medication              |
| Test Results       | Diagnostic test outcomes           |

---

## ⚙️ Key Features & Workflow

### 🧹 1. Data Cleaning

The dataset underwent multiple preprocessing and quality improvement steps:

#### ✅ Missing Value Treatment

* Identified missing values across columns
* Imputed missing numerical values using median-based techniques
* Ensured minimal information loss

#### ✅ Duplicate Record Handling

* Detected duplicate patient records
* Removed duplicate entries to improve reporting accuracy

#### ✅ Data Type Corrections

* Converted admission and discharge dates into proper datetime format
* Standardized numerical fields for analysis

#### ✅ Data Standardization

* Cleaned categorical values
* Corrected inconsistent gender labels
* Removed extra spaces and formatting issues

#### ✅ Billing Data Cleaning

* Removed currency symbols and unwanted characters
* Converted billing amounts to numeric format

#### ✅ Outlier Detection & Treatment

* Applied IQR (Interquartile Range) method
* Identified extreme billing values
* Used outlier capping instead of deletion to preserve valid healthcare records

#### ✅ Feature Engineering

Created new analytical features such as:

* Length of Stay
* Admission Month
* Age Groups

---

### 📊 2. Exploratory Data Analysis (EDA)

Several analyses were performed to understand patient behavior, healthcare trends, and billing patterns.

#### 👥 Patient Demographics Analysis

* Age distribution
* Gender distribution
* Age group segmentation

#### 🩺 Medical Condition Analysis

* Disease prevalence
* Medical condition frequency
* Gender vs medical condition comparison

#### 🏥 Admission Analysis

* Admission type distribution
* Monthly admission trends
* Patient admission patterns

#### 💰 Financial & Billing Analysis

* Average billing amount by medical condition
* Billing amount by admission type
* Detection of billing anomalies

#### 📅 Length of Stay Analysis

* Calculated hospital stay duration
* Compared stay duration across patient groups

#### 📈 Visualizations Created

* Histograms
* Boxplots
* Countplots
* Pie Charts
* Bar Charts
* Line Charts
* Crosstab Analysis

---

## 🛠️ Tech Stack

### Programming Language

* Python

### Libraries Used

* Pandas
* NumPy
* Matplotlib
* Seaborn

### Development Environment

* Jupyter Notebook

### Techniques Applied

* Data Cleaning
* Data Validation
* Feature Engineering
* Outlier Detection (IQR Method)
* Exploratory Data Analysis (EDA)
* Data Visualization

---

## 📈 Key Insights & Findings

### Insight 1

* Certain medical conditions generated significantly higher average billing amounts than others.

### Insight 2

* Specific age groups showed higher hospital admission rates, indicating potential healthcare risk segments.

### Insight 3

* Emergency admissions were associated with higher treatment costs compared to planned admissions.

### Insight 4

* Outlier analysis revealed unusually high billing records that required further investigation.

---

## 💡 Business Impact

This project demonstrates how effective data cleaning can:

* Improve healthcare data reliability
* Reduce reporting inconsistencies
* Support operational planning
* Enable accurate KPI reporting
* Improve patient and billing analytics
* Assist healthcare management in data-driven decision-making

---

## 🚀 Future Work

### 📊 Interactive Dashboard

Build a Power BI or Tableau dashboard to visualize healthcare KPIs in real time.

### 🤖 Predictive Analytics

* Length of Stay
* Readmission Risk
* Treatment Costs

### 📈 Advanced Healthcare Analytics

Perform:

* Patient segmentation
* Disease trend forecasting
* Insurance claim analysis

---

## 📷 Sample Analysis Areas

✔ Data Quality Assessment

✔ Missing Value Handling

✔ Duplicate Removal

✔ Outlier Detection

✔ Patient Demographics

✔ Disease Analysis

✔ Admission Trends

✔ Billing Analysis

✔ Length of Stay Analysis
