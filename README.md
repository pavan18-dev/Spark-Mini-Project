🗺️ Spark Postal Network Analysis — Mini Project






This is my Apache Spark Mini Project analyzing the Indian Pincode & Post Office Dataset.
The project focuses on geographical clustering, postal density, underserved regions, and identifying suitable locations for new post offices using both analytical and geospatial models.

📂 Project Files

Bda Mini Project.ipynb → Complete PySpark analysis and visualizations

Spark Mini Project Report.pdf → Final written report with results and insights

pincode dataset.csv → Dataset used (≈ 165 000 records)

🧰 Tech Stack

🐍 Python

⚡ Apache Spark

📊 Pandas, NumPy, Matplotlib, Folium, Seaborn

🌍 Geopy, Scikit-learn (DBSCAN)

📓 Jupyter Notebook

🌟 Project Highlights

Cleaned, transformed, and analyzed a nationwide postal dataset (1 L + records).

Built geospatial visualizations of all Indian post offices using Folium maps.

Implemented Nearest Post Office Finder — real-time map search by location.

Designed a Saturation Score Model to identify underserved districts.

Applied DBSCAN clustering to detect isolated post offices (> 5 km apart).

Proposed new postal locations using combined analytical + geospatial insights.

📊 Analysis Performed

✅ Data cleaning and schema optimization in PySpark

🌐 Geographical clustering of offices by latitude & longitude

📈 District-level postal density (Saturation Score = Total Offices / Unique Pincodes)

🗺️ Interactive map of nearest post offices to user location

🧭 Distance analysis between two post offices (via geodesic distance)

🟢 Expansion recommendations for underserved regions

📈 Key Insights

📍 High postal concentration in metro areas (Delhi, Mumbai, Hyderabad).

🟡 Rural and hilly regions show low saturation — potential for new offices.

🟣 DBSCAN clusters showed isolated nodes > 5 km apart, indicating service gaps.

🧮 Population vs Post Office ratio varies significantly — some states underserved.

📊 Model proposed 20 priority districts nationwide for future postal infrastructure.

🗺️ Visualizations

🧭 Nearby Post Offices Interactive Map

🟢 New Post Office Suitability Map (Low Saturation Districts)

🟣 Postal Network Optimization Map (DBSCAN Isolation)

🧮 Population vs Post Office Comparison Chart

🧾 Distance between Two Post Offices Map

🪄 How to Run

Clone the repository:

git clone https://github.com/your-username/Spark-Postal-Analysis.git
cd Spark-Postal-Analysis


Install dependencies:

pip install pyspark pandas folium geopy scikit-learn matplotlib


Run the notebook:

jupyter notebook "Bda Mini Project.ipynb"

🧾 Results Summary
Analysis	Outcome
Saturation Score Model	Highlighted top 20 underserved districts in India
DBSCAN Clustering	Found isolated offices > 5 km from nearest neighbor
Geodesic Distance Tool	Mapped real-world postal routes between areas
Population Analysis	Compared state population to number of offices
Visualization Layer	Interactive Folium maps for all postal activities
🧩 Conclusion

This project demonstrates how Big Data Analytics and Geospatial Computation
can optimize national postal infrastructure by identifying underserved zones,
planning new offices strategically, and enhancing last-mile delivery efficiency.
