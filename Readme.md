<h1 align="center">Cardiovascular Disease (CVD) Prediction Project</h1>
<p align="center">Health Analytics • Exploratory Data Analysis • Predictive Modeling • Tableau Visualization</p>

---

##  Project Overview

Cardiovascular diseases (CVDs) are among the leading causes of death worldwide.  
To reduce mortality, it is critical to understand the factors contributing to heart attacks and build predictive models that can detect high-risk individuals early.

This project performs:

- End-to-end data cleaning  
- Exploratory Data Analysis (EDA)  
- Statistical insights  
- Predictive modeling (Logistic Regression)  
- Interactive Tableau Dashboard creation  

The dataset contains **14 attributes** and **4000+ records** related to heart health indicators.

---

##  Problem Statement

A healthcare organization wants to investigate the factors influencing cardiovascular disease and create a predictive model to identify patients at high risk of heart attacks.

With a dataset containing 14 cardiovascular-related variables, the goal is to:

- Study and examine the most impactful features  
- Understand patterns that differentiate healthy vs. diseased individuals  
- Build a model to predict heart attack risk  
- Create dashboards to visualize key health indicators  

---

##  Project Files

| File | Description |
|------|-------------|
| `data.csv` | Main heart disease dataset |
| `preprocessing.ipynb` | Python notebook for data cleaning & EDA |
| `modeling.ipynb` | Logistic regression modeling & evaluation |
| `dashboard.twbx` | Tableau dashboard for CVD insights |
| `README.md` | Documentation |

*(Replace with actual file names.)*

---

##  Tools & Technologies

| Category | Tools |
|----------|-------|
| Programming | Python (Pandas, NumPy) |
| Visualization | Matplotlib, Seaborn |
| Modeling | Logistic Regression |
| Dashboard | Tableau |
| Development | Jupyter Notebook |

---

##  1. Data Importing, Understanding & Inspection

### ✔ Preliminary Inspection
Performed initial checks on:
- Shape of dataset  
- Data types of each attribute  
- Summary of columns  
- Missing values and duplicates  

### ✔ Data Cleaning
- Removed duplicate entries  
- Treated missing data using appropriate strategies (mean/median/mode for numeric; mode for categorical)  
- Standardized column names for readability  

### ✔ Statistical Summary
- Generated descriptive statistics for all numerical columns  
- Analyzed central tendency and variability  

---

## 2. Exploratory Data Analysis (EDA)

### 2.1 Categorical Variable Analysis
- Identified categorical variables (e.g., gender, chest pain type, fasting blood sugar, exercise-induced angina, thalassemia)  
- Visualized frequency counts using **count plots**

###  2.2 CVD Across Age Groups
- Analyzed how age affects probability of heart disease  
- Explored age distribution of diseased vs. healthy patients  

### 2.3 Resting Blood Pressure
- Studied relationship between **anomalous resting BP** and heart attack occurrence  
- Visualized BP trends among patients

###  2.4 Gender Distribution
- Examined gender composition of the dataset  
- Compared CVD occurrence in males vs. females  

---

## 3. EDA + Modeling Insights

###  3.1 Cholesterol Levels
- Analyzed cholesterol distribution  
- Detected patterns in cholesterol values among diseased vs. healthy patients  

###  3.2 Peak Exercise (Max Heart Rate / ST Depression)
- Studied effect of peak exercise indicators on CVD  
- Explored whether high exercise stress correlates with heart attack risk  

###  3.3 Thalassemia & Other Key Factors
- Investigated whether **thalassemia** is a major CVD determinant  
- Compared influence of:
  - chest pain type  
  - fasting blood sugar  
  - resting ECG results  
  - exercise-induced angina  
  - slope of ST segment  
  - number of major vessels  

###  3.4 Pair Plot Visualization
- Used pair plots to observe relationships between all variables  
- Checked variable separation patterns  

---

##  4. Predictive Modeling

Performed logistic regression modeling:

### Modeling Workflow:
1. Data preprocessing & encoding  
2. Scaling numerical variables  
3. Train-test split  
4. Training logistic regression model  
5. Predicting outcomes on test data  
6. Evaluating model using:
   - Confusion matrix  
   - Accuracy  
   - Recall & Precision  

---

##  Dashboarding in Tableau

Created dashboards to visualize:

- Distribution of diseased vs. healthy patients  
- Age, gender, and cholesterol patterns  
- Blood pressure vs. CVD occurrence  
- Exercise-related indicators  
- Thalassemia, fasting blood sugar & ECG effects  

### Dashboard Goals:
- Help clinicians explore critical health variables  
- Provide a clear visual difference between **Healthy vs. Diseased** individuals  
- Highlight risk factors useful in predictive modeling



