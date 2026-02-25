# 🛠️ Feature Engineering in Machine Learning

This repository contains practical notebooks and code for **Feature Engineering** techniques used in real-world Machine Learning projects.

Feature Engineering ka main goal hota hai:
➡️ raw data ko meaningful, clean aur model-ready banana.

---

## 📌 What is Feature Engineering?

Feature engineering is the process of:
- new features banana add New features 
- useless features remove karna
- data ko transform karna
taaki machine learning model better performance de sake.

---

## 📂 Topics Covered

### 1️⃣ Handling Missing Values
- Mean / Median Imputation
- Mode Imputation
- Forward Fill / Backward Fill
- SimpleImputer

---

### 2️⃣ Categorical Encoding

- Label Encoding
- One Hot Encoding
- get_dummies()

---

### 3️⃣ Feature Scaling

- Standard Scaling
- Min Max Scaling
- Robust Scaling

---

### 4️⃣ Outlier Treatment

- IQR Method
- Z-score Method
- Capping / Flooring

---

### 5️⃣ Feature Transformation

- Log Transformation
- Square Root Transformation
- Power Transformation

---

### 6️⃣ Date & Time Features

- Extract year, month, day
- Extract weekday
- Weekend feature

---

### 7️⃣ Feature Creation

- New column creation
- Mathematical combinations
- Business logic based features

---

### 8️⃣ Binning / Discretization

- Equal width binning
- Equal frequency binning
- pd.cut()
- pd.qcut()

---

### 9️⃣ Feature Selection

- Correlation based filtering
- Variance Threshold
- SelectKBest
- Model based feature importance

---

### 🔟 Handling High Cardinality

- Rare label grouping
- Frequency encoding

---

## 🧠 Why Feature Engineering is Important?

- Model accuracy will be improve
- Overfitting will be decrease 
- Model will be more stable
- And it will be get the minumum time.
- Real-world data ke liye mandatory hota hai

---

## 🧪 Tools & Libraries Used

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

---

## 📝 Example

```python
import pandas as pd
from sklearn.preprocessing import StandardScaler

scaler = StandardScaler()
df[['age','salary']] = scaler.fit_transform(df[['age','salary']])
