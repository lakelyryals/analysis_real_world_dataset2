# 🚲 Real-World Data Analysis: Bike Sharing Dataset

## ✍️ Author
**Lakely Ryals**

## 📌 Project Overview
This project explores the **Bike Sharing Dataset** from the UCI Machine Learning Repository to uncover rental behavior patterns across time, seasons, and weather conditions.

The goal is to use real-world public data to conduct an exploratory data analysis (EDA) that reveals how factors like temperature, humidity, weekday, and user type influence daily bike rental counts.

---

## 📂 Dataset Information
- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/bike+sharing+dataset)
- **File Used**: `day.csv` (daily rental records from 2011–2012)
- **Main Features**:
  - `dteday`: date
  - `season`: 1 = winter, 2 = spring, etc.
  - `temp`, `hum`, `windspeed`: normalized weather data
  - `casual`, `registered`, `cnt`: number of rentals by user type and total

---

## 📈 Key Visualizations
- **Line Chart**: Total rentals over time
- **Boxplots**:
  - Rentals by season
  - Rentals by weekday
- **Scatterplots**:
  - Temperature vs. rental count
  - Humidity vs. rental count
  - Casual vs. registered users

---

## 🔍 Key Insights
- Rentals peak during **commute hours** and **warmer seasons**
- **Temperature** has a strong positive correlation with usage
- **Humidity** and **windspeed** slightly reduce rental activity
- Weekends see more **casual** users; weekdays more **registered** commuters

---

## 🛠️ Tools Used
- Python
- Jupyter Notebook
- Pandas, Seaborn, Matplotlib

---

## 📎 Files Included
- `bike_sharing_analysis.ipynb`: Full notebook with analysis and plots
- `day.csv`: Raw dataset (not included on GitHub due to size, link to UCI)





## 🤝 Acknowledgment
This project was created as a capstone for practicing real-world data analysis and visualization.
