# 🧹 Data Wrangling: Handling Missing Values in Survey Data

## 📌 Overview

This project focuses on **data cleaning and preprocessing**, specifically identifying and handling missing values in a survey dataset. The notebook demonstrates practical techniques used in real-world data analysis workflows.

The dataset consists of survey responses related to **employment status, remote work, and other respondent attributes**, and is used to explore how missing data can impact analysis.

---

## 📊 Dataset Description

* **Type:** Survey dataset
* **Format:** CSV (`survey-data.csv`)
* **Structure:** Tabular (rows = respondents, columns = features)
* **Content:** Employment information, remote work status, and related variables

Each row represents an individual respondent, while each column corresponds to a survey question or attribute.

---

## 🧹 Data Wrangling Tasks Performed

### 🔍 1. Missing Value Detection

* Checked for null values using Pandas (`isnull()` and `sum()`)
* Identified columns with high missing rates

### 📊 2. Missing Data Visualization

* Used heatmaps (Seaborn) to visualize missing patterns
* Gained insight into how missing values are distributed across features

### 🛠 3. Data Cleaning / Imputation

* Applied **mode imputation** for categorical variables (e.g., `Employment`)
* Replaced missing values with the most frequent category
* Ensured dataset consistency for further analysis

---

## 🧠 Key Learnings

* Importance of handling missing data before analysis
* Different strategies for imputing categorical data
* Visual tools can reveal patterns not obvious in raw data
* Data quality directly affects analytical outcomes

---

## 🛠 Technologies Used

* **Python**
* **Pandas** – data manipulation
* **NumPy** – numerical operations
* **Seaborn & Matplotlib** – data visualization

---

## 📁 Project Structure

```
.
├── Finding Missing Values Data Wrangling.ipynb
├── survey-data.csv (external source)
└── README.md
```

---

## 🚀 How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/data-wrangling-missing-values.git
   ```
2. Open the notebook:

   ```bash
   cd data-wrangling-missing-values
   jupyter notebook
   ```
3. Run all cells to reproduce the analysis

---

## 🎯 Use Case

This project is ideal for:

* Beginners learning **data preprocessing**
* Students practicing **data wrangling techniques**
* Analysts preparing datasets for **machine learning or visualization**

---

## 📌 Future Improvements

* Apply advanced imputation methods (e.g., KNN, regression)
* Perform exploratory data analysis (EDA)
* Build predictive models using cleaned data

---

## 👤 Author

**Genesis Adriel Segovia**

---

## 📄 License

This project is for educational purposes.
