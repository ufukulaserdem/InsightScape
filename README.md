# 📊 InsightScape – End-to-End Monitoring on Azure

**InsightScape** is a practical observability project focused on monitoring applications and infrastructure in Azure using native tools like Log Analytics, Azure Monitor, Application Insights, and Dashboards. It simulates a real-world telemetry pipeline with proactive alerting and rich visual insights.

![InsightScape Diagram](./Insightscape.png)

---

## 📌 Project Goals

- Create and configure a **Log Analytics Workspace**
- Collect metrics and diagnostics from VMs and App Services
- Enable **Application Insights** for real-time app telemetry
- Run **KQL** queries to analyze log data
- Visualize insights using Azure Dashboards
- Configure **Alerts** for application and infrastructure health

---

## 🧱 Architecture Components

| Component             | Description |
|----------------------|-------------|
| Azure Monitor         | Central hub for observability |
| Log Analytics Workspace | Collects logs from Azure resources |
| Application Insights  | Gathers app-level telemetry like requests, exceptions |
| Azure Dashboard       | Displays charts, metrics, and logs |
| Alerts                | Triggered by thresholds and performance indicators |
| App Service / VM      | Sample resource for sending metrics and logs |

---

## ⚙️ Deployment Steps

Each step is documented in Obsidian-compatible markdown files:

1. `1.0_Create_Resource_Group_and_Log_Analytics.md`  
2. `2.0_Connect_Resources_to_Log_Analytics.md`  
3. `3.0_Install_and_Query_Azure_Monitor_Logs.md`  
4. `4.0_Setup_Application_Insights.md`  
5. `5.0_Create_Custom_Dashboard_and_Alerts.md`

---

## ✅ Prerequisites

- Azure subscription
- Basic familiarity with Azure CLI or Azure Portal
- [AZ-104](https://learn.microsoft.com/en-us/certifications/exams/az-104/) and [AZ-400](https://learn.microsoft.com/en-us/certifications/exams/az-400/) preparation

---

## 📁 File Structure

```
📦InsightScape
 ┣ 📄 README.md
 ┣ 📄 1.0_Create_Resource_Group_and_Log_Analytics.md
 ┣ 📄 2.0_Connect_Resources_to_Log_Analytics.md
 ┣ 📄 3.0_Install_and_Query_Azure_Monitor_Logs.md
 ┣ 📄 4.0_Setup_Application_Insights.md
 ┣ 📄 5.0_Create_Custom_Dashboard_and_Alerts.md
 ┗ 📷 Insightscape.png
```

---

## 🧠 Learning Outcomes

- Understand core Azure monitoring components and relationships
- Apply KQL for log data exploration
- Use dashboards and alerts to track app health
- Gain hands-on skills aligned with AZ-104 and AZ-400 certification paths