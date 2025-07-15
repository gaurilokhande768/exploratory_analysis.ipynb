# Predictive Maintenance for Manufacturing


## 🚀 Project Goal
Predict when manufacturing machines are likely to fail using historical sensor data to reduce unplanned downtime and enable proactive maintenance.


## 📊 Dataset
Source: `Predictive_Maintenance_Corrected.xlsx`  
Sheet: `Sensor Data`


### Features:
- `Timestamp`: Date and time of the record
- `Machine_ID`: Unique ID for the machine
- `Vibration (mm/s)`
- `Temperature (°C)`
- `Pressure (bar)`


### Target:
- `Failure`: 0 (No Failure), 1 (Failure)


## ⚙️ Model Building
Two classifiers were used:
- Random Forest Classifier
- XGBoost Classifier


### Evaluation Metrics:
- Confusion Matrix
- Accuracy, Precision, Recall, F1-Score
- ROC-AUC Score


## 📈 Results
Both models were trained and tested. The notebook includes evaluation metrics and feature importance plots to interpret model decisions.


## 🛠️ Requirements
Install packages from `requirements.txt`:
```bash
pip install -r requirements.txt