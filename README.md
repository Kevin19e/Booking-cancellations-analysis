# Hotel Booking Cancellation Prediction

## Overview
This project uses machine learning to predict whether a hotel booking will be cancelled.

The goal is to help hotels reduce revenue loss, optimize resource allocation, and improve customer satisfaction.

---

## Dataset
- Source: Kaggle – Hotel Booking Demand
- Features include:
  - Lead time
  - Customer demographics
  - Booking channel
  - Financial attributes

---

## Methodology

### Data Processing
- Removed missing values and duplicates
- Applied one-hot encoding for categorical variables

### Models Used
- Logistic Regression (baseline)
- Decision Tree
- Random Forest (best model)

---

## Results
- Logistic Regression: AUC = 0.47
- Decision Tree: AUC = 0.59
- Random Forest: AUC = 0.64 (best performance)

Key finding:
👉 Lead time is the most important factor influencing cancellations

---

## Business Impact
- Improves overbooking strategies
- Reduces revenue loss
- Enables targeted customer interventions

---

## Tech Stack
- Python
- Pandas
- Scikit-learn
- Matplotlib / Seaborn

---

## Future Improvements
- Handle class imbalance (SMOTE / resampling)
- Hyperparameter tuning
- Deploy model as API

---

## Author
Kevin Elezi
