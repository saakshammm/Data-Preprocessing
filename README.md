# 🚢 Titanic Dataset - Data Cleaning & Preprocessing

This project is part of my machine learning journey. It involves cleaning, preprocessing, and preparing the Titanic dataset for training ML models.

---

## 📁 Files Included

| File Name              | Description                                       |
|------------------------|---------------------------------------------------|
| `Titanic-Dataset.csv`  | Original raw dataset                              |
| `cleaned_data.csv`     | Dataset after dropping unnecessary columns and filling out the missing values  |
| `Cleaning.ipynb`       | Notebook for data cleaning and basic inspection   |
| `Pre-processing.ipynb` | Notebook for preprocessing: imputation, encoding, scaling, outlier removal |

---

## ✅ Preprocessing Pipeline

1. **Import Dataset & Inspect**
   - Loaded the Titanic dataset
   - Checked for null values and data types

2. **Handle Missing Values**
   - Filled missing values using `SimpleImputer` (mean strategy)

3. **Encode Categorical Variables**
   - Used `OneHotEncoder` via `ColumnTransformer` to convert categorical columns

4. **Normalize/Standardize Numerical Data**
   - Applied either `StandardScaler` or `MinMaxScaler` from Scikit-learn

5. **Outlier Detection & Removal**
   - Visualized using boxplots
   - Removed outliers using IQR method

---

## 🛠️ Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `sklearn`

---

## 🙌 Credits

This project was created as part of my learning process. Feel free to suggest improvements or fork it for your own learning.

