Campus Energy-Use Dashboard


---

📁 Overview

This project analyzes energy consumption data collected from multiple campus buildings.
The goal is to load, clean, process, and visualize energy usage trends to identify patterns such as peak hours and high-consumption buildings.


---

🎯 Objectives

Import multiple building energy CSV files

Clean and validate timestamp + kWh values

Aggregate usage (daily, weekly, building-wise)

Model buildings using Object-Oriented Programming

Generate a combined visualization dashboard

Export cleaned data, summaries, and insights



---

🧰 Technologies Used

Python

Pandas

NumPy

Matplotlib

Object-Oriented Programming



---

🚀 How to Run

1. Install required packages:



pip install -r requirements.txt

2. Run the main script:



python src/run_dashboard.py


---

🗂 Input Data

Stored in ./data/

Contains one CSV per building (example: building_A.csv, building_B.csv)

Each file includes timestamp and kWh readings.


> (Use real dataset link or source name here if applicable)




---

📊 Output Files (Generated)

File	Description

cleaned_energy_data.csv	Fully cleaned dataset
building_summary.csv	Mean, min, max, and total kWh per building
dashboard.png	Multi-plot visualization
summary.txt	Key findings and insights



---

📈 Dashboard Contents

The visualization includes:

📍 Line chart (Daily energy usage trend)

📍 Bar chart (Weekly average per building)

📍 Scatter plot (Peak-hour consumption)



---

📝 Summary of Insights (Example Format — You will replace with your results)

Highest-consuming building: Building X

Peak usage time: 10:00 AM – 12:00 PM

Significant trend: Higher consumption on weekdays compared to weekends



---

🏁 Conclusion

The dashboard provides actionable insights for campus energy planning, helps detect inefficiencies, and supports decision-making for sustainability initiatives.
