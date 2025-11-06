# AICW_PoweBI_Student_Performance_and_Analysis

# 🎓 Student Performance Analysis in Power BI

## 📘 Project Overview

This project focuses on analyzing **student performance data** using **Power BI**. The interactive dashboard provides insights into students’ scores in Math, Reading, and Writing and examines how demographic and socio-economic factors such as **gender**, **ethnicity**, **parental education**, and **test preparation** influence their academic outcomes.

---

## 🎯 Problem Statement

Educational institutions often struggle to identify key factors influencing student performance. The dataset contains individual student details, including test scores and demographic information, but meaningful insights are not easily visible.

As a **Data Analyst**, your goal is to:

1. Analyze students' average scores across subjects.
2. Understand performance variations by gender, ethnicity, and parental education.
3. Evaluate the impact of test preparation on performance.
4. Provide an interactive dashboard for educators and management to explore performance trends.

---

## 🧠 Objectives

* Measure overall academic performance by subject and total average.
* Compare scores between demographic groups (Gender, Ethnicity, Parental Education).
* Identify patterns showing how test preparation affects student results.
* Enable dynamic filtering and interactive exploration through slicers.

---

## 📊 Data Model

The dataset includes the following key columns:

* **Student ID** – Unique identifier for each student.
* **Gender** – Male or Female.
* **Ethnicity** – Group A, B, C, D, or E.
* **Parental Education** – Education level of parents.
* **Test Preparation** – Whether test preparation was completed or not.
* **Math Score**, **Reading Score**, **Writing Score** – Student performance metrics.

---

## ⚙️ Key Measures (DAX)

* **Average Math Score** = AVERAGE(`Scores[Math Score]`)
* **Average Reading Score** = AVERAGE(`Scores[Reading Score]`)
* **Average Writing Score** = AVERAGE(`Scores[Writing Score]`)
* **Average Score Percentage** = AVERAGE((`Math Score` + `Reading Score` + `Writing Score`) / 3)

These measures form the foundation for visual insights and KPIs.

---

## 📈 Visualizations Used

### 🧩 **KPI Cards**

* **Count of Students**
* **Average Math Score**
* **Average Reading Score**
* **Average Writing Score**
* **Average Score Percentage**

### 📊 **Charts & Visuals**

1. **Bar Chart:**
   Average Score Percentage by **Ethnicity**.

2. **Line Chart:**
   Average Score Percentage by **Parental Education** (shows performance decline with lower education levels).

3. **Donut Chart:**
   Average Score Percentage by **Gender** (comparison of male vs female performance).

4. **Pie Chart:**
   Average Score Percentage by **Test Preparation** (students who completed test prep perform better).

5. **Stacked Bar/Stream Graph:**
   Average Score Percentage by **Ethnicity and Parental Education** (combined view).

6. **Clustered Column Chart:**
   Comparison of **Math, Reading, and Writing Scores** for each student.

7. **Slicers (Filters):**

   * Ethnicity
   * Gender
   * Parental Education
   * Test Preparation

---

## 💡 Insights Derived

* Students who **completed test preparation** scored significantly higher across all subjects.
* **Parental education** level positively correlates with student performance — children of parents with bachelor’s or higher degrees perform better.
* Average performance across all ethnic groups remains relatively consistent, showing minimal variance.
* **Female students** showed slightly higher average reading and writing scores, while **male students** performed better in math.

---

## 🧰 Tools Used

* **Power BI Desktop**
* **Power Query** for data cleaning and transformation
* **DAX (Data Analysis Expressions)** for calculated measures
* **Excel/CSV dataset** as data source

---

## 📊 Dashboard Features

* **Interactive Filters** for quick segmentation.
* **Dynamic KPIs** displaying real-time averages.
* **Visual storytelling** through diverse charts and comparisons.
* **Clean and intuitive UI** for educators and management.

---

## 🏁 Conclusion

The **Student Performance Dashboard** in Power BI helps educators and analysts:

* Identify learning gaps.
* Measure the impact of test preparation and parental education.
* Understand demographic trends affecting academic performance.
* Support data-driven decisions to improve student outcomes.

---

**Project Title:** *Student Performance Analysis using Power BI*
**Prepared by:** *[Your Name]*
**Role:** *Data Analyst / Power BI Developer*
**Tools Used:** *Power BI, Excel, Power Query, DAX*
