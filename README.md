# 💼 Salary Prediction using Multiple Linear Regression

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Regression-orange)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

# 📌 Project Overview

This project focuses on predicting employee salaries using Machine Learning regression techniques.

The primary objective is to compare the performance of:

- Simple Linear Regression (SLR)
- Multiple Linear Regression (MLR)

The project demonstrates how incorporating multiple relevant features improves prediction accuracy and overall model performance.

---

# 🎯 Problem Statement

Employee salary prediction is a real-world regression problem where salary depends on multiple professional factors such as:

- Experience
- Leadership exposure
- Project management experience
- Certifications

This project aims to:

- Build regression models
- Compare model performance
- Analyze evaluation metrics
- Interpret regression coefficients
- Visualize prediction performance

---

# 📂 Dataset Information

The dataset contains the following features:

| Feature | Description |
|---|---|
| Total Experience | Total years of professional experience |
| Team Lead Experience | Years of team leadership experience |
| Project Manager Experience | Years of project management experience |
| Certifications | Number of certifications completed |
| Salary | Target variable |

---

# 🤖 Machine Learning Models Used

## 1️⃣ Simple Linear Regression

Uses only one independent variable to predict salary.

### Formula

$$
Y = \beta_0 + \beta_1 X
$$

---

## 2️⃣ Multiple Linear Regression

Uses multiple independent variables to predict salary.

### Formula

$$
Y = \beta_0 + \beta_1 X_1 + \beta_2 X_2 + \beta_3 X_3 + \cdots + \beta_n X_n
$$

---

# 🛠️ Technologies & Libraries Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# ⚙️ Project Workflow

## 1. Data Collection
- Loaded dataset
- Explored dataset structure

## 2. Data Preprocessing
- Checked missing values
- Feature selection
- Train-test split

## 3. Model Building
- Built Simple Linear Regression model
- Built Multiple Linear Regression model

## 4. Model Evaluation
Compared models using:
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- R² Score

## 5. Visualization
- Regression plots
- Metric comparison charts
- Residual analysis

---

# 📊 Evaluation Metrics

| Metric | Description |
|---|---|
| MSE | Measures average squared prediction error |
| MAE | Measures average absolute prediction error |
| R² Score | Measures goodness of fit |

---

# 📈 Model Performance Comparison

The Multiple Linear Regression model performed better than the Simple Linear Regression model because it achieved:

- Lower Mean Squared Error (MSE)
- Lower Mean Absolute Error (MAE)
- Higher R² Score

This indicates that the Multiple Linear Regression model captured more information from the dataset and produced more accurate salary predictions.

---

# 🧠 Key Learnings

Through this project, the following concepts were explored:

- Regression analysis
- Difference between SLR and MLR
- Model evaluation techniques
- Coefficient interpretation
- Data visualization
- Error analysis
- Git & GitHub workflow

---

# 📷 Sample Visualizations

The project includes:
- Regression line plots
- Residual analysis
- Performance comparison charts

---

# 🚀 Installation & Setup

## Clone Repository

```bash
git clone https://github.com/Sharif-Abusad/salary-prediction-ml.git
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

## Run Jupyter Notebook

```bash
jupyter notebook
```

---

# 📁 Project Structure

```text
salary-prediction-ml/
│
├── Salary_Prediction.ipynb
├── dataset.csv
├── requirements.txt
├── README.md
└── images/
```

---

# 🔮 Future Improvements

Potential enhancements for this project:

- Polynomial Regression
- Regularization Techniques
- Feature Engineering
- Hyperparameter Tuning
- Model Deployment using Flask or Streamlit

---

# ✅ Conclusion

This project successfully demonstrates that Multiple Linear Regression provides better prediction performance compared to Simple Linear Regression by utilizing multiple relevant input features.

The project highlights the importance of:
- Feature selection
- Error analysis
- Visualization
- Model comparison techniques

---

# 👨‍💻 Author

**Sharif Abusad**

If you found this project useful, feel free to ⭐ the repository.
