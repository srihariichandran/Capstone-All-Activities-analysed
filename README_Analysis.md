# 🏃‍♂️ Capstone Project – All Activities Analysed (Strava + Cycling KPIs)

This repository contains a comprehensive data analysis project based on cycling and activity data sourced from Strava and related sources. The goal of this capstone project is to derive meaningful KPIs from raw activity logs, explore performance trends, and visualize fitness insights using Python.

---

## 📂 Repository Structure
📁 /Capstone-All-Activities-analysed
│
├── Session_Level_Activity_KPIs.ipynb # Jupyter notebook for per-session KPI analysis
├── Strava_Analysis.ipynb # Full exploratory analysis on Strava activity data
├── Cycling data Analysis.ipynb # Combined insights from multiple sources
│
├── strava_activities.csv # Raw Strava activity data
├── strava_activities_with_kpis.csv # Strava data enriched with KPIs
├── cyclist_data_23T2.csv # Semester-based group dataset (23T2)
├── cycling_data_with_kpis.csv # Cleaned + calculated metrics dataset
├── ImprovedData_FullKPI.xlsx # Final cleaned Excel file with all KPIs
│
├── Data Analysis Team.pdf # Team overview / planning slides
├── INTRO MEET 1.pdf # Introductory project brief
├── image.png # Sample visual or heatmap
├── README.md # You're reading this!


---

## 📊 Project Highlights

- ✅ Cleaned and filtered raw session data (removal of nulls, missing steps, etc.)
- 🧮 Computed key fitness KPIs including:
  - Calories per minute  
  - Calories per km  
  - Average speed  
  - MET estimates  
  - Distance-efficiency scores  
  - Effort level flags
- 📈 Created insightful visualizations such as:
  - KDE plots, histograms, and boxplots per activity type
  - Jointplots to compare calorie burn vs duration or distance
  - Activity-wise heatmaps and correlation matrices
- 🔍 Filtered and analysed patterns across different activity types
- 🧠 Performed hypothesis-driven comparisons between running, walking, cycling sessions
- 📁 Created notebooks for both session-level and full data-level KPI workflows

---

## 🧰 Tools Used

- **Python (Pandas, NumPy, Seaborn, Matplotlib)**
- **Jupyter Notebook**
- **Excel (for summary exports)**
- **Git + GitHub (for version control)**

---

## 📌 Future Work (Ideas)

- Time series trends (weekly/monthly progress tracking)
- Clustering user behavior by pace, calories, or distance
- Predictive modeling (e.g., calories burned or fatigue score estimation)
- Integration with wearable device outputs (e.g., ReflexionPro)

---

## 🔗 Author

**Srihari Chandran**  
📍 Master of Data Science – Deakin University  
📫 [LinkedIn](https://www.linkedin.com/in/srihariichandran/) | 📈 [GitHub Profile](https://github.com/srihariichandran)

---

> This is an academic capstone project submitted for assessment purposes. All datasets are either anonymized or used with permission for analysis.


