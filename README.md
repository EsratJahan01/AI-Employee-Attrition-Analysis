# AI-Employee-Attrition-Analysis
A machine learning project to predict employee attrition using the IBM HR dataset. Compares Logistic Regression, Decision Trees, Random Forest and ANN to identify key factors behind employee turnover.
# HR Employee Attrition Prediction

This project uses Machine Learning to predict whether an employee is likely to leave a company (attrition) based on various factors like job satisfaction, income, and work-life balance.

## 📌 Project Overview
Employee turnover is a major cost for companies. This project serves as a proof-of-concept to help HR departments identify "at-risk" employees early using data-driven insights.

## 📊 Dataset
We used the **IBM HR Analytics Employee Attrition & Performance** dataset from Kaggle.
* **Size:** 1,470 records, 35 features.
* **Target:** Binary Classification (Yes/No).

## 🛠️ Tech Stack & Tools
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn, TensorFlow/Keras
* **Visualization:** Matplotlib, Seaborn

## 🤖 Models Compared
We implemented and compared four different models:
1. **Logistic Regression:** 89.12% (Best overall performance)
2. **Artificial Neural Network (ANN):** 89.12%
3. **Random Forest:** 86.39%
4. **Decision Tree:** 76.53%

## 📈 Key Findings
* **Model Choice:** Simple models like Logistic Regression performed best because the dataset features had strong linear relationships.
* **Imbalance Challenge:** Since only ~16% of employees left, the project highlights the importance of looking at **F1-Score and Recall** rather than just Accuracy.
* **Top Factors:** Job satisfaction, overtime, and monthly income are major indicators of attrition.

## 🚀 How to Run
1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`.
3. Run the Jupyter Notebook to see the analysis and results.

---
**Course:** CSE366: Artificial Intelligence  
**Institution:** East West University  
**Project Members:** Fahmida Siraj Adrita, Sejuty Anjum, Fahmida Tabassum, Sabikun Nahar meem, Esrat Jahan Jerin.
