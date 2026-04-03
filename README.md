# Industrial-Sensor-Analytics-AI
 Project Overview

As an AI & Data Science specialist with a background in Electronics, I developed this project to bridge the gap between Hardware (Sensors) and Predictive Analytics. This pipeline simulates a factory environment where machine health is monitored via Voltage and Temperature sensors to identify potential "Fault" states before they cause downtime.

 Key Features

* Synthetic Data Generation: Created a robust dataset of 1,000+ industrial sensor readings using Python and NumPy.
* SQL Integration: Implemented an SQLite database to store and query high-frequency sensor data.
* Advanced Analytics: Used SQL GROUP BY and HAVING clauses to isolate machines overheating (Temp > 60°C) during fault states.
* Data Visualization: Built Matplotlib scatter plots to visualize the correlation between Voltage fluctuations and Machine Temperature.

* Technical Stack

* Language: Python 3.x
* Database: SQL (SQLite)
* Libraries: Pandas, NumPy, Matplotlib
* Domain: Industrial IoT (IIoT) / Predictive Maintenance

* Business Insights (The "So What?")

By analyzing the sensor logs, this script identifies:

1. Which machines are currently in a 'Fault' status.
2. The specific Voltage-Temperature correlation that leads to hardware failure.
3. Prioritization for maintenance teams based on Average Temperature per machine unit. 
