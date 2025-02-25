# 📊 Exploratory Data Analysis (EDA) on COVID-19 Dataset

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on a COVID-19 dataset to uncover key insights about patient outcomes, including **death rates, ICU admission, intubation, and comorbidities**. The analysis aims to understand how different factors impact patient survival and COVID-19 severity.

## 🛠️ Tools & Technologies Used
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **Jupyter Notebook / Google Colab**
- **Git & GitHub**

## 🏆 Key Findings
- **Older people** were the most affected in terms of **positive cases and death count**.
- **Patients with pneumonia** had a **higher probability of infection and death**.
- **ICU admission & intubation** significantly increased the risk of death (intubated patients had a **75% mortality rate**).
- **Comorbidities** such as **diabetes, hypertension, and cardiovascular diseases** were strongly correlated with mortality.
- **Younger patients (<40 years old)** had a significantly lower **death rate**.

## 📊 Data Preprocessing & Cleaning
✔ Handled missing values.  
✔ Removed irrelevant columns.   
✔ Checked for **missingness patterns** to assess potential biases.

## 📉 Data Visualization & Analysis
We used **Seaborn and Matplotlib** for effective data visualization:
- **Bar plots** to compare death counts by conditions.
- **Heatmaps** to show correlations between variables.
- **Box plots** for distribution of age and death rate.
- **Histograms** for patient age distribution.

## 📌 System Architecture
```
[Dataset] → [Data Cleaning] → [EDA] → [Visualizations] → [Insights]
```

## 🔮 Future Scope
- **Build a predictive model** to classify high-risk patients.
- **Time-series analysis** of COVID-19 cases and deaths.
- **Develop a dashboard** for healthcare professionals.

## 📥 Dataset
The dataset used in this analysis can be found on **Kaggle**: [COVID-19 Dataset](https://www.kaggle.com/datasets/meirnizri/covid19-dataset)

---
⭐ **If you find this project useful, give it a star on GitHub!** ⭐
