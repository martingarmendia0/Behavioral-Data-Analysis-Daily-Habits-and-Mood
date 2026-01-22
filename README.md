# Behavioral Data Analysis: Daily Habits and Mood

## Repository Description

This project explores the relationship between daily habits and emotional well-being using behavioral data. Through exploratory data analysis (EDA), the notebook examines how screen time, physical activity, sleep, and social interaction are associated with mood and stress levels. The focus is on generating interpretable insights rather than building complex predictive models.

The project is designed as an **entry-level / junior Data Analyst portfolio piece**, emphasizing clear methodology, thoughtful interpretation, and responsible use of data.

---

## Project Objectives

* Analyze daily behavioral habits and their relationship with mood and stress.
* Apply exploratory data analysis techniques to uncover patterns and trends.
* Visualize relationships using Matplotlib.
* Practice feature engineering with a clearly defined target variable.
* Communicate insights with appropriate scientific and ethical caution.

---

## Dataset

* **Type:** Synthetic (simulated) dataset
* **Structure:** Longitudinal daily records per user
* **Key variables:**

  * Screen time (hours)
  * Physical activity (minutes)
  * Sleep duration (hours)
  * Social interaction score
  * Mood score (1–10)
  * Stress level (1–10)

The dataset was intentionally generated to reflect realistic behavioral patterns while avoiding the use of sensitive or real personal data.

---

## Methodology

1. **Data Generation & Loading**
   Creation of a structured synthetic dataset with realistic distributions and noise.

2. **Exploratory Data Analysis (EDA)**

   * Descriptive statistics using Pandas
   * Visual analysis using Matplotlib
   * Examination of distributions, scatter plots, and correlations

3. **Correlation Analysis**
   Identification of relationships between habits, mood, and stress, with careful interpretation.

4. **Feature Engineering**
   Construction of a binary variable (`low_mood`) to represent risk of low emotional well-being.

---

## Key Insights

* Physical activity and sleep show a positive association with mood.
* Higher screen time tends to be weakly associated with lower mood and higher stress.
* Stress level is negatively correlated with mood.
* Emotional well-being appears to be influenced by multiple interacting habits rather than a single factor.

---

## Limitations

* The data is synthetically generated and may not capture all real-world complexities.
* Mood and stress are treated as self-reported variables.
* Correlation does not imply causation.
* Results should be interpreted as exploratory rather than diagnostic or predictive.

---

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook

---

## Ethical Considerations

This project avoids real personal data and does not aim to diagnose or predict mental health conditions. The analysis is exploratory and educational, focusing on responsible interpretation of behavioral data.

---

## Author

Martín Garmendia
Psychologist | Data Analytics & Data Science Student

---

## Notes

This repository is part of a personal portfolio intended to demonstrate data analysis skills at an entry-level/junior standard, with an emphasis on clarity, interpretability, and methodological rigor.
