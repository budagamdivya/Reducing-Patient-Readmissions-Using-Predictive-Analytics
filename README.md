
# 🏥 Reducing Patient Readmissions Using Predictive Analytics

## 📌 Project Overview
Hospital readmissions are costly and often preventable. In this project, I analyzed over 100,000 patient records from U.S. hospitals to identify key drivers of 30-day readmissions. Using predictive modeling and data visualization, I aimed to help healthcare organizations proactively reduce readmission rates and improve patient outcomes.

## 📊 Objective
- Identify the most common patterns among patients who are readmitted within 30 days.
- Predict the likelihood of patient readmission using logistic regression.
- Provide actionable insights through visual dashboards to support hospital decision-making.

## 🧰 Tools & Technologies
- **Python** (Pandas, Seaborn, Scikit-learn, Matplotlib)
- **Power BI** / Tableau for dashboard
- **Jupyter Notebook** / VS Code
- **CSV dataset**: Diabetic patient hospital visits (130+ U.S. hospitals, 1999–2008)

## 🧹 Data Cleaning Summary
- Dropped irrelevant columns (e.g., `encounter_id`, `payer_code`)
- Removed rows with missing gender or race
- Converted target variable: `readmitted` → 1 = `<30 days`, 0 = otherwise
- Label encoded categorical variables
- Final dataset: ~70,000 cleaned records


## 📈 Exploratory Data Analysis (EDA)
- Most patients **are not readmitted**, but a small high-risk segment exists.
- Readmissions are more frequent in **older age groups (60–80)**.
- Features like **number of medications**, **time in hospital**, and **inpatient visits** showed strong correlation with readmissions.


## 🤖 Predictive Modeling
- **Model Used**: Logistic Regression
- **Accuracy**: 89%
- **Top Predictive Features**:
  - Number of inpatient visits
  - Number of medications
  - Discharge disposition
- Evaluated with confusion matrix and classification report

## Dashboards Creation 
https://app.sigmacomputing.com/pace-university/workbook/workbook-5MAJJpDuuQQgP3Mxl4xumI?:link_source=share



## 📌 Key Takeaways
- Proactively targeting high-risk groups (elderly, multiple hospital visits) can reduce costs and improve outcomes.
- Hospitals can implement alert systems based on predictive scores.
- Logistic regression provides explainability + actionable insights for clinical teams.

- ## 🙋‍♀️ Author
**Sai Divya Sree Budagam**  
Aspiring Business/Data Analyst | Passionate about using analytics to improve patient outcomes  

