# SCT_DS_4

Traffic Accident Analysis  

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

