# PRODIGY_DS_05
Internship task 5

# 🚦 Traffic Accident Data Analysis

## 📌 Project Overview

This project analyzes traffic accident data to identify patterns related to **weather conditions, road conditions, and time of day**. It also visualizes accident hotspots to better understand high-risk areas and contributing factors.

The goal is to extract meaningful insights that can help improve road safety and decision-making.

---

## 🎯 Objectives

* Analyze accident trends based on **time of day**
* Study the impact of **weather conditions**
* Examine how **road surface conditions** affect accidents
* Identify and visualize **accident hotspots**
* Understand **combined contributing factors**

---

## 📊 Dataset

The dataset used in this project is sourced from the
**UK Department for Transport**.

### Key Features:

* Date and Time of accidents
* Weather Conditions
* Road Surface Conditions
* Light Conditions
* Geographic Coordinates (Latitude & Longitude)

---

## 🛠️ Technologies Used

* Python 🐍
* Pandas
* Matplotlib
* Seaborn
* Folium (for map visualization)

---

## 🔍 Analysis Performed

### ⏰ Time-Based Analysis

* Extracted hour from timestamp
* Identified peak accident hours (rush hours)

### 🌧️ Weather Analysis

* Compared accident frequency across different weather conditions
* Observed higher accidents during adverse weather

### 🛣️ Road Condition Analysis

* Analyzed impact of road surface (wet, dry, icy)
* Found increased risk on wet/slippery roads

### 🌙 Light Condition Analysis

* Compared accidents during daylight vs darkness

### 🔥 Hotspot Visualization

* Used heatmaps to identify accident-prone areas
* Highlighted geographic clusters of accidents

### 🔗 Contributing Factors

* Combined analysis of weather and road conditions
* Identified how multiple factors increase accident risk

---

## 📈 Key Insights

* Accidents are highest during **morning and evening rush hours**
* **Rain and fog** significantly increase accident probability
* **Wet roads** contribute to higher accident rates
* More accidents occur during **low visibility conditions**
* Certain regions show **high accident density (hotspots)**

---

## 🚀 How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/your-username/traffic-accident-analysis.git
```

2. Install required libraries:

```bash
pip install pandas matplotlib seaborn folium
```

3. Run the Jupyter Notebook:

```bash
jupyter notebook
```

---

## 📁 Project Structure

```
├── data/
│   └── Accidents.csv
├── notebooks/
│   └── analysis.ipynb
├── images/
│   └── visualizations.png
├── README.md
```

---

## 💡 Future Improvements

* Build a machine learning model to predict accident severity
* Add real-time data integration
* Enhance visualization with interactive dashboards

---

## 📌 Conclusion

This project demonstrates how data analysis can uncover patterns in traffic accidents and help identify critical risk factors. Such insights can support better planning and safer road systems.

---

## 🙌 Acknowledgements

* Dataset provided by **UK Department for Transport**

