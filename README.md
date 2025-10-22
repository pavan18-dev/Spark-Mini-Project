# 🗺️ Spark Postal Network Analysis — Mini Project

[![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)](https://www.python.org/)  
[![Apache Spark](https://img.shields.io/badge/Apache%20Spark-3.5-orange?logo=apache-spark)](https://spark.apache.org/)  
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

This project leverages **Apache Spark** and geospatial analytics to analyze the Indian postal network.  
Using the national *Pincode Dataset*, the aim is to identify postal coverage gaps, detect isolated post-offices, and recommend strategic expansion locations.

---

## 📂 Project Files

- `Bda Mini Project.ipynb` → Complete PySpark analysis & visualizations  
- `Spark Mini Project Report.pdf` → Final written report summarizing results  
- `pincode dataset.csv` → Dataset used (≈ 165 000+ records covering all India)  

---

## 🧰 Tech Stack

- 🐍 Python  
- ⚡ Apache Spark  
- 📊 Pandas, NumPy, Matplotlib, Folium  
- 🌍 Geopy, Scikit-learn (DBSCAN clustering)  
- 📓 Jupyter Notebook  

---

## 🌟 Key Highlights

- Cleaned and processed India’s postal network dataset with >100k records  
- Developed interactive maps (via Folium) visualizing post-office locations & clusters  
- Built a *Saturation Score* model (Total Offices ÷ Unique Pincodes) to identify underserved districts  
- Applied DBSCAN geospatial clustering to detect isolated post offices (>5 km apart)  
- Provided actionable insights for new post-office placement and last-mile delivery optimization  

---

## 📊 Analysis Overview

- ✅ Data cleaning & standardization using PySpark  
- 🌐 Geospatial clustering of post offices (latitude & longitude)  
- 📈 District-level density heat-map (Saturation Score)  
- 🗺️ Real-time “Nearest Post Office Finder” by user location  
- 🧭 Straight-line distance tool for two post-offices and route visualization  
- 🟢 Expansion recommendation for low-coverage regions  

---

## 📈 Major Findings

- 📍 Metro regions (Delhi, Mumbai, Hyderabad) show high postal density  
- 🟡 Rural or remote states/districts often have low saturation scores → targets for new offices  
- 🟣 DBSCAN clustering identified many isolated offices (>5 km neighbour) indicating service gaps  
- 🧮 Significant variation in state-wise “people per post office” ratio  
- 📊 Produced a list of top 20 underserved districts for postal expansion  

---

## 🗺️ Visualisations

- 🧭 Nearby Post Offices Interactive Map  
- 🟢 New Office Suitability Map (Low Saturation Districts)  
- 🟣 Postal Network Optimisation Map (Isolated Offices)  
- 🧮 Population vs Post Office Comparison Chart  
- 🧾 Distance Between Two Post Offices Map  

---

## 🪄 How to Run

```bash
1. Clone the repository:  
   bash
   git clone https://github.com/pavan18-dev/Spark-Mini-Project.git
   cd Spark-Mini-Project
   

2. Install dependencies:  
   bash
   pip install pyspark pandas folium geopy scikit-learn matplotlib 
   

3. Run the notebook:  
   bash
   jupyter notebook "Bda Mini Project.ipynb"
   
