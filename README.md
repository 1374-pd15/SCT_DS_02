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
| `SCT_DS_02.ipynb` | Jupyter Notebook with full implementation |
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

🔍 Key Findings
Gender was a major determinant: women had a much higher survival rate.

Passenger Class (Pclass) showed a clear trend: survival was higher in 1st class.

Age mattered — children and young adults had better chances.

Passengers with larger families had lower survival rates.

📊 Visual Samples
Sample Visuals Created:

sns.countplot(x='Survived', hue='Sex')

sns.boxplot(x='Pclass', y='Age', hue='Survived')

sns.heatmap(df.corr(), annot=True)

These helped explain which features contributed most to survival, allowing us to choose the most relevant ones for training our models.

✅ Conclusion
This task provided a well-rounded experience in:

Cleaning and preparing real-world data

Performing impactful visual analysis

Building and evaluating multiple classification models

It was a strong reinforcement of the core data science workflow, especially in dealing with classic binary classification problems.


