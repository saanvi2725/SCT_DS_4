# SCT_DS_4
Here’s a well-structured, beginner-friendly and **humanized `README.md`** for **Task 04** of your SkillCraft Technologies internship:

---

# 📌 Task 04 – Traffic Accident Analysis  
**SkillCraft Technologies – Data Science Internship**

---

## 🧠 Objective  
In this task, I analyzed traffic accident data to uncover patterns related to:
- 🛣️ **Road conditions**
- 🌦️ **Weather**
- 🕒 **Time of day**

The goal was to understand what factors contribute to accidents and identify **hotspot areas** where accidents happen most frequently.

---

## 📂 Dataset Used
I used the [US Accidents (Kaggle)](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents) dataset, which includes over 3 million accident records collected from across the United States.

**Key features analyzed:**
- `Weather_Condition`, `Temperature`, `Humidity`
- `Road_Surface_Condition`, `Visibility`
- `Start_Time`, `End_Time`, `City`, `Severity`
- `Start_Lat`, `Start_Lng` (for hotspot mapping)

---

## 🧰 Tools & Libraries
- `pandas`, `numpy` for data manipulation
- `matplotlib`, `seaborn` for visualizations
- `folium` or `plotly` for interactive maps
- `datetime` for time-based analysis

---

## 🔍 What I Did

### ✅ Data Cleaning
- Handled missing values in weather and road condition columns
- Converted timestamps to proper datetime format
- Filtered out incomplete or irrelevant records

### ✅ Exploratory Data Analysis (EDA)
- Accidents by **hour of day**, **day of week**, and **month**
- Comparison of accident counts during **clear vs foggy/rainy conditions**
- Heatmap of accident frequency by time and weather

### ✅ Visualization of Hotspots
- Plotted accident locations using latitude and longitude on an interactive map
- Highlighted cities with the most frequent accidents

---

## 📊 Key Insights
- Most accidents happen between **7–9 AM** and **4–6 PM** (rush hours)
- Rain, fog, and low visibility significantly increase accident frequency
- Certain cities consistently show up as accident hotspots (e.g., Los Angeles, Miami)

---

## 📁 Files Included
- `traffic_accident_analysis.ipynb`: Code and visualizations
- `accident_dataset.csv` or link to original Kaggle dataset
- Images or screenshots of visual insights (optional)

---

## 🚀 What's Next?
I’d love to try clustering hotspot areas using KMeans or predicting accident severity using machine learning in future tasks!

---

Let me know if you’d like this saved as a `.md` file or tailored to a specific dataset you're using (like Indian or UK traffic data)!
