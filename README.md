**📱 Digital Lifestyle Analysis
Screen Time, Income Level, and Well-Being Indicators
📌 Overview**

Digital devices play an essential role in modern daily life, but not everyone interacts with them in the same way. This project investigates how daily screen time relates to income level and explores how screen usage is connected to psychological and lifestyle indicators such as stress, happiness, digital dependence, sleep duration, and social media usage.

The goal is to understand whether socioeconomic status affects digital behavior and whether heavy screen time corresponds to meaningful differences in well-being.

🎯 **Objectives**

This study aims to:

Determine whether daily screen time differs across income levels

Explore relationships between screen time and:

stress

happiness

digital dependence

sleep hours

social media usage

Present comprehensive EDA (scatter plots, boxplots, heatmaps, correlations)

Apply formal statistical tests (ANOVA and Pearson correlation)

Provide data-driven insights using a publicly available digital lifestyle dataset

🧪 **Hypotheses**
Main Hypothesis: Income Level → Screen Time

Null Hypothesis (H₀):
Income level has no statistically significant effect on daily screen time
(all income groups have the same mean screen time).

Alternative Hypothesis (H₁):
Income level has a significant effect on daily screen time.

Additional Hypothesis: Income Level → Digital Dependence

H₀: Income level has no effect on digital dependence.

H₁: Income level significantly affects digital dependence.

Correlation Hypotheses (Screen Time vs. Well-Being Indicators)

For each variable:

H₀: There is no linear relationship with screen time.

H₁: There is a significant linear relationship with screen time.

All tests use α = 0.05.

**📊 Dataset Description**

This project uses the Digital Lifestyle Benchmark Dataset, which includes:

Demographics: age, gender, region, income level

Digital behavior: device hours per day, social media minutes, phone unlocks, notifications

Psychological indicators: stress, anxiety, depression, happiness, digital dependence

Lifestyle factors: sleep hours, physical activity days, daily role

The dataset provides a rich basis for exploring both digital usage and its psychological context.

**🔧 Data Preparation**
1. Cleaning

Removed rows with missing values in key variables

Restricted screen time to the realistic 0–18 hour range

Created a cleaned dataframe (df_clean) for analysis

2. Selected Variables

device_hours_per_day

income_level

stress_level

happiness_score

digital_dependence_score

social_media_mins

sleep_hours

**🔍 Analytical Approach**
Exploratory Data Analysis (EDA)

The notebook includes:

Screen time distribution (histogram)

Income level distribution (countplot)

Average screen time per income group (bar plot)

Boxplots comparing screen time across income groups

Scatter plots comparing screen time with:

stress

happiness

digital dependence

social media minutes

sleep hours

A correlation matrix and heatmap

**Statistical Testing**
1. ANOVA — Income Level → Screen Time

Used to test whether income groups differ in mean daily screen time.

2. ANOVA — Income Level → Digital Dependence

Tests whether socioeconomic status affects digital dependency.

3. Pearson Correlations

Between screen time and:

stress

happiness

digital dependence

social media minutes

sleep hours

Each includes correlation coefficients and p-values.

**🧮 Key Results**
⭐ 1. Income Level and Screen Time (ANOVA)

F-statistic: 2.56

p-value: 0.053

**📌 Interpretation:**

Since p > 0.05, we fail to reject H₀.

The effect is borderline (marginal) → a weak trend exists, but not statistically conclusive.

⭐ 2. Income Level and Digital Dependence (ANOVA)

F-statistic: 2.29

p-value: 0.076

**📌 Interpretation:**

p > 0.05, so no significant effect of income level on digital dependence.

The p-value suggests a weak, emerging trend, but not enough for significance.

⭐ 3. Correlation Analysis (Screen Time vs. Well-Being)

Stress: slight positive relationship

Happiness: slight negative relationship

Digital dependence: strong positive tendency

Sleep hours: mild negative trend

Social media minutes: positive, but weaker than expected

Several correlations had significant p-values (p < 0.05), indicating non-random relationships.

**📌 Summary Insight:**
Heavier screen users tend to show higher stress, higher digital dependence, lower happiness, and slightly reduced sleep duration.

🧾 Conclusion

This project shows that:

Income level does not significantly influence daily screen time, though the relationship is marginal

Income level also does not significantly influence digital dependence, but a weak trend appears

Screen time is more strongly related to psychological indicators than to socioeconomic status

Heavy screen usage corresponds to higher stress, stronger digital dependence, and slightly lower happiness

Overall, digital lifestyle patterns are influenced more by behavioral and emotional factors than by income alone.

**🚀 Future Work**

Potential extensions:

Regression models to predict stress or digital dependence

Weekday vs. weekend screen time comparison

Interaction effects (such as income × age)

Cluster analysis to find digital lifestyle segments

🛠️ **Technologies Used**

Python

Pandas, NumPy

Matplotlib & Seaborn

SciPy (ANOVA + Pearson correlation)

Google Colab
