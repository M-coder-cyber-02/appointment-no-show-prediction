# Appointment No-Show Prediction

This project aims to predict whether patients will miss their scheduled medical appointments using clinical and demographic data. Accurate prediction of no-shows can help healthcare providers improve scheduling efficiency, reduce wasted resources, and enhance patient care.

---

## Project Overview

Appointment no-shows cause significant operational challenges and financial losses in healthcare. This project analyzes patient and appointment data, performs exploratory data analysis, feature engineering, and builds machine learning models to predict no-shows.

Two classification models—Logistic Regression and Random Forest—are trained and evaluated. The models are assessed using precision, recall, F1-score, and accuracy to measure their effectiveness.

---

## Data Description

The dataset includes patient demographics, appointment details, medical history indicators, and social factors such as scholarship status. Key features include age, gender, chronic diseases, appointment day, and wait time.

---

## Methodology

- Data cleaning: handled missing values, removed irrelevant columns  
- Feature engineering: created meaningful variables, encoded categorical data  
- Exploratory data analysis: visualized distributions and relationships  
- Statistical tests: used chi-square tests to check feature associations  
- Model building: trained Logistic Regression and Random Forest classifiers  
- Model evaluation: calculated precision, recall, F1-score, and accuracy  
- Cross-validation: performed 5-fold cross-validation for robustness

---

## Results Summary

| Model               | Class | Precision | Recall | F1-score | Accuracy |
|---------------------|-------|-----------|--------|----------|----------|
| Logistic Regression  | 0     | 64%       | 67%    | 65%      | 64%      |
| Logistic Regression  | 1     | 65%       | 62%    | 64%      |          |
| Random Forest       | 0     | 78%       | 48%    | 60%      | 67%      |
| Random Forest       | 1     | 63%       | 86%    | 73%      |          |

The Random Forest model performed better in predicting no-shows (class 1) with higher recall and F1-score.

---

## How to Run
  
```bash
git clone https://github.com/M-coder-cyber-02/appointment-no-show-prediction/edit/main/README.md
pip install -r requirements.txt
jupyter notebook Appointment_No_Show_Prediction.ipynb
```
---

## Future Work

Experiment with advanced models like XGBoost or LightGBM

Hyperparameter tuning to improve performance

Incorporate time-based features such as prior no-show history

Explore cost-sensitive learning to handle class imbalance

---

## Contact

**Author**: Mahwish Malik  
**LinkedIn**: https://www.linkedin.com/in/dr-mahwish-m-a570892a8/  
**Email**: mahwishmalik1997@gmail.com

---

## Acknowledgements
Thanks to the data providers and open-source libraries used in this project.
