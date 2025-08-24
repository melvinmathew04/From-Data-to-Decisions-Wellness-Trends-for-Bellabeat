# Turning Steps into Strategy: A Bellabeat Case Study

This project analyzes **Fitbit fitness tracker data** to uncover trends in physical activity, sleep, and calorie expenditure.  
The findings are applied to **Bellabeat**, a high-tech wellness company, to provide **data-driven marketing recommendations**.

---

## 📌 Business Task
Bellabeat wants to understand how smart device data can reveal user health and wellness behaviors.  
The goal of this analysis is to:
1. Identify usage trends from Fitbit data.  
2. Translate these insights into actionable strategies for Bellabeat.  

---

## 📂 Data Sources
The dataset comes from a public [Fitbit Fitness Tracker dataset on Kaggle](https://www.kaggle.com/datasets/arashnic/fitbit), collected via Amazon Mechanical Turk (April–May 2016).  
Files used:
- `dailyActivity_merged.csv`  
- `dailyCalories_merged.csv`  
- `dailySteps_merged.csv`  
- `sleepDay_merged.csv`  
- `weightLogInfo_merged.csv`  

---

## 🛠️ Data Cleaning & Preparation
- Standardized column names for consistency.  
- Converted date/time fields into usable formats.  
- Removed duplicate and null values.  
- Merged datasets into a **master daily dataset** containing steps, calories, activity minutes, sleep, and weight/BMI.  
- Validated number of unique users and date ranges.  

---

## 📊 Analysis & Findings
- **Steps vs Calories**: Clear positive relationship → more steps = higher calorie burn.  
- **Sedentary Time**: Majority of the day spent sedentary, with fewer “very active” minutes.  
- **Weekday vs Weekend Trends**: Users generally take more steps on weekdays.  
- **Sleep Patterns**: Incomplete but show significant variability in total sleep time.  

---

## 📈 Visualizations
Key plots include:
- Scatter plot: **Steps vs Calories**  
- Line chart: **Average Steps by Day of Week**  
- Bar chart: **Activity Minutes Breakdown**  
- Histogram: **Sleep Distribution**  

---

## 🚀 Recommendations for Bellabeat
1. **Promote Activity Streaks** – gamify daily step goals with challenges.  
2. **Target Sedentary Users** – in-app nudges for micro-workouts and reminders to move.  
3. **Weekend Campaigns** – encourage weekend workouts and outdoor activities.  
4. **Sleep Optimization** – highlight Bellabeat’s sleep tracking features.  
5. **Hydration & Recovery** – link sedentary breaks with reminders from the Bellabeat Spring water bottle.  




