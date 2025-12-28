Investigating the Relationship Between Screen Time and Income Level
📌 **Overview**

Digital technology shapes how individuals work, communicate, and spend leisure time. However, the relationship between socioeconomic status and digital behavior remains underexplored.
This study investigates whether income level is associated with differences in daily screen time, offering insight into how socioeconomic factors influence digital habits and potential behavioral disparities.

By comparing screen time across income groups and applying statistical tests, the project aims to provide a deeper understanding of how socioeconomic status contributes to modern digital lifestyles.

🎯 **Objectives**

This study aims to:

Analyze the relationship between income level and daily screen time.

Determine whether individuals from different income brackets show significantly different digital habits.

Explore whether related well-being indicators (stress, happiness, digital dependence) also vary with income.

Provide a statistically grounded evaluation using ANOVA, post-hoc analysis, and correlation tests.

🧪 Hypotheses
Null Hypothesis (H₀)

Income level has no statistically significant effect on daily screen time.
(Mean screen time is the same across all income groups.)

Alternative Hypothesis (H₁)

Income level has a statistically significant effect on daily screen time.
(At least one income group differs from the others.)

Additional Tests

To strengthen the analysis, the following relationships were also tested:

Screen time vs. stress, happiness, and digital dependence

Income level vs. these psychological variables

Using Pearson correlation, ANOVA, and t-tests

All hypothesis tests were evaluated with a significance threshold of α = 0.05.

📊 **Dataset Description**

The project uses the Digital Lifestyle Benchmark Dataset, consisting of:

Demographics: age, gender, region, income level

Digital Behavior: device hours per day, social media minutes, phone unlocks, notifications

Psychological Indicators: stress, anxiety, depression, happiness, digital dependence

Lifestyle Attributes: sleep hours, physical activity days, daily role

The dataset is large and diverse enough to support socio-behavioral comparisons.

🔧 **Data Preparation**
1. Data Cleaning

Removed missing values for key variables

Filtered unrealistic values (e.g., >18 hours/day screen time)

Ensured categorical consistency for income groups

2. Feature Selection

Key variables used in this project:

device_hours_per_day

income_level

stress_level

happiness_score

digital_dependence_score

social_media_mins

sleep_hours

3. Structuring

Created a cleaned dataframe (df_clean) suitable for EDA and hypothesis testing.

🔍 **Analytical Approach**
Exploratory Data Analysis (EDA)

Visual comparison of screen time across income groups

Boxplots, bar charts, distribution plots

Group statistics for each income category

Correlation analysis with well-being indicators

Statistical Testing

One-way ANOVA to test differences in screen time among 4 income groups

Post-hoc Tukey test to identify which groups differ significantly

Independent t-tests for pairwise comparisons

Pearson correlation to explore broader relationships

⭐ **Key Findings**

Income level is significantly associated with daily screen time (ANOVA p < 0.05), leading to a rejection of the null hypothesis.

Lower-income individuals tended to exhibit higher average screen time, while higher-income individuals showed more balanced usage patterns.

Digital dependence scores were higher among lower-income groups, suggesting potential attachment to devices or digital coping behaviors.

Happiness and stress levels showed variation across income categories, with higher-income individuals reporting slightly higher happiness and lower stress.

Social media minutes and notifications also differed across groups, reflecting distinct behavioral patterns linked to socioeconomic status.

These results indicate that screen time is not solely a behavioral choice, but may be influenced by socioeconomic factors.

🧾 **Conclusion**

The analysis demonstrates a clear relationship between income level and digital behavior, particularly screen time.
Lower-income groups tend to spend more time on devices and report higher digital dependence, while higher-income individuals show lower screen time and more balanced emotional indicators.

This suggests that socioeconomic status contributes to different digital lifestyle patterns, potentially influencing well-being, productivity, and stress.

🚀 **Future Work**

Develop regression models to predict screen time from income and lifestyle factors

Include region or occupation as moderating variables

Expand the dataset with offline social interaction measures

Explore behavioral segmentation using clustering techniques

📌 **Technologies Used**

Python (Pandas, NumPy)

Matplotlib & Seaborn

SciPy (ANOVA, Tukey, Pearson correlation)

Google Colab
