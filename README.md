## Heart Disease Risk Factors: Exploratory Data Analysis (EDA)

### 📚 **Project Overview**

This project explores the **UCI Heart Disease Dataset** to identify critical risk factors associated with heart disease. It aims to derive data-driven health insights by performing **exploratory data analysis (EDA)**, applying **inferential statistical tests**, and creating **visualizations** that reveal significant patterns. The analysis focuses on understanding how variables such as age, gender, resting blood pressure, maximum heart rate achieved, and chest pain type contribute to heart disease risk. This project forms part of a portfolio intended for academic applications in health data science.

---

### 🎯 **Objectives**

* Identify **key risk factors** associated with heart disease.
* Analyze the impact of **age** on heart disease likelihood.
* Assess **gender differences** in heart disease prevalence and risk factors.
* Explore how **chest pain types** correlate with heart disease outcomes.
* Investigate whether **maximum heart rate achieved (thalach)** predicts heart disease.
* Evaluate the role of **resting blood pressure (trestbps)** in heart disease risk.

---

### 🗃️ **Dataset Description**

* **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/45/heart+disease)
* **Records:** 297 patients
* **Key Features:**

  * `age`: Age of the patient
  * `sex`: Gender (1 = male; 0 = female)
  * `cp`: Chest pain type (0–3)
  * `trestbps`: Resting blood pressure (mm Hg)
  * `chol`: Serum cholesterol (mg/dl)
  * `thalach`: Maximum heart rate achieved
  * `target`: Heart disease presence (1 = yes; 0 = no)

---

### 🔍 **EDA Approach & Insights**

#### 1️⃣ **Key Risk Factors Analysis**

* **Approach:** Correlation heatmaps, logistic regression, feature importance analysis.
* **Insight:** Identified **maximum heart rate (thalach)**, **chest pain type**, and **resting blood pressure** as strongly associated with heart disease.

#### 2️⃣ **Age and Heart Disease Risk**

* **Approach:** Age distribution plots, logistic regression.
* **Insight:** Risk spikes observed after **age 50**, with **critical thresholds** around ages **55–60**.

#### 3️⃣ **Gender Differences in Prevalence**

* **Approach:** Grouped bar charts, chi-square tests.
* **Insight:** **Males** showed higher heart disease prevalence; differences in chest pain type distribution were noted across genders.

#### 4️⃣ **Chest Pain Types & Outcomes**

* **Approach:** Stacked bar plots, ANOVA tests.
* **Insight:** **Typical angina (type 1)** showed the **strongest association** with heart disease presence.

#### 5️⃣ **Maximum Heart Rate (Thalach) Analysis**

* **Approach:** Boxplots, scatter plots, correlation analysis.
* **Insight:** Patients with heart disease achieved **lower maximum heart rates**, with a **negative correlation** between thalach and disease presence.

#### 6️⃣ **Resting Blood Pressure (Trestbps) Analysis**

* **Approach:** KDE plots, t-tests.
* **Insight:** **Statistically significant differences** in resting blood pressure levels between groups; higher **trestbps thresholds** correlated with increased heart disease risk.

---

### 🛠️ **Tools & Technologies**

* **Languages:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, SciPy, Statsmodels
* **Techniques:** EDA, hypothesis testing (t-tests, ANOVA), logistic regression, correlation analysis, data visualization

---

### 🖼️ **Key Visualizations**

* **Correlation heatmaps** for feature relationships.
* **KDE plots** comparing blood pressure distributions.
* **Boxplots** for thalach analysis by heart disease status.
* **Stacked bar plots** for chest pain types vs. disease outcomes.
* **Scatter plots** showing thalach vs. heart disease presence.

---

### ⚡ **Project Structure**

```
Heart_Disease_EDA/
│
├── data/                  # Dataset files
├── notebooks/             # Jupyter notebooks with EDA and analysis
├── visualizations/        # Generated plots and charts
├── README.md              # Project overview and documentation
└── requirements.txt       # Dependencies
```

---

### 📊 **Results & Conclusions**

* **Maximum heart rate achieved** and **resting blood pressure** emerged as critical predictors.
* **Gender-specific trends** indicate higher prevalence among **males**, requiring tailored interventions.
* **Chest pain types**, especially **typical angina**, are strongly predictive and warrant early clinical attention.
* **Age-based analysis** suggests **preventive strategies** should intensify after **age 50**.

---

### 🚀 **Next Steps**

* Incorporate **machine learning classification models** (e.g., Logistic Regression, Random Forest) to predict heart disease.
* Perform **cross-validation** to ensure model generalizability.
* Conduct **multivariate analysis** combining top risk factors for deeper clinical insights.

---

### 🤝 **Acknowledgments**

* Dataset provided by the **[UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/45/heart+disease)**.
* Inspired by research efforts in cardiovascular health and disease prevention.

---

### 📬 **Contact**

For inquiries or collaboration opportunities:

* **Email:** [ojotimilehin01@gmail.com](mailto:ojotimilehin01@gmail.com)
* **GitHub:** [GitHub Portfolio](https://github.com/)

---

### 🌟 **Why This Project Matters**

Understanding heart disease risk factors is vital for **early detection**, **personalized treatments**, and **healthcare planning**. This project showcases the integration of **data science techniques** with **healthcare insights**, demonstrating readiness for advanced studies in **health data science**.

---

### 📄 **License**

This project is open-source and available under the **MIT License**.

---

### 🎓 **Author**

*Ojo Timilehin*
*Data Science | Healthcare Insights | EDA Expert*
**Email:** [ojotimilehin01@gmail.com](mailto:ojotimilehin01@gmail.com)

---

*"Turning healthcare data into actionable insights for better outcomes."*

Thank you
