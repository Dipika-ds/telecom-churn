# Telecom Customer Churn Prediction

## 📌 Overview
This project analyzes customer churn in the telecom industry and builds a predictive model to identify high‑risk customers. The goal is to provide actionable insights that help businesses reduce churn and improve customer retention.

- **Problem:** ~25–30% of customers discontinue service, leading to revenue loss.
- **Solution:** Logistic Regression model to predict churn and highlight key drivers.
- **Tools:** Python, Pandas, Seaborn, Scikit‑Learn, Matplotlib

---

## ⚙️ Workflow
1. **Data Loading & Cleaning**
   - Converted `TotalCharges` to numeric and handled missing values.
   - Standardized target variable `Churn` (Yes → 1, No → 0).

2. **Exploratory Data Analysis (EDA)**
   - Visualized churn distribution.
   - Analyzed churn by contract type, tenure, and monthly charges.
   - Identified patterns in customer behavior.

3. **Modeling**
   - Preprocessed numeric features (scaling) and categorical features (one‑hot encoding).
   - Trained Logistic Regression with balanced class weights.
   - Evaluated using Accuracy, ROC‑AUC, Confusion Matrix, and Classification Report.

4. **Insights**
   - Month‑to‑month contracts → highest churn risk.
   - Short tenure → higher churn probability.
   - High monthly charges → churn more likely.
   - Long‑term contracts and bundled services (e.g., Tech Support) reduce churn.

---

## 📊 Results
- **Accuracy:** ~80%  
- **ROC‑AUC:** ~0.82  
- **Key Drivers:** Contract type, tenure, monthly charges, support services.  

Visualizations include:
- Churn distribution
- Churn by contract type
- Tenure vs churn
- Monthly charges vs churn
- Confusion matrix & ROC curve

---

## 📊 Evaluation Metrics

The model’s performance metrics are saved in `figures/metrics.json` for reproducibility.

Accuracy: ~80%

ROC‑AUC: ~0.82

Churn Rate: ~26%

These values confirm that the logistic regression model provides strong predictive power while remaining interpretable.

---

## 💡 Business Recommendations
- Offer loyalty discounts to month‑to‑month customers.
- Provide onboarding support for new customers (short tenure).
- Target high‑charge customers with personalized retention offers.
- Promote long‑term contracts and bundled service packages.

---

## 📂 Repository Structure

 
   telecom_churn/
   
   │── data/                # Dataset (Telco Customer Churn CSV)
   
   │── notebooks/           # Jupyter notebook (Telecom_Churn.ipynb)
   
   │── figures/             # Plots and evaluation metrics
   
   │── models/              # Saved logistic regression model
   
   │── README.md            # Project documentation
   
   │── requirements.txt     # Python dependencies



---

## 🚀 Next Steps
- Add cross‑validation and hyperparameter tuning.
- Compare with tree‑based models (Random Forest, XGBoost).
- Use SHAP values for explainable AI insights.
- Deploy as a simple web app for real‑time churn prediction.

---

## 👩‍💻 Author
**Dipika Chandra**  
- IIT ISM Postgraduate | Ex‑Ericsson Senior Solution Integrator  
- Skills: Python, SQL, Power BI, Machine Learning, Data Visualization  
- [LinkedIn](https://linkedin.com/in/dipika-chandra26a1a71a0) | [GitHub](https://github.com/your‑repo)
