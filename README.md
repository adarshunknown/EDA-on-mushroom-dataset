# EDA-on-mushroom-dataset
This project performs a comprehensive **Exploratory Data Analysis (EDA)** on the Mushroom dataset. The dataset consists of descriptions of hypothetical mushroom species, categorized as **edible** or **poisonous** based on physical attributes.

---

## 📁 File

- `eda on mushroom.ipynb` — Jupyter notebook containing all EDA steps and visualizations.

---

## 📦 Dataset Description

Each record in the dataset represents a mushroom, with categorical features such as:

- `cap-shape`, `cap-color`, `gill-size`, `gill-color`, `stalk-shape`, `odor`, etc.
- The target variable is `class`:  
  - `e` = edible  
  - `p` = poisonous

The dataset contains **only categorical variables**.

---

## 📊 EDA Overview

The EDA is divided into three major stages:

### 1️⃣ Univariate Analysis
- Count plots for each categorical feature
- Distribution of `edible` vs `poisonous` classes
- Frequency of individual feature values

### 2️⃣ Bivariate Analysis
- Relationship between features and the target variable
- Chi-square-based feature importance
- Visualizations using bar plots and stacked plots

### 3️⃣ Multivariate Analysis
- Correlation heatmaps (with encoded data)
- Pairplots for selected feature sets
- Multicollinearity checks

---

## 🧪 Techniques & Tools Used

- `pandas`, `numpy` for data manipulation
- `matplotlib`, `seaborn` for plotting
- `LabelEncoder` for encoding categorical variables
- Chi-square tests for feature relevance

---

## 📌 Key Insights

- Features like `odor`, `gill-color`, and `spore-print-color` are highly discriminative between edible and poisonous mushrooms.
- Some features show perfect separation — potentially useful for decision-tree-based models.
- No significant missing data in the dataset.


