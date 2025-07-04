# 🚢 Task 02: Titanic Survival Prediction  
**SkillCraft Data Science Internship**

## 📌 Objective
The goal of this task is to analyze the Titanic dataset and build machine learning models to predict whether a passenger survived the disaster. The task demonstrates data preprocessing, exploratory data analysis (EDA), and the application of classification algorithms.

---

## 🧠 Data Science Concepts Applied

### 1. Data Cleaning & Preprocessing
- Handled missing values (`Age`, `Cabin`, `Embarked`)
- Converted categorical features (`Sex`, `Embarked`, `Pclass`) using **Label Encoding** and **One-Hot Encoding**
- Dropped irrelevant or sparse columns like `Cabin`, `Ticket`, and `Name`

### 2. Exploratory Data Analysis (EDA)
- Analyzed the impact of features like gender, class, and age on survival
- Visualized key distributions using:
  - Countplots (`Survival` by `Sex`, `Pclass`, etc.)
  - Boxplots (`Age` distribution across classes and survival status)
  - Heatmaps (correlation matrix)

### 3. Feature Engineering
- Created `FamilySize` by combining `SibSp` and `Parch`
- Extracted `Title` from `Name` (optional)

### 4. Supervised Machine Learning
- Applied multiple classification algorithms:
  - **Logistic Regression**
  - **K-Nearest Neighbors (KNN)**
  - **Decision Tree Classifier**
- Compared performance using accuracy and classification reports

### 5. Model Evaluation
- Used the following metrics:
  - Accuracy Score
  - Confusion Matrix
  - Precision, Recall, and F1 Score

---

## 📁 Files Included

| File Name | Description |
|----------|-------------|
| `Task02_Titanic_Survival_Analysis.ipynb` | Jupyter Notebook with full implementation |
| `titanic.csv` | Cleaned Titanic dataset used for analysis |
| `README.md` | This documentation file |

---

## 🛠️ Libraries Used
```python
pandas
numpy
matplotlib
seaborn
scikit-learn
