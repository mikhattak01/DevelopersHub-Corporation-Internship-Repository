 # DevelopersHub-Corporation-Internship-Repository

# 📊 Data Science Internship Portfolio

A collection of data science projects completed during my internship, demonstrating skills in exploratory data analysis, machine learning, and business insights generation.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## 📁 Projects Overview

| # | Project | Objective | Dataset Size | Best Model | Key Metric |
|---|---------|-----------|--------------|------------|------------|
| 1 | Iris Species Analysis | Exploratory Data Analysis | 150 samples | EDA Visualization | Clear species separation |
| 2 | Credit Risk Prediction | Predict loan defaulters | 252,000 samples | Random Forest | 59.3% Recall |
| 3 | Loan Acceptance Prediction | Identify likely acceptors | 45,211 samples | Decision Tree | 83.8% Accuracy |

---

## 🌸 Task 1: Iris Species Analysis

### Objective
Perform exploratory data analysis to understand species characteristics and identify distinguishing features among iris flower species.

### Dataset
- **Iris Dataset** (Seaborn built-in / UCI)
- 150 samples, 4 features, 3 species

### Summary
- **Setosa** has small petals and wide sepals - completely distinct from other species
- **Versicolor** shows intermediate petal size
- **Virginica** has the largest petals (longest and widest)
- **Petal measurements** separate species better than sepal measurements
- No outliers detected - dataset is clean and well-behaved

### Key Skills Demonstrated
- Data loading with pandas
- Summary statistics generation
- Scatter plots, histograms, and box plots
- Pattern identification through visualization

---

## 💳 Task 2: Credit Risk Prediction

### Objective
Predict whether a loan applicant is likely to default, helping financial institutions make informed lending decisions.

### Dataset
- **Loan Prediction Dataset** (Kaggle)
- 252,000 loan applications, 12 features
- Target: Risk_Flag (12.3% default rate - imbalanced)

### Summary
- **Best Model**: Random Forest Classifier
- **Recall**: 59.3% (catches nearly 60% of defaulters)
- **AUC-ROC**: 0.758 (good discriminatory power)
- **Top Risk Factors**: Income, City, Age, Profession, Experience
- Business impact: Saves millions in potential default losses annually

### Key Skills Demonstrated
- Handling imbalanced datasets
- Binary classification (Logistic Regression, Decision Tree, Random Forest)
- Confusion matrix analysis
- Feature importance extraction
- Business impact calculation

---

## 📞 Task 3: Personal Loan Acceptance Prediction

### Objective
Identify which customers are most likely to accept a personal loan offer, enabling targeted marketing campaigns.

### Dataset
- **Bank Marketing Dataset** (UCI)
- 45,211 bank customers, 17 features
- Target: Loan acceptance (11.7% acceptance rate)

### Summary
- **Best Model**: Decision Tree (best interpretability for business)
- **Accuracy**: 83.8%
- **Key Predictors**: Contact method (35%), Month (23%), Days since last contact (18%)
- **Best Customers**: Previous campaign successes (64.7% acceptance), Students (35.3%), Retired (22.8%)
- **Customers to Avoid**: Blue-collar workers (7.3%), Entrepreneurs (8.3%)

### Key Skills Demonstrated
- Customer segmentation analysis
- Categorical data encoding
- Correlation analysis
- Business insight extraction
- Marketing campaign optimization

---

## 📈 Key Learnings

### Technical Skills Gained
- ✅ Data cleaning and preprocessing
- ✅ Handling missing values and outliers
- ✅ Exploratory Data Analysis (EDA)
- ✅ Feature engineering and selection
- ✅ Binary classification with imbalanced data
- ✅ Model evaluation (confusion matrix, precision, recall, F1, AUC-ROC)
- ✅ Business impact analysis

### Tools Mastered
- **Pandas** - Data manipulation
- **NumPy** - Numerical operations
- **Matplotlib & Seaborn** - Visualization
- **Scikit-learn** - Machine learning models

### Business Insights
- Credit risk models need high recall (catching defaulters) more than high accuracy
- Customer segmentation improves marketing ROI significantly
- Simple models (Decision Trees) can be more interpretable for business stakeholders
- Class imbalance is common in real-world banking data

---

# 📁 Repository Structure

DEVELOPERSHUB CORPORATION PRACTICE GIT REPO/
│
├── 📓 Task 1.ipynb # Iris Species Analysis (EDA)
├── 📓 Task 2.ipynb # Credit Risk Prediction
├── 📓 Task 5.ipynb # Loan Acceptance Prediction
│
├── 📊 Datasets/
│ ├── Iris.csv # Iris flower dataset
│ ├── Loan Prediction.csv # Credit risk dataset
│ └── bank-full.csv # Bank marketing dataset
│
├── 📈 credit_risk_report.png # Visual report for Task 2
└── 📖 README.md # This file

---

# 📝 Conclusion

This internship portfolio demonstrates proficiency in:

- Data Analysis: Extracting meaningful insights from raw data.
- Machine Learning: Building and evaluating classification models.
- Business Communication: Translating technical results into actionable recommendations.

All three tasks showcase the complete data science workflow from data exploration to model deployment recommendations.

---

# 🤝 Connect With Me

![LinkedIn](www.linkedin.com/in/mazhar-iqbal-khattak)
![GitHub](https://github.com/mikhattak01)

---