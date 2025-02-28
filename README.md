# 📊 Survival Analysis of Primary Biliary Cirrhosis (PBC)

## 📌 Background
Primary Biliary Cirrhosis (PBC) is a chronic autoimmune liver disease that can lead to progressive liver damage and increased mortality risk. Understanding the factors influencing patient survival is crucial for improving treatment strategies and clinical decision-making. This project employs survival analysis techniques to investigate the impact of various clinical and demographic variables on PBC patient survival.

## 🛠 Methodology
The analysis follows these key steps:
1. **Data Preprocessing**: Cleaning and transforming the PBC dataset from the Mayo Clinic.
2. **Kaplan-Meier Survival Curve**: Estimating survival probabilities over time.
3. **Log-rank Test**: Comparing survival distributions across different patient groups.
4. **Cox Proportional Hazard Model**: Identifying significant predictors of survival.
5. **Extended Cox Model with Time-Dependent Covariates**: Addressing non-proportional hazards to enhance model accuracy.

## 📊 Key Insights
- The **Kaplan-Meier survival curves** revealed that factors such as ascites, hepatomegaly, and sex significantly impact survival.
- **Log-rank tests** indicated statistical differences in survival based on key clinical factors.
- **The Cox Proportional Hazard model** identified bilirubin levels, albumin, and age as significant predictors of survival time.
- **The Extended Cox Model** helped adjust for time-dependent covariates, improving prediction accuracy.

This project provides valuable insights into survival trends among PBC patients and can aid in personalized treatment strategies.

