# Call-Center-Analytics-Dashboard-project
This project extracts call center data from APIs, transforms and cleans the data in Microsoft Fabric, stores it in a reporting-ready model, and delivers interactive Power BI dashboards for business users.

**Business Problem**

The organization required visibility into call center performance metrics, agent productivity, customer interactions, and service levels. Data was available through operational APIs but lacked a centralized reporting and analytics solution.

Call Center API
      │
      ▼
Fabric Data Pipeline
(API Ingestion)
      │
      ▼
Data Transformation
(Dataflow Gen2 / Notebook)
      │
      ▼
Fabric Warehouse
      │
      ▼
Power BI Dashboard


<img width="1693" height="929" alt="image" src="https://github.com/user-attachments/assets/844691e3-7ab0-46e0-a4c4-31058e5af356" />


**Dashboard KPIs**
Total Calls
Answered Calls
Abandoned Calls
Average Handle Time (AHT)
Average Wait Time
Service Level %
First Call Resolution
Agent Productivity
Call Volume Trends
Queue Performance



| Technology                | Purpose               |
| ------------------------- | --------------------- |
| API                       | Source System         |
| Microsoft Fabric Pipeline | Data Ingestion        |
| Dataflow Gen2 / Notebook  | Transformation        |
| Fabric Warehouse          | Data Storage          |
| Power BI                  | Reporting & Analytics |



<img width="1381" height="763" alt="image" src="https://github.com/user-attachments/assets/b367fdbe-28a5-459c-9e3c-ddb6e075eebd" />

