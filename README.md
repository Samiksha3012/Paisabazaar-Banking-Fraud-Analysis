# PaisaBazaar Credit Risk Analysis & Prediction

An end-to-end data analytics and machine learning project to analyze customer credit behavior, identify potential risk patterns, and predict credit score categories using Python, Scikit-learn, and Power BI.

## 🎯 Project Objectives
- Analyze customer financial profiles and credit behavior.
- Identify factors associated with credit scores.
- Classify customers into Good, Standard, and Poor credit score categories.
- Present credit risk indicators through a Power BI dashboard.

## 🔄 Project Workflow

1. **Data Loading:** Load the customer credit dataset.
2. **Data Cleaning:** Handle missing values, inconsistent categories, and data types.
3. **Exploratory Data Analysis:** Examine credit scores, income, debt, loan patterns, and payment behavior.
4. **Feature Engineering:** Prepare numerical and categorical features for modeling.
5. **Model Training:** Train Decision Tree and Random Forest classifiers.
6. **Hyperparameter Tuning:** Apply GridSearchCV and stratified cross-validation.
7. **Model Evaluation:** Compare models using accuracy and macro F1-score.
8. **Dashboard Development:** Build a Power BI dashboard to visualize credit risk indicators and analytical findings.

## 🔍 Key Insights
- Higher annual income tends to be associated with better credit scores.
- Outstanding debt and credit utilization help reveal potential credit risk patterns.
- Customers aged 14–18 show an unusual concentration of unspecified loan types, warranting further investigation into data quality and record validity.
- Standard credit scores form the largest customer segment in the analyzed dataset.

## 🤖 Machine Learning Models

- Decision Tree Classifier
- Random Forest Classifier
- GridSearchCV for hyperparameter tuning

### Random Forest Performance

| Metric | Score |
|---|---:|
| Test Accuracy | **82.00%** |
| Macro F1-score | **81.19%** |

Random Forest outperformed the Decision Tree models in the reported test results.

## 🛠️ Technologies Used

- Python, Pandas, NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab
- Microsoft Power BI

## 🚀 How to Run

1. Open the notebooks in Jupyter Notebook or Google Colab.
2. Configure the dataset paths.
3. Run `Paisabaar credit risk EDA.ipynb`.
4. Run `Predictive Models.ipynb` to train and evaluate the models.

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

*Note: The dataset is not included in this repository. Update the dataset paths before running the notebooks.*

## 📌 Conclusion

This project combines exploratory data analysis, machine learning, and business intelligence to investigate customer credit behavior, identify potential risk indicators, and support data-driven credit risk assessment.

---

## 📊 Power BI Dashboard

Developed a completed Power BI dashboard to visualize credit risk indicators and customer financial behavior.

**Key dashboard features:**
- Credit utilization ratio and outstanding debt
- Good credit score and delayed customer percentages
- Loan-type and credit mix analysis
- High-risk customer rankings
- Monthly credit utilization trends
- Credit inquiries across age groups
