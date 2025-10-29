# HEDIS Hospital Analysis 📊

![Status](https://img.shields.io/badge/status-active-brightgreen)
![Python](https://img.shields.io/badge/python-3.10-blue)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

🔗 [View Project on GitHub](https://github.com/ChapaMchivi/hedis-hospital-analysis)

This notebook simulates a hospital dataset and applies HEDIS-aligned analytics, including:

-  Data cleaning & feature engineering  
-  Univariate & bivariate analysis  
-  Simulated screening flags (cancer, diabetes, BP)  
-  Outlier detection & audit flagging  
-  Stratified reporting dashboards  

##  Changelog

**v1.1.0**
- Refactored screening logic for cancer, diabetes, and BP flags
- Improved dashboard visuals and stratification
- Synced README with updated logic


## 🔧 Tech Stack  
- Python (pandas, seaborn, matplotlib)  
- Jupyter Notebook  
- GitHub for version control  

##  Structure  
- `hedis-hospital-analysis.ipynb`: Main notebook  
- `data/`: Simulated or anonymized datasets  
- `images/`: Visual assets (charts, dashboards)  
- `README.md`: Project overview  
- `requirements.txt`: Package list  
- `venv/`: Virtual environment (optional)

##  Reproducibility  
- Virtual environment setup: `python -m venv venv`  
- Install packages: `pip install -r requirements.txt`

##  Visual Summary

Below are key visualizations from the HEDIS hospital analysis notebook:

![Correlation Matrix](images/correlation_matrix.png)
![Doctors by Visit Volume](images/doctors_by_visit_volume.png)
![Length of Stay by Department Type](images/length_of_stay_by_department_type.png)
![Length of Stay Distribution](images/length_of_stay_distribution.png)
![Outlier Detection – Length of Stay](images/outlier_detection_length_of_stay.png)
![Outlier Detection – Minutes](images/outlier_detection_minutes.png)
![Outlier Detection – Revenue](images/outlier_detection_revenue.png)
![Patient Risk Distribution](images/patient_risk_distribution.png)
![Revenue Distribution by Department](images/revenue_distribution_by_department.png)
![Screening Rates by Risk Profile](images/screening_rates_by_risk_profile.png)
![Service Time by Risk Profile](images/service_time_by_risk_profile.png)
![Top 10 Doctors by Visit Volume](images/top_10_doctors_by_visit_volume.png)
![Visit Volume by Department](images/visit_volume_by_department.png)



