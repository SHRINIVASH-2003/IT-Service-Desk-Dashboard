# 🖥️ IT Service Desk Executive Operations & SLA Performance Dashboard

An interactive **Power BI** dashboard built to give IT Service Desk leadership a real-time, end-to-end view of ticket operations — from incident volume and resolution performance to SLA compliance, team workload, and customer satisfaction.

![Status](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi&logoColor=black)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-blue)

---

## 📌 Overview

The **IT Service Desk Executive Operations & SLA Performance Dashboard** consolidates incident management data into a single, executive-ready view. It enables IT operations managers and support leads to monitor service health, identify bottlenecks, track SLA adherence, and evaluate team and channel performance — all through interactive, filterable visuals.

This project was designed and built independently, covering the full workflow of data modeling, DAX measure creation, and dashboard/report design in Power BI.

---

## 🎯 Key Objectives

- Provide a single-page, at-a-glance view of IT Service Desk performance
- Track SLA compliance and resolution efficiency in real time
- Break down incidents by category, priority, team, region, and channel
- Surface root causes driving recurring incidents
- Monitor customer satisfaction alongside operational metrics

---

## 📊 Dashboard Features

| Section | Visual Type | Description |
|---|---|---|
| Total Incident Count | KPI Card | Total number of incidents logged |
| Total Resolved Count | KPI Card | Total number of incidents resolved |
| Average Resolution Time | KPI Card | Average time taken to resolve an incident |
| SLA Compliance Rate | KPI Card | Percentage of incidents resolved within SLA |
| Customer Satisfaction Rating | KPI Card | Star-rated customer satisfaction score |
| Total Incident Count by Category | Clustered Bar Chart | Incident volume broken down by category |
| Priority Wise Breakdown | Pie Chart | Distribution of incidents by priority level |
| Resolved Incidents by Team | Line & Clustered Column Combo | Resolution performance across assignment groups/teams |
| Root Cause Analysis Breakdown | Funnel Chart | Incidents by root cause, from highest to lowest impact |
| Resolved Incidents by Employee | Table | Resolution counts per assigned employee |
| Incident Response Status | Line Chart | Trend of incident status over time |
| Incident Reported Channels | Donut Chart | Volume of incidents by reporting channel |
| Quarter / Region Filters | Slicers | Dynamic filtering across the entire report |

---

## 🧮 Data Model

The report is built on a **star-schema-style data model** with the following tables:

- **Fact-Details** – Core fact table containing incident-level records and measures (Total Incident Count, Total Resolved Incidents, Average Resolution Time, SLA Compliance Rate, etc.)
- **Category** – Dimension table for incident categories
- **Region** – Dimension table for geographic/regional breakdown
- **Date** – Date dimension enabling time intelligence (quarter, trend analysis)

Key DAX measures include:
- `Total Incident Count`
- `Total Resolved Incident`
- `Average Resolution Time`
- `SLA Compliance Rate`
- `Customer Satisfaction Rating Display`

---

## 🛠️ Tools & Technologies

- **Power BI Desktop** – Data modeling, DAX, and report design
- **DAX (Data Analysis Expressions)** – Custom KPI and time-intelligence measures
- **Power Query (M)** – Data transformation and cleaning
- **Custom Theme** – Dark Cyber Blue theme for a modern, executive-style UI

---

## 🖼️ Preview

> Add a screenshot of your dashboard here so visitors can preview it without downloading the file:
>
> ```markdown
> ![Dashboard Preview](assets/dashboard-preview.png)
> ```

---

## 📂 Repository Structure

```
IT-Service-Desk-Dashboard/
│
├── IT_Service_Desk_Dashboard.pbix   # Power BI dashboard file
├── assets/                          # Screenshots / preview images
└── README.md                        # Project documentation
```

---

## 🚀 How to Use

1. Clone or download this repository.
2. Open `IT_Service_Desk_Dashboard.pbix` in **Power BI Desktop** (free download from Microsoft).
3. If connected to a live data source, update the data source credentials/connection under **Home → Transform Data → Data Source Settings**.
4. Use the **Quarter** and **Region** slicers to filter the report interactively.

> 🔒 Note: If the dashboard uses sample/demo data, no additional setup is required — it will open and render as-is.

---

## 📈 Key Insights Enabled

- Identify which incident **categories** and **priorities** drive the most volume
- Track **SLA compliance trends** to flag at-risk service levels early
- Compare **team-level resolution performance** to balance workload
- Pinpoint **recurring root causes** to support proactive problem management
- Monitor **customer satisfaction** alongside operational KPIs

---

## 👤 Author

Built and designed independently as a self-driven Power BI project.

Feel free to connect, fork, or reach out with feedback and suggestions!

---

## 📄 License

This project is open for learning and portfolio purposes. Feel free to reference the structure and approach for your own dashboards.
