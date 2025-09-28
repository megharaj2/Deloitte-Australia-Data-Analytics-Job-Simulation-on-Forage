# Deloitte Job Simulation – Data Analysis & Forensic Technology

This repository contains my work for the **Deloitte Job Simulation (Forage platform)**.  
The case study was based on Daikibo Industrials, focusing on **factory telemetry analysis** 
and **forensic technology (gender pay equality)**.

---

## 🔍 Project Overview

### Task 1 – Telemetry Data Analysis (Tableau)
- Analysed machine health telemetry data from **4 global factories**.
- Created a calculated field "Unhealthy" (10 = 10 mins downtime).
- Built 2 interactive bar charts:
  - **Down Time per Factory**
  - **Down Time per Device Type**
- Designed a **dashboard** linking both charts:
  - Selecting a factory filters machine downtime.
- Identified the factory and device type with the most downtime.

📂 Files:
- `tableau/downtime_dashboard.twbx`
- `tableau/dashboard_screenshot.png`

---

### Task 2 – Forensic Technology (Excel)
- Analysed **gender pay equality** scores across factories and job roles.
- Added a new column **Equality Class** based on the rules:
  - **Fair**: score between -10 and +10  
  - **Unfair**: score < -10 or > 10  
  - **Highly Discriminative**: score < -20 or > 20  
- Produced a clean, classified dataset.

📂 Files:
- `excel/Equality Table - Classified.xlsx`

---

## 🛠️ Tools Used
- **Tableau**: Data visualization, dashboards
- **Excel**: Data classification, forensic analysis
- **Forage Platform**: Deloitte Job Simulation tasks

---

## 📂 Repository Structure

```text
deloitte-job-simulation/
│
├── data/                
│   ├── daikibo-telemetry-data.json        # Telemetry dataset (if allowed, else synthetic sample)
│   ├── Equality Table.xlsx                # Provided Excel dataset
│
├── tableau/             
│   └── dashboard_screenshot.png           # Final screenshot submission
│
├── excel/               
│   └── Equality Table - Classified.xlsx   # Completed Excel forensic task
│          
└── README.md 
```

---


## 📊 Key Deliverables
- Tableau dashboard to analyze machine downtime
- Excel file with classified gender equality scores
- Business insights into operational inefficiencies and workforce equality

