# Diabetes Risk Forecast

## Hot to identify potential diabetic patients based on the similar characteristics to other patients with diabetes diagnostic?



Dashboard 1.png![Dashboard 1](https://user-images.githubusercontent.com/77758249/126440042-840629f4-ade0-4d12-b551-bf69fb5c165e.png)

Our dataset contains 2000 observations for female patients older that 21 years old. After doing some preliminar EDA and building a classification model we can share the following dashboard with this findings:

1) Diagnostic Results: % of the total outcome of patients with Diabetes 34.20%

2) Blood Pressure Type vs Outcome: We apply some Feature engineering techniques in Python to split 2 types of Blood Pressure called HS1 and HS2 according to the following classification.
- A normal diastolic blood pressure is lower than 80. A reading of 90 or higher means you have high blood pressure.
- Normal: Systolic below 120 and diastolic below 80
- Elevated: Systolic 120–129 and diastolic under 80
- Hypertension stage 1: Systolic 130–139 and diastolic 80–89
- Hypertension stage 2: Systolic 140-plus and diastolic 90 or more
- Hypertensive crisis: Systolic higher than 180 and diastolic above 120.

#### We can see that Blood Pressure type H2 is more correlated with a positive diabetic diagnostic that type HS1.

3)BMI (weight) Range vs Outcome: The standard weight status categories associated with BMI ranges for adults are shown in the following table.

Below 18.5 -> Underweight
18.5 – 24.9 -> Normal or Healthy Weight
25.0 – 29.9 -> Overweight
30.0 and Above -> Obese

#### We can see on the graphic that weight increase is highly correlated with a positive diabetic diagnostic. 
