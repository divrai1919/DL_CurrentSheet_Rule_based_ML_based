# Machine Learning-Based Identification of Current Sheets in Solar Wind

## Project Overview
This project explores the identification of Current Sheets (CS) in solar wind plasma using NASA ACE (Advanced Composition Explorer) spacecraft data. It combines physics-based feature engineering, traditional rule-based detection techniques, and machine learning algorithms to identify potential current sheet events.

## Key Features
- **Data Preprocessing:** Cleaning, synchronizing, and resampling magnetic field and solar wind plasma measurements.
- **Physics-Based Feature Engineering:** Calculation of Plasma Beta, Alfvén Speed, Alfvén Ratio, and magnetic field derivatives.
- **Rule-Based Detection:** Identification of potential current sheets using percentile-based thresholds.
- **Machine Learning Models:** Implementation of Random Forest and XGBoost classifiers.
- **Time-Series Analysis:** Chronological training and testing split to preserve temporal order.
- **Model Evaluation:** Performance assessment using Precision, Recall, F1-score, and classification reports.
- **Feature Importance:** Analysis of important physical parameters contributing to model predictions.

## Technologies Used
- Python
- Pandas & NumPy
- Matplotlib
- Scikit-learn
- XGBoost
- Jupyter Notebook

## Objective
To explore how machine learning techniques can complement physics-based approaches for identifying potential current sheet structures in solar wind data.
