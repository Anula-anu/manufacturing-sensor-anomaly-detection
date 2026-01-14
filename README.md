# Manufacturing Sensor Data Anomaly Detection

## Overview
This project detects anomalies in time-series sensor data collected from a manufacturing line using an unsupervised machine learning approach.

---

## Technologies Used
- Python
- Pandas
- scikit-learn
- Matplotlib

---

## Dataset
- Smart Manufacturing IoT-Cloud Monitoring Dataset (Kaggle)
- The dataset contains time-series sensor readings.
- Temperature sensor data was used for anomaly detection.

---

## Project Workflow
1. Loaded sensor data from a CSV file.
2. Converted timestamps to datetime format.
3. Cleaned missing values using forward fill.
4. Removed invalid sensor readings.
5. Applied Isolation Forest for anomaly detection.
6. Visualized anomalies on a time-series plot.

---

## Anomaly Detection Method
Isolation Forest was used because it works well for unlabeled data and efficiently identifies abnormal patterns.

---

## Output
- Jupyter Notebook with anomaly detection code and results.
- Time-series chart showing detected anomalies with timestamps.

---

## Files in This Repository
- manufacturing_anomaly_detection.ipynb
- smart_manufacturing_data.csv
- manufacturing_sensor_anomalies.png
- README.md

---

## How to Run
1. Install required libraries:
   pip install pandas scikit-learn matplotlib
2. Open the notebook:
   jupyter notebook manufacturing_anomaly_detection.ipynb
3. Run all cells to view results.

---

## Result
The model successfully detects abnormal sensor readings and highlights them on a time-series chart.

---

## Author
Anula Biju

