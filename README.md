# Heart Disease Risk Analysis: Exploring Health and Lifestyle Factors Using Python & Power BI
## Project Objectives
This project analyzed patient health data and developed an interactive dashboard that helps identify patterns and associations between heart disease and key demographic, clinical, and lifestyle factors.

## Dataset used
- <a href = “https://github.com/Gem-24/Heart-Disease-Risk-Analysis-and-Interactive-Dashboard/edit/main/heart_disease_risk_2026.csv”>dataset</a>
- <a href = “https://github.com/Gem-24/Heart-Disease-Risk-Analysis-and-Interactive-Dashboard/edit/main/heart_disease_risk_2026_clean.csv”>dataset_cleaned</a>

## Question KPIs
-	What proportion of patients have heart disease?
-	How does heart disease differ by gender? 
-	Which age group has the highest heart disease rate? 
-	How is heart disease associated with BMI? 
-	How does heart disease vary with HbA1c/blood sugar status? 
-	Is heart disease more common among smokers? 
-	What is the association between family history and heart disease? 
-	How is exercise-induced angina associated with heart disease? 
-	How does blood pressure relate to heart disease? 

## Dashboard Interaction
-<a href = “https://github.com/Gem-24/Heart-Disease-Risk-Analysis-and-Interactive-Dashboard/edit/main/Heart%20disease%20risk%20analysis.pbix”>Dashboard Power BI</a>

## Tools and Purposes
-	Python/ Google Colab was used for data preparation which involves data cleaning and transformation
-	Pandas was used for Data manipulation and analysis
-	Microsoft Power BI/ DAX was used for Data Modelling, measures and analytical calculations, KPIs and dashboard development.
-	CSV: Dataset storage and exchange

## Process
-	Collected Dataset and identified the Problems in the dataset
-	Verified data for any missing values, duplicates and sort out the same
-	Inspected and prepared the dataset for analysis by ensuring consistency and accuracy of the dataset. The dataset was transformed to create additional analytical variables.
-	Imported the cleaned dataset and DAX measures were created to calculate important metrics such as Total Patients, Patients with Heart Disease, heart Disease Prevalence, Average Age, Average BMI, total patients with Diabetes, total patients with High Cholesterol, Patients with Family History, Patients with Stage 2 High Blood Pressure, Patients classified as Obese, Male/Female distribution
-	Developed Dashboard with first page containing patients overview and demographics, and second page bearing the risk factor analysis.

## Dashboard
<img width="624" height="351" alt="Dashboard pg1" src="https://github.com/user-attachments/assets/6efe1e6b-ec62-4891-a30f-c1bf1e8b26ca" />
<img width="624" height="350" alt="Dashboard pg2" src="https://github.com/user-attachments/assets/8e65225d-cbb3-4656-9d47-fe7e705569ef" />


## Project insight
-	Out of 9,000 patients, 2,727 were recorded as having heart disease, giving an overall observed prevalence of 30.30%. 
-	Older patients had a much higher observed rate than younger patients (Old: 46.69% → Mid-Aged: 24.39% → Young: 9.89%) 
-	Male patients had a higher observed heart disease rate than female patients (Male: 35.36% vs Female: 24.69%)
-	Heart disease prevalence increased across the BMI categories, with the highest observed rate among patients classified as obese (Obesity: 47.94%) compared with patients with Normal having 22.72%
-	Patients classified as diabetic had an observed heart disease rate of approximately 47.06%, compared with 21.28% among patients with normal HbA1c status. 
-	Patients classified with Stage 2 high systolic blood pressure had an observed heart disease rate of approximately 48.81%, compared with 17.70% among patients with normal systolic blood pressure. 
-	Current smokers had an observed heart disease rate of approximately 46.44%, higher than former smokers and never smokers. 
-	Patients with a family history of heart disease showed an observed rate of approximately 35.60%, compared with 28.31% among those without a family history.
-	Patients with exercise-induced angina had an observed heart disease rate of approximately 67.85%, compared with 19.14% among those without it.

## Final Conclusion
This project demonstrates how data analysis can transform a raw healthcare dataset into meaningful and interactive insights.
This analysis identified noticeable patterns involving age, gender, BMI, HbA1c, blood pressure, smoking status, family history and exercise-induced angina. Among these, older age, obesity, higher HbA1c categories, elevated blood pressure, current smoking, family history and exercise-induced angina were associated with higher observed heart disease prevalence in the dataset.
Overall, the project demonstrates my ability to take a dataset from raw data → Python data preparation → Power BI modelling → DAX calculations → interactive visualization → actionable insights.

## Note 
This dashboard is intended for analytical and educational purposes and should not be used as a medical diagnostic tool.
