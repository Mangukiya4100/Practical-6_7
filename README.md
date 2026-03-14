# Practical 6_7 – Data Analytics Task

## Student Information

* **Name:** Khilan Mangukiya
* **Enrollment Number:** 2054070500026
* **Subject:** Data Analytics Techniques (DAT)
* **Task:** Practical 6_7

---

# Objective

To implement **data storage, data integration, and pattern discovery** on a dataset related to mobile usage, sleep duration, and stress levels using Python in Google Colab.

---

# Dataset

**File:** `sleep_mobile_stress_dataset_15000.csv`

### Features

* user_id
* age
* gender
* occupation
* daily_screen_time_hours
* phone_usage_before_sleep_minutes
* sleep_duration_hours
* sleep_quality_score
* stress_level
* caffeine_intake_cups
* physical_activity_minutes
* notifications_received_per_day
* mental_fatigue_score

---

# Tools & Technologies

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* SQLite

---

# Implementation Steps

## 1. Data Storage

The processed dataset was stored in multiple formats:

* CSV file
* Excel file
* SQLite database

This allows efficient storage and retrieval of data for analysis.

---

## 2. Data Integration

Multiple attributes were combined to create new meaningful features:

* **Digital Behavior Index**
  Combines screen time, phone usage before sleep, and notifications.

* **Lifestyle Score**
  Combines sleep duration and physical activity.

* **Stress Risk Score**
  Combines stress level, mental fatigue, and digital behavior.

These integrated attributes help improve analysis.

---

## 3. Pattern Discovery

Different techniques were applied to discover patterns in the dataset.

### Correlation Analysis

A correlation matrix was used to identify relationships between variables such as:

* Screen time vs stress level
* Sleep duration vs mental fatigue

### Clustering (K-Means)

Users were grouped into clusters based on behavioral features such as:

* Screen time
* Sleep duration
* Stress level
* Physical activity

This helped identify different user behavior patterns.

---

# Results

* High screen time is associated with higher stress and fatigue.
* Lower sleep duration leads to increased mental fatigue.
* Users were successfully grouped into behavioral clusters using K-Means clustering.

---

# Outcome

The practical successfully implemented **data storage, integration, and pattern discovery techniques** to analyze the relationship between mobile usage, sleep habits, and stress levels.

---

# Repository Structure

```
Practical-6-7
│
├── sleep_mobile_stress_dataset_15000.csv
├── practical_6_7_colab.ipynb
└── README.md
```

---

# Conclusion

This practical demonstrated the complete **data analytics workflow**, including storing datasets, integrating multiple attributes, and discovering meaningful patterns from the data using clustering and statistical analysis.
