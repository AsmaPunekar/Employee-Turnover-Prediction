# 👨‍💼 Employee Turnover Analytics

> **Predicting Employee Attrition Using Machine Learning and Data Analytics**
> **This project is part of Professional Certificate Program in Generative AI and Machine Learning - IITG by Simplilearn Learning platform
**Author:** **Asma I. Punekar**

---

## 📌 Project Overview

Employee turnover is a critical business challenge that impacts organizational productivity, increases recruitment costs, and affects employee morale. This project analyzes historical employee data to identify the key factors contributing to employee attrition and builds machine learning models to predict employees who are at risk of leaving the organization.

The project combines **Exploratory Data Analysis (EDA), Clustering, Classification Models, and Risk Zone Analysis** to provide actionable insights for Human Resources (HR) teams.

---

## 🎯 Project Objectives

* Analyze historical employee data to understand turnover patterns.
* Identify the major factors influencing employee attrition.
* Segment employees into different risk categories based on their likelihood of leaving.
* Build predictive machine learning models for employee attrition.
* Generate actionable recommendations to improve employee retention.

---

## 📊 Dataset Information

**Source:** Company Employee Records

### Features

| Feature                 | Description                                              |
| ----------------------- | -------------------------------------------------------- |
| `satisfaction_level`    | Employee satisfaction score                              |
| `last_evaluation`       | Most recent performance evaluation                       |
| `number_project`        | Number of projects completed                             |
| `average_monthly_hours` | Average monthly working hours                            |
| `time_spend_company`    | Years spent in the company                               |
| `Work_accident`         | Workplace accident indicator                             |
| `promotion_last_5years` | Promotion received in the last five years                |
| `department`            | Employee department                                      |
| `salary`                | Salary category (Low / Medium / High)                    |
| `left`                  | Target variable (1 = Employee Left, 0 = Employee Stayed) |

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* KMeans Clustering
* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier
* Jupyter Notebook

---

## 🔄 Project Workflow

### 1. Data Preprocessing

* Checked for missing values and duplicate records.
* Encoded categorical variables.
* Standardized numerical features.
* Prepared the dataset for machine learning models.

---

### 2. Exploratory Data Analysis (EDA)

Performed comprehensive data exploration to understand employee behavior:

* Distribution of employee satisfaction
* Attrition analysis
* Salary-wise turnover
* Department-wise turnover
* Correlation heatmap
* Feature relationship analysis

---

### 3. Clustering Analysis

Applied **KMeans Clustering** on employees who left the company.

The clustering was performed using:

* Satisfaction Level
* Last Evaluation Score

The clusters helped identify different employee profiles, including:

* High Satisfaction – High Performance
* Low Satisfaction – High Risk
* Moderate Satisfaction – Moderate Risk

---

### 4. Predictive Modeling

The dataset was split into training and testing sets.

The following machine learning algorithms were implemented:

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier

Model performance was evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

### 5. Employee Risk Zone Classification

Employees were categorized into four risk levels based on their predicted probability of leaving.

| Risk Zone      | Description                |
| -------------- | -------------------------- |
| 🟢 Safe Zone   | Low probability of leaving |
| 🟡 Low Risk    | Moderate probability       |
| 🟠 Medium Risk | High probability           |
| 🔴 High Risk   | Very high probability      |

This classification enables HR teams to prioritize retention strategies effectively.

---

## 📈 Key Insights

* Employees with **low satisfaction levels** are significantly more likely to leave.
* Employees working **long hours across multiple projects** show higher attrition rates.
* **Lack of promotions** is strongly associated with employee turnover.
* Employees receiving **low salaries** exhibit higher attrition.
* KMeans clustering revealed distinct employee behavior groups, helping identify high-risk employees.

---

## 💡 Business Recommendations

* Develop targeted retention strategies for high-risk employees.
* Introduce career development and promotion opportunities.
* Balance employee workloads to prevent burnout.
* Offer performance-based incentives and recognition programs.
* Conduct regular employee satisfaction surveys to monitor engagement.


## 🔮 Future Enhancements

* Hyperparameter tuning using GridSearchCV
* Model deployment using Streamlit
* Explainable AI with SHAP and LIME
* Docker containerization
* CI/CD integration with GitHub Actions
* Real-time employee attrition prediction dashboard

---

## 👩‍💻 About the Author

**Asma I. Punekar**

**Data Scientist | Machine Learning | Deep Learning | Generative AI**

I'm passionate about building AI-driven solutions that solve real-world business problems through data analytics, machine learning, and intelligent automation.

---

## ⭐ Support

If you found this project useful, please consider **starring ⭐ the repository** and sharing your feedback.
