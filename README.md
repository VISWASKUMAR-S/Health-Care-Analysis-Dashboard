# Healthcare Data Analysis with Power BI

## Objective
The objective of this project is to leverage Power BI for a deep dive into the provided healthcare datasets. This task encompasses meticulous data cleaning and sophisticated data modeling, utilizing DAX for advanced analytics. The goal is to create a comprehensive, interactive dashboard in Power BI that presents a cohesive narrative of the healthcare data. This dashboard will serve as a tool to uncover and visualize important trends, such as the interplay between patient demographics and treatment outcomes, cost implications of various medical procedures, and overall hospital performance metrics. The analysis will provide invaluable insights, aiding healthcare providers in enhancing patient care and operational efficiency, and positioning HealthStat Solutions at the forefront of healthcare analytics.
                                                                ![HOSPITAL VIEW](./assets/72d341eb-d0db-4712-af2e-a418e3ad673e.png)
## About the Data

### Health Care Dataset 1
- **PatientID**: A unique identifier for each patient. (Primary Key)
- **PatientName**: Name of the patient.
- **Age**: Age of the patient.
- **Gender**: Gender of the patient.
- **BloodType**: Blood type of the patient.
- **Diagnosis**: The diagnosis given to the patient.
- **Treatment**: The treatment provided to the patient.
- **AdmissionDate**: Date when the patient was admitted.
- **DischargeDate**: Date when the patient was discharged.
- **TotalBill**: The total bill amount for the patient's treatment.
- **Full Prescription Details**: Detailed prescription information including medication names, dosages, frequency, and duration.

### Health Care Dataset 2
- **PatientID**: A unique identifier for each patient, corresponding to 'PatientID' in "HealthcareDataset1.xlsx". (Foreign Key)
- **Hospital**: The name of the hospital where the patient was treated.
- **DoctorName**: Name of the doctor who treated the patient.
- **RoomNumber**: The room number assigned to the patient.
- **DailyCost**: The daily cost of the patient's treatment.
- **TreatmentType**: Type of treatment provided.
- **RecoveryRating**: A rating of the patient's recovery (out of 10).

It sounds like you have a clear and ambitious objective for your Power BI project! Here's a structured approach to help you achieve your goals:

### **1. Data Cleaning**
- **Remove Duplicates**: Ensure there are no duplicate records in your datasets.
- **Handle Missing Values**: Decide how to handle missing data (e.g., imputation, removal).
- **Standardize Formats**: Ensure consistency in data formats (e.g., dates, numerical values).

### **2. Data Modeling**
- **Relationships**: Establish relationships between the two datasets using `PatientID` as the key.
- **Calculated Columns**: Use DAX to create calculated columns for additional insights (e.g., length of stay, total cost).

### **3. Advanced Analytics with DAX**
- **Measures**: Create measures for key metrics such as average treatment cost, recovery ratings, etc.
- **Time Intelligence**: Utilize DAX functions to analyze trends over time (e.g., monthly admissions, discharge rates).

### **4. Dashboard Design**
- **Interactive Visuals**: Use a variety of visuals (e.g., bar charts, line graphs, pie charts) to represent different aspects of the data.
- **Filters and Slicers**: Allow users to filter data by demographics, treatment types, hospitals, etc.
- **Narrative**: Ensure the dashboard tells a cohesive story, highlighting key insights and trends.

### **5. Key Insights to Uncover**
- **Patient Demographics and Treatment Outcomes**: Analyze how age, gender, and blood type affect treatment outcomes.
- **Cost Analysis**: Examine the cost implications of different treatments and procedures.
- **Hospital Performance**: Compare performance metrics across hospitals, such as recovery ratings and average costs.

### **6. Enhancing Patient Care and Operational Efficiency**
- **Predictive Analytics**: Use historical data to predict future trends and outcomes.
- **Operational Metrics**: Track metrics like bed occupancy rates, average length of stay, and readmission rates.

## Conclusion
This project aims to transform raw healthcare data into actionable insights through the power of Power BI. By creating an interactive and comprehensive dashboard, we can uncover critical trends and metrics that will help healthcare providers improve patient care and operational efficiency. The insights gained from this analysis will position HealthStat Solutions as a leader in healthcare analytics, driving better outcomes for patients and providers alike.

