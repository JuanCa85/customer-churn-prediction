# 📊 Customer Churn Prediction (92% Accuracy)

Built a machine learning model to predict customer churn with 92% accuracy, identifying key behavioral drivers and enabling targeted retention strategies to reduce revenue loss.

---

## ⚡ TL;DR

- Built a churn prediction model with **92% accuracy**
- Identified key drivers of customer churn
- Provided actionable recommendations to improve retention

![Status](https://img.shields.io/badge/Status-Completed-success)
![Model](https://img.shields.io/badge/Model-RandomForest-blue)
![Accuracy](https://img.shields.io/badge/Accuracy-92%25-brightgreen)

---

## 📌 Project Overview

End-to-end machine learning project focused on predicting customer churn and translating data into actionable business insights.

---

## 🚀 Business Problem

Customer churn represents a critical challenge for businesses, directly impacting revenue and growth.

The objective of this project was to identify customers at risk of leaving and uncover the key behavioral patterns driving churn.

---

## 🎯 Objective

- Predict customer churn using machine learning
- Identify high-risk customer segments
- Generate actionable insights to improve retention
  
### 💡 Key Takeaway

Customer engagement and tenure are the strongest predictors of churn, suggesting that early-stage customer experience and continuous interaction are critical for retention.

---

## 💼 Business Impact

This model enables businesses to:

- Identify high-risk customers before churn occurs
- Focus retention efforts on the most vulnerable segments
- Improve customer lifetime value through targeted strategies

If implemented, this approach can significantly reduce churn rates and protect revenue streams.

This approach helps organizations move from reactive to proactive customer retention strategies. 

### 🔍 Key Drivers of Churn

The model identified the most important features influencing churn, including:

- Customer tenure
- Usage frequency
- Service engagement

These variables play a critical role in predicting customer behavior.

---

## 🧠 Approach

1. Data Cleaning & Preprocessing  
   - Handled missing values  
   - Encoded categorical variables  
   - Normalized numerical features  

2. Exploratory Data Analysis (EDA)  
   - Analyzed churn distribution  
   - Identified correlations and trends  

3. Model Development  
   - Logistic Regression  
   - Random Forest  
   - Model comparison and tuning  

4. Model Evaluation  
   - Accuracy  
   - Precision / Recall  
   - Confusion Matrix  

---

## 📈 Key Insights

- **Lifetime is the strongest churn predictor** (correlation: -0.374) — churned customers had an average tenure of **1.0 months** vs **4.7 months** for retained customers
- **Contract length is critical** — customers on short-term contracts churn at significantly higher rates; average contract period for churned customers was **1.7 months** vs **5.7 months** for retained
- **Low class frequency signals risk** — churned customers attended **1.4 classes/month** on average vs **2.1** for retained customers
- **Additional charges reflect engagement** — retained customers generated **$158 in additional charges** vs **$115** for churned customers, suggesting higher overall engagement
---

## 🏆 Results

- ✅ **Random Forest** outperformed Logistic Regression across all metrics on a dataset of 4,000 gym membership records
- ✅ **92% accuracy** | **84% precision** | **82% recall** on the churn class
- ✅ Identified **5 distinct customer segments** with churn rates ranging from **5.4% to 35.8%**
- ✅ High-risk cluster (Cluster 4) churns at **3.5x the rate** of the most loyal segment (Cluster 3)

---

## 🧩 Recommendations

- **Target Cluster 4 immediately** — intervene within the first month with onboarding programs and engagement incentives
- **Promote long-term contracts** — customers on 6–12 month contracts show dramatically lower churn; offer discounts for upgrades
- **Monitor class attendance frequency** — flag customers dropping below 1.5 classes/month for proactive outreach
- **Early engagement is key** — the first 30 days are the most critical window for retention 

---

## 💼 Business Impact

This model can help companies:

- Proactively target customers at risk  
- Optimize retention campaigns  
- Reduce revenue loss due to churn  

---

## 🛠 Tools & Technologies

- Python (Pandas, NumPy)
- Scikit-learn (Machine Learning)
- Data Visualization (Matplotlib / Seaborn)
- Jupyter Notebook

---

## 📷 Visualizations

These visualizations summarize key findings and model performance:

### Churn Distribution
![Churn Distribution](https://github.com/JC-Insights/customer-churn-prediction/blob/main/images/churn_distribution.png)

Top variables driving churn prediction, highlighting the importance of customer engagement and tenure.

### Feature Importance
![Feature Importance](https://github.com/JC-Insights/customer-churn-prediction/blob/main/images/feature_importance.png)

### Model Performance
![Model Performance](https://github.com/JC-Insights/customer-churn-prediction/blob/main/images/model_performance.png)

The model shows strong performance in correctly identifying both churned and retained customers, with minimal misclassification.

---

## ▶️ How to Run

Clone the repository:

```bash
git clone https://github.com/your-username/customer-churn-prediction.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the notebook:

```bash
jupyter notebook
```

---

## 📁 Project Structure

│  
├── data/   
├── notebooks/   
├── src/  
├── images/  
└── README.md  

---

## 📬 Contact

LinkedIn: https://linkedin.com/in/juan-carlos-vm/  
GitHub: https://github.com/JuanCa85

---

## 📌 Author

Juan Carlos Vértiz Millán  
Data Analyst | Python • SQL • Power BI
