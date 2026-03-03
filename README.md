# Lab 4: Data Quality Assessment & Preprocessing

## Dataset Used
Wine Dataset (Different dataset as required)

## Author
Abbas Aziz

---

## Project Overview
This project applies data quality assessment and preprocessing techniques on the Wine dataset.  
The goal is to identify data issues, clean the data, normalize features, and apply dimensionality reduction.

---

## Tasks Implemented

### 1️⃣ Data Quality Assessment
- Checked data types
- Verified missing values
- Checked duplicate records
- Dataset contains 178 rows and 13 numerical features
- No original missing values were found

---

### 2️⃣ Handling Missing Values
- Artificially introduced 2% missing values
- Applied **Median Imputation**
- Median was chosen because it is robust to outliers

---

### 3️⃣ Outlier Detection
- Used the **IQR (Interquartile Range) method**
- Removed extreme values
- Dataset size reduced from 178 to 154 rows

---

### 4️⃣ Normalization
Applied two normalization techniques:
- Min-Max Scaling
- Z-score Standardization

This ensures all features are on comparable scales.

---

### 5️⃣ PCA (Dimensionality Reduction)
- Applied PCA to reduce dimensionality
- Explained variance ratio shows how much variance is captured by principal components

---

## Conclusion
The dataset was successfully cleaned, normalized, and transformed.
Preprocessing improves data quality and prepares it for machine learning tasks.

---

## Tools Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook
