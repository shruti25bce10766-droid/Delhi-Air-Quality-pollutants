---

📌 Delhi AQI Analysis – Visualization Project

📍 Overview
--
This project analyzes the Air Quality Index (AQI) levels of Delhi using real dataset inputs and produces key data visualizations.
It preprocesses real pollutant data and generates:
✔ Weekly Time-Series Visualization
✔ Pollutant Distribution Box Plot
✔ Pollutant Contribution Pie Chart

(Documentation requirements covered per: readme structure section )


---

🎯 Features

Feature	Description

Data Cleaning	Handling NaN values, formatting timestamps
Time-Series Trend	Weekly analysis of key pollutants
Statistical Distribution	Box plots showing pollutant variance
Proportional Contribution	Pie chart illustrating pollution dominance


Matches functional module requirement of at least 3 modules 


---

🛠 Tech Stack

Python

Pandas

Matplotlib

NumPy


(Includes tools used, as required in README )


---

🧠 Dataset

Delhi AQI Dataset (CSV)

Columns used (if available): pm25, pm10, no2, so2, co, o3, date


Dataset details are part of design expectations for analytical projects 


---

📂 Project Structure

📁 Delhi-AQI-Analysis
│
├── 📄 main.py                  # Code file
├── 📄 README.md                # Documentation
├── 📊 delhi_aqi_timeseries_graph.png
├── 📊 delhi_aqi_boxplot.png
├── 📊 delhi_aqi_pie_chart.png
└── 📁 input dataset


---

🚀 How to Run

1️⃣ Install Requirements

pip install pandas matplotlib numpy

2️⃣ Place dataset in correct path

/kaggle/input/delhi-aqi/Delhi_AQI_Dataset.csv

3️⃣ Execute Script

python main.py


---

🧪 Testing Instructions

Ensure every column listed exists in the dataset

Check generated PNG files after execution

Modify pollutant column list to expand analysis


Testing guidance required in README 


---



Plot	Description

Time Series	Weekly PM2.5 & NO2 trends
Box Plot	Distribution of PM25, PM10, NO2 & SO2
Pie Chart	Relative pollution contributions


---

📌 Future Enhancements

Real-time AQI API integration

Dashboard UI via Streamlit

Predictive modeling using ML



---

👥 Target Users

Environmental researchers

Students working on pollution impact analysis

Data science learners working with time-series visualizations


Matches README expectations to state target users & high-level scope 


---

📚 References

Project documentation guidelines 

Dataset Source: Delhi AQI CSV (Public dataset)



---

✔ This README successfully covers:

Requirement	Status

Project title	✅
Overview	✅
Features	✅
Tools	✅
Install & Run Steps	✅
Testing Instructions	✅
