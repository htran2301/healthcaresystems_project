# healthcaresystems_project
Mainly work on Databricks: healthcare monitoring system analyzing patient records and clinical metrics to identify high-risk patients and evaluate chronic disease treatments.
# Healthcare Monitoring System – Databricks

## 📌 Project Overview
This project designs and implements a **healthcare monitoring and analytics system** using Databricks to analyze patient demographics, clinical metrics, and prescription data. The system focuses on identifying **high-risk patients**, monitoring **chronic disease indicators**, and supporting **early intervention and follow-up decisions**, with a case study centered on **Type 2 Diabetes**.

The project demonstrates how scalable data platforms can support proactive, data-driven healthcare management.

---

## 🎯 Objectives
- Monitor chronic disease indicators using patient and clinical data  
- Identify high-risk patients requiring immediate attention or follow-up  
- Evaluate treatment effectiveness for Type 2 Diabetes therapies  
- Demonstrate scalable data management and analytics using Databricks  

---

## 🗂️ Data Description
The project uses **synthetically generated healthcare data** (1,000 records) representing:
- Patient demographics  
- Chronic disease diagnoses  
- Clinical measurements (e.g., glucose, heart rate, blood pressure, creatinine)  
- Prescription and therapy information  

Chronic conditions included:
- Heart Disease  
- Asthma  
- COPD  
- Hypertension  
- Chronic Kidney Disease  
- **Type 2 Diabetes** (primary focus)

---

## 🔄 Project Workflow

### 1. Data Ingestion
- Loaded multiple structured tables into Databricks
- Organized data into a healthcare-style schema for analysis

---

### 2. Data Management & Preparation
- Cleaned and standardized clinical and prescription records  
- Joined patient, disease, and treatment tables using SQL  
- Validated numerical ranges for clinical metrics  

---

### 3. Analytical SQL Queries
Developed analytical queries to:
- Identify patients with **dangerous clinical readings**
- Detect patients **overdue for follow-up** (>30 days)
- Compare therapy effectiveness for Type 2 Diabetes
- Flag patients classified as **“Severe”** vs “Resolved” or “In Remission”

---

### 4. Key Insights
- Identified patients with dangerous glucose and creatinine levels  
- Found gaps in follow-up care across multiple chronic conditions  
- Observed strongest glucose improvement in patients receiving **Insulin**, followed by **Metformin**  
- Highlighted the need for automated alerts and patient outreach systems  

---

### 5. Business Value
The monitoring system:
- Enables **early identification of at-risk patients**
- Reduces reliance on manual tracking and reporting
- Supports proactive follow-up and treatment evaluation
- Demonstrates how Databricks can scale healthcare analytics workflows

---

## 🧠 Tools & Technologies
- Databricks  
- SQL  
- Delta Lake  
- Jupyter / Databricks Notebooks  

---

## ⚠️ Limitations
- Data is **synthetic** and used for educational purposes  
- Analysis scope focuses primarily on Type 2 Diabetes  
- Real-world deployment would require compliance with healthcare privacy regulations (HIPAA)

---

## 📈 Outcome
This project illustrates how a **data-driven healthcare monitoring system** can improve patient follow-up, identify clinical risks early, and support better healthcare decision-making using modern analytics platforms.

