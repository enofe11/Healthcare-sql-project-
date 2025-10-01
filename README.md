# Healthcare-sql-project-
This project performs **Exploratory Data Analysis (EDA)** on a hospital management database to uncover meaningful insights related to **appointments**, **doctor productivity**, **revenue**, **billing**, **insurance usage**, and **patient behavior**. 
The analysis was done using SQL queries to address key business and operational questions that can support better decision-making within the hospital.

## 🧠 Problem Statement

Hospitals generate vast amounts of data across multiple departments. However, without proper analysis, this data remains underutilized. This project aims to analyze hospital data to:

- Identify departments with the highest appointments.
- Detect operational inefficiencies.
- Understand patient behavior and value.
- Optimize insurance and payment systems.
- Improve overall healthcare service delivery.

## 📥 Data Source
**Source** https://www.kaggle.com/datasets/kanakbaghel/hospital-management-dataset
The dataset used in this project simulates a **Hospital Management System** and includes tables such as:
- `doctors`
- `appointments`
- `patients`
- `treatments`
- `billing`

## 📊 Key Insights and Recommendation
### 🛠 Operational Insights
- **Top Specializations by Appointment**: Pediatrics has the highest appointments.
- The Central Branch shows the highest number of cancellations.
- **Recommendation**: Investigate causes – doctor availability, long wait times, or patient drop-offs.

- **Peak Appointment Days**:Tuesdays and Wednessdays show the highest patient traffic

- **Appointment Status by Branch**: Some branches experience higher cancellation rates, suggesting process inefficiencies.
- **Peak Appointment Days**:Tuesdays and Wednessdays show the highest patient traffic.

### 👨‍⚕️ Doctor Productivity
- **Revenue by Doctor**: - Dr. Sarah Talyor (Demartalogy, Central) – $33,836
  - Dr. Alex Davis (Pediatrics, Central) – $25,698
- **Appointment Distribution**: Appointment load is unevenly distributed among doctors, leading to potential overwork.

### 💳 Revenue & Billing Analysis
### 🧾 Total Revenue by Payment Status
- **Paid**: $173,424
- **Pending**: $184,612
- **Failed**: $193,212
- **Insight**: Improve recovery on pending bills and reduce failed payments with automated alerts.

- **Failed Payments**: Credit card and mobile payment methods show the highest failure rates.

### 🏦 Insurance Optimization
- **Top Insurance Providers**: A small number of insurance companies cover the majority of patients, but some underperform in payment reliability.

### 🧑‍🤝‍🧑 Patient Segmentation
- **Top Spending Patients**: A small percentage of patients are responsible for a high portion of total payments.
- **Frequent Visitors**: Patients with chronic or recurring needs represent opportunities for care plan optimization.

---
  
