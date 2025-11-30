# 📱 Digital Lifestyle Analysis  
### Investigating the Relationship Between Screen Time and Social Interaction Indicators

## 📌 Overview
Digital devices have become a central part of everyday life, shaping how people communicate, socialize, and manage their routines. Although increased screen time offers convenience and online connectivity, its effects on real-world social interaction and emotional well-being are not fully understood.

This project analyzes the relationship between **daily screen time** and **social-interaction–related indicators**, including social media usage, stress, happiness, and digital dependence. The goal is to determine whether heavier screen usage is linked to reduced well-being or behavioral changes.

---

## 🎯 Objectives
This study aims to:

- Examine the relationship between daily screen time and social interaction indicators.  
- Investigate whether increased screen time is associated with reduced emotional well-being.  
- Identify behavioral patterns related to digital habits.  
- Analyze how lifestyle metrics (stress, anxiety, happiness, sleep) vary across different screen time levels.

---

## 🧪 Hypotheses

### **Null Hypothesis (H₀)**
There is **no statistically significant correlation** between daily screen time and any of the social-interaction–related or emotional well-being indicators  
(social media usage, stress, happiness, digital dependence).

### **Alternative Hypothesis (H₁)**
There **is** a statistically significant correlation between daily screen time and at least one of these indicators.

Hypothesis testing was conducted using **Pearson correlation coefficients** and **p-values (α = 0.05)**.

---

## 📊 Dataset Description
The project uses the **Digital Lifestyle Benchmark Dataset**, which includes:

- Demographic data (age, gender, region, income level)  
- Behavioral metrics (device hours per day, social media minutes, notifications, phone unlocks)  
- Psychological indicators (stress, anxiety, depression, happiness, digital dependence)  
- Lifestyle factors (sleep duration, physical activity)

The dataset is publicly available and ideal for behavioral and digital well-being analysis.

---

## 🔧 Data Preparation

### **1. Data Cleaning**
- Removed missing values from key variables  
- Filtered unrealistic values (e.g., >18 hours of screen time)  
- Ensured consistent data types for numerical fields  

### **2. Feature Selection**
The core features used:

- `device_hours_per_day`
- `social_media_mins`
- `stress_level`
- `anxiety_score`
- `depression_score`
- `happiness_score`
- `digital_dependence_score`
- `sleep_hours`

### **3. Structuring**
A cleaned dataframe (`df_clean`) was created for EDA and hypothesis testing.

---

## 🔍 Analytical Approach

### **Exploratory Data Analysis (EDA)**
- Distribution plots for all major variables  
- Scatter plots comparing screen time with social media usage  
- Correlation matrix and heatmap  
- Screen-time-based group comparisons (0–2h, 2–4h, 4–6h, …, 10+h)

### **Statistical Testing**
- Pearson correlation (r-values)  
- p-values to determine statistical significance  
- Hypothesis evaluation based on α = 0.05 threshold  

---

## ⭐ Key Findings

- **Screen time and social media usage showed a positive correlation**, meaning heavier device users spend more time on social media.  
- **Digital dependence increased sharply** among individuals with higher daily device usage.  
- **Stress and anxiety levels showed mild positive correlations** with screen time.  
- **Happiness scores decreased slightly** as screen time increased.  
- Users in the **10+ hours/day** group displayed the highest levels of social media use, notifications, and digital dependence.  
- Several relationships were statistically **significant (p < 0.05)**, providing evidence to **reject the null hypothesis**.

---

## 🧾 Conclusion
The analysis shows that daily screen time is meaningfully related to behavioral and emotional metrics. Higher screen time is associated with increased social media engagement, higher stress, and stronger digital dependence, alongside a slight reduction in happiness levels.

These findings suggest that heavy digital consumption may influence both social interaction patterns and emotional well-being.

---

## 🚀 Future Work
- Predictive modeling (e.g., regression) to forecast digital dependence  
- Expanding analysis with additional behavioral variables  
- Comparing weekday vs. weekend digital behavior  
- Including offline social interaction metrics if available  

---

## 📌 Technologies Used
- Python (Pandas, NumPy)  
- Matplotlib  
- SciPy (Pearson correlation)  
- Google Colab  

