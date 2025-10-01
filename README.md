# Healthcare-sql-project-
This project performs **Exploratory Data Analysis (EDA)** on a hospital management database to uncover meaningful insights related to **appointments**, **doctor productivity**, **revenue**, **billing**, **insurance usage**, and **patient behavior**. 
The analysis was done using SQL queries to address key business and operational questions that can support better decision-making within the hospital.

## 🧠 Problem Statement

Hospitals generate vast amounts of data across multiple departments. However, without proper analysis, this data remains underutilized. This project aims to analyze hospital data to:

- Identify departments with the highest appointments.
- Branch with the higest cancellations.
- What are the Peak days
- Detect operational inefficiencies.
- Understand patient behavior and value.
- Optimize insurance and payment systems.
- Improve overall healthcare service delivery.

## 📥 Data Source
**Source** https://www.kaggle.com/datasets/kanakbaghel/hospital-management-dataset
- The dataset used in this project simulates a **Hospital Management System** and includes tables such as:
- `doctors`
- `appointments`
- `patients`
- `treatments`
- `billing`

## 📊 Key Insights and Recommendation
- Pediatrics has the highest appointments.
- The Central Branch shows the highest number of cancellations.
- **Recommendation**: Investigate causes – doctor availability, long wait times, or patient drop-offs.

- Tuesdays and Wednessdays show the highest patient traffic

### 👨‍⚕️ Doctor Productivity
- **Revenue by Doctor**: - Dr. Sarah Talyor (Demartalogy, Central) – $33,836,Dr. Alex Davis (Pediatrics, Central) – $25,698
- **Appointment Distribution**:Dr.Sarah Taylor (Central hospital) has the highest appointment 29 While Dr.Robert Davis (Westside Clinic) has the least appointments 13
- Appointment load is unevenly distributed among doctors, leading to potential overwork.
  
### Total Revenue by Payment Status
- **Paid**: $173,424
- **Pending**: $184,612
- **Failed**: $193,212
- **Insight**: Improve recovery on pending bills and reduce failed payments with automated alerts.

- **Failed rate count**:Cash(23), Credit card(23) and Insurance (21).
- **Recommendation**No single payment method dominates in failure rate;this suggests that the failures are systemic. Invesigate common cause across all payment methods(such as downtime,incorrect customer details, or transaction limits) and implement monitoring to reduce overall failure rate.

- **Top Insurance Providers**: MedCare Plus	18 patients and WellnessCorp with	16 patients.

### 🧑‍🤝‍🧑 Patient Segmentation
- 10 patients account for 20% of total hospital revenue
- Recommendation: Enroll them in VIP health plans or loyalty programs

  
