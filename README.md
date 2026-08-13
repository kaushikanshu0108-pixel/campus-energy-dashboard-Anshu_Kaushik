# Campus Energy-Use Dashboard

Analyzes energy consumption data collected from multiple campus buildings. The project loads, cleans, and processes raw building-level energy data, then visualizes usage trends to surface patterns such as peak hours and high-consumption buildings.

## Objectives
- Import multiple building energy CSV files
- Clean and validate timestamp and kWh values
- Aggregate usage by day, week, and building
- Model buildings using Object-Oriented Programming
- Generate a combined visualization dashboard
- Export cleaned data, summaries, and insights

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Object-Oriented Programming

## How to Run
```bash
pip install -r requirements.txt
python src/run_dashboard.py
```

## Input Data
Stored in `./data/` — one CSV per building (e.g. `building_A.csv`, `building_B.csv`), each containing timestamp and kWh readings.

## Output Files (Generated)
| File | Description |
|---|---|
| `cleaned_energy_data.csv` | Fully cleaned dataset |
| `building_summary.csv` | Mean, min, max, and total kWh per building |
| `dashboard.png` | Multi-plot visualization |
| `summary.txt` | Key findings and insights |

## Dashboard Contents
- Line chart — daily energy usage trend
- Bar chart — weekly average per building
- Scatter plot — peak-hour consumption

## Summary of Insights
- Highest-consuming building: _add your result here_
- Peak usage time: _add your result here_
- Notable trend: _add your result here_

## Conclusion
The dashboard provides actionable insights for campus energy planning, helps detect inefficiencies, and supports decision-making for sustainability initiatives.
