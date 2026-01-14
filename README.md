# Unsupervised Machine Learning for Fraud Detection

Master’s Thesis – MIM + Analytics (UTDT, 2022) - Early application of unsupervised ML to fraud detection in financial institutions

“Application of Unsupervised Machine Learning Methods for Fraud Detection in Financial Institutions”

Variables:
- Date and time
- IP address
- IP City
- Device ID
- Keyboard language
- Connection channel (Web/Mobile)
- Operating system
- Browser type
- Browser version
- Internet provider
- External risk score

## Data Availability
Due to confidentiality reasons, the original datasets are not included.
The analysis focuses on methodology, modeling approach, and results interpretation.

## Objective
Apply unsupervised machine learning techniques to detect fraudulent patterns
in financial transactions without labeled data.

## Dataset
Transactional-level data with behavioral, device, and network features.

## Methods
- Clustering (K-Means, DBSCAN)
- Anomaly Detection
- Graph based Feature Engineering  

## Key Results
- Identified fraud-related behavioral clusters
- Improved early fraud detection without supervised labels

## Repository Structure
.
├── notebooks/
│   ├── 01_variable_selection_graphs.ipynb
│   ├── 02_outlier_detection_graphs.ipynb
│   └── 03_dbscan_model.ipynb
│
├── reports/
│   └── Master_Thesis_Unsupervised_Fraud_Detection.pdf
│
└── README.md
