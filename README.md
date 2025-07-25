# 🚦 PRODIGY_DS_05 - US Accidents Data Analysis

This repository contains the solution for Task 5 of the **Prodigy InfoTech Data Science Internship**. The task focuses on analyzing a real-world dataset of US traffic accidents to uncover patterns and insights using data cleaning, preprocessing, and visualization techniques.

---

## 📥 Dataset

- **Source**: [US Accidents (Kaggle)](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents)
- **Description**: A comprehensive dataset of over 7 million US accident records from February 2016 to Present, including weather, time, and location details.
- **Download**: You can download the dataset from [here](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents)

---

## 📌 Objectives

- Understand the dataset and identify missing/irrelevant columns.
- Handle missing values smartly using techniques like mean/mode imputation.
- Perform exploratory data analysis (EDA) with visualizations.
- Gain insights into accident severity, time-based trends, and weather influence.

---

## 🧹 Data Preprocessing

- Removed unnecessary columns such as: `ID`, `Source`, `Description`, `Street`, `Country`, etc.
- Dropped columns with excessive nulls: `Sunrise_Sunset`, `Nautical_Twilight`, `Civil_Twilight`, etc.
- Converted `Start_Time` & `End_Time` to `datetime`, extracted features like Hour, Day, Month.
- Filled missing `Humidity` with **mean** and categorical fields like `Wind_Direction`, `Timezone` with **mode**.

---

## 📊 Exploratory Data Analysis (EDA)

- **Severity Distribution**: Visualized to understand the impact level (1: Least to 4: Most Severe).
- **Time-based Trends**:
  - Peak accident hours (7–9 AM and 4–7 PM).
  - Monthly and weekday patterns.
- **Geographic Trends**:
  - States with the highest accidents: **California**, **Florida**, **Texas**.
- **Weather Factors**:
  - Influence of humidity, temperature, visibility, etc.

---

## 📌 Technologies Used

- **Python**
- **Jupyter Notebook**
- **Libraries**:
  - `pandas`, `numpy` – Data manipulation
  - `matplotlib`, `seaborn` – Visualization

---

