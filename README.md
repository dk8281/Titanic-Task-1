# Titanic-Task-1
# 🚢 Task 1: Data Cleaning & Preprocessing - Titanic Dataset

## 📌 Objective

The goal of this task is to clean and preprocess the Titanic dataset to prepare it for machine learning models. This includes handling missing values, encoding categorical variables, removing outliers, and scaling numerical features.

---

## 🧰 Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🧪 Steps Performed

### 1. Data Exploration
- Loaded the dataset using `pandas`.
- Checked data types, null values, and summary statistics using `.info()`, `.describe()`, and `.isnull().sum()`.

### 2. Handling Missing Values
- Filled missing values in `Age` with the **median**.
- Filled missing values in `Embarked` with the **mode**.
- Dropped the `Cabin` column due to too many missing values.

### 3. Encoding Categorical Variables
- Converted `Sex` into numerical using **label encoding** (`male`=0, `female`=1).
- Applied **one-hot encoding** to `Embarked` (with `drop_first=True` to avoid dummy variable trap).

### 4. Outlier Detection & Removal
- Used **boxplots** to visualize outliers in the `Fare` column.
- Removed outliers in `Fare` beyond the **99th percentile**.

### 5. Feature Scaling
- Standardized the `Age` and `Fare` columns using **StandardScaler** from `sklearn`.

---

## 📊 Visualizations

- Boxplot for Fare outlier detection
- Missing value summary

---

## 📁 Files in Repository

- `Titanic-Dataset.csv` – Dataset used.
- `titanic_preprocessing.py` or `.ipynb` – Main code file.
- `README.md` – This file, explains the task.


---

## 📚 What I Learned

- How to clean and preprocess real-world data.
- The importance of handling missing values appropriately.
- Difference between label encoding and one-hot encoding.
- How to detect and remove outliers.
- When and why to apply feature scaling.

---

