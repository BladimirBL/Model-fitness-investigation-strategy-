# 🏋️ Model Fitness — Customer Churn Analysis

> Machine Learning project focused on identifying customer churn patterns in a fitness chain by analyzing user behavior and activity data. The goal is to define churn indicators and propose data-driven customer retention strategies.

---

## 🛠️ Tools & Technologies

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

---

## 📫 Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bladimir-andres-hernandez-a1764a2b7)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:bladimir4hernandez@gmail.com)

---

## 📌 Project Overview

**Model Fitness** is a gym chain looking to develop a data-driven customer interaction strategy. One of the biggest challenges in the fitness industry is customer churn — losing members who stop attending or cancel their memberships.

This project uses **Machine Learning** to predict which customers are likely to churn, segment them into behavioral clusters, and generate actionable retention recommendations.

---

## 🎯 Key Questions Answered

- Which customer profiles are most likely to cancel their membership?
- What behavioral and demographic factors correlate most with churn?
- Can we predict churn before it happens using classification models?
- How can customers be segmented into meaningful groups for targeted retention strategies?

---

## 🔍 Methodology

```
1. Exploratory Data Analysis (EDA)
   - Distribution analysis of churned vs. retained customers
   - Feature correlation heatmap
   - Histograms by churn group

2. Predictive Modeling (Classification)
   - Logistic Regression
   - Random Forest Classifier
   - Model evaluation: Accuracy, Precision, Recall
   - Train/test split with StandardScaler

3. Customer Clustering (Unsupervised Learning)
   - Hierarchical Clustering (Dendrogram)
   - K-Means Clustering (5 clusters)
   - Churn rate analysis per cluster

4. Conclusions & Retention Recommendations
```

---

## 📊 Key Findings & Conclusions

### 🔴 Churn Risk Factors
- **New customers** have the highest churn risk — they leave due to lack of support and guidance during their early weeks.
- Customers with **low group visit frequency** are significantly more likely to cancel.
- **Contract length** is a strong churn predictor — short-term members churn at much higher rates.

### 🤖 Predictive Models
- Both **Logistic Regression** and **Random Forest** achieved strong performance in predicting churn.
- The Random Forest model captured non-linear relationships between features more effectively.
- Key predictors included: contract duration, visit frequency, age, and group activity participation.

### 👥 Customer Clusters (K-Means, k=5)
- **5 distinct customer segments** were identified with significantly different churn rates.
- High-risk clusters showed low engagement, short contracts, and minimal social interaction.
- Low-risk clusters were characterized by long-term contracts, frequent visits, and group participation.

### 💡 Retention Recommendations
1. **Prioritize onboarding** — New members need personalized guidance and follow-up to build the habit.
2. **Promote group activities** — Many customers join gyms for social interaction; group classes increase retention.
3. **Reward loyal customers** — Long-term members should receive incentives to maintain their loyalty.
4. **Early churn detection** — Monitor engagement signals and proactively reach out to at-risk customers before they cancel.

---

## 📁 Project Structure

```
📦 model-fitness-churn-analysis
 ┣ 📓 Model_Fitness_Investigation_strategy.ipynb   # Main notebook
 ┗ 📄 README.md
```

---

⭐ *If you found this project useful, feel free to leave a star!*
