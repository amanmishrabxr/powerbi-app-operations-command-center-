# Enterprise Mobile App Telemetry & Live Operations Command Center

An enterprise-grade operational analytics dashboard built with **Microsoft Power BI** and **DAX** to monitor mobile app health, user crash telemetry, real-time engagement, and monetization streams.

---

## 📊 Dashboard Previews

### Executive Command Center
![Command Center Overview](./Screenshot%202026-10-25%20105645.png)

### Telemetry & Crash Performance Drilldown
![Telemetry View](./Screenshot%202026-10-25%20115315.png)

---

## 📁 Repository Deliverables

| Deliverable | Description | File Link |
| :--- | :--- | :--- |
| **Power BI Dashboard** | Full interactive data model, DAX measures, and visual reports | [powerbi-app-operations-command-center.pbix](./powerbi-app-operations-command-center.pbix) |
| **Project Documentation** | Comprehensive analytical report & methodology | [power bi report file.pdf](./power%20bi%20report%20file.pdf) |

---

## 🗄️ Datasets

The dashboard models telemetry and user cohorts using the following root datasets:

* `FactEvents.csv` – Interaction telemetry, session triggers, and feature usage events.
* `FactCrashes.csv` – Exception details, stack traces, device hardware, and OS versions.
* `FactUsers.csv` – Demographic cohorts, install attributes, and geographic distribution.
* `FactRevenue.csv` – In-app purchases, transaction conversions, and monetary clearing.
* `DimDate.csv` – Standardized calendar dimension supporting time intelligence calculations.

---

## ⚙️ Setup & Reproduction Guide

### Prerequisites
- [Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/) (Windows)
- [Git](https://git-scm.com/)

### Steps to Run Locally
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/amanmishrabxr/powerbi-app-operations-command-center-.git](https://github.com/amanmishrabxr/powerbi-app-operations-command-center-.git)
   cd powerbi-app-operations-command-center-
