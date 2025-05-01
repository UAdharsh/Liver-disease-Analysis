# Liver Patient Dataset Analysis using PCA

This project demonstrates **dimensionality reduction** and **data visualization** techniques using **Principal Component Analysis (PCA)** on the Indian Liver Patient Dataset (ILPD). It also includes preprocessing steps such as handling missing values, scaling, outlier detection, normalization of skewed features, and visualization using scatter and scree plots.

---

## 📊 Features of This Project

- Load and preprocess real-world liver disease data
- Handle missing values and categorical data
- Detect and remove outliers using the IQR method
- Normalize highly skewed features using log transformation
- Standardize features for PCA
- Apply PCA to reduce dimensions while retaining variance
- Visualize:
  - 2D scatter plot of PCA results
  - Scree plot to analyze explained variance
- Analyze feature contributions to each principal component

---

## 🧪 Dataset

The Indian Liver Patient Dataset (ILPD) contains records of liver patients and healthy individuals. The original dataset includes features such as:

- Age, Gender
- Bilirubin levels
- Enzyme levels
- Protein counts
- Diagnosis (Liver disease or not)

> You must place the dataset file as `liver_patient_data.csv` in the project directory.

---

## 🛠️ Requirements

- Python 3.7+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Install dependencies using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
