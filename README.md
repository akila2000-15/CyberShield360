# 🛡️ CyberShield360 — Cybersecurity Analytics Dashboard

> **An end-to-end cybersecurity analytics and business intelligence project built with Power BI, Python, SQL, and DAX to monitor security threats, vulnerabilities, firewall activity, malware, phishing, incidents, and organizational risk.**

![Power BI](https://img.shields.io/badge/Power%20BI-Data%20Analytics-yellow)
![Python](https://img.shields.io/badge/Python-Data%20Processing-blue)
![SQL](https://img.shields.io/badge/SQL-Database-orange)
![DAX](https://img.shields.io/badge/DAX-Power%20BI-purple)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Processing-blue)
![GitHub](https://img.shields.io/badge/GitHub-Portfolio-black)

---

## 📌 Project Overview

**CyberShield360** is an end-to-end **Cybersecurity Business Intelligence and Data Analytics Dashboard** designed to transform large-scale security data into actionable insights.

The project combines **Python-based data generation and preprocessing, SQL database management, data modeling, Power BI visualization, and DAX analytics** to provide a centralized view of an organization's cybersecurity posture.

The dashboard enables security and management teams to analyze:

* 🔐 User and device security
* 🚨 Security incidents
* 🎣 Phishing email activity
* 🦠 Malware detection
* 🔥 Firewall traffic and threats
* ⚠️ Vulnerabilities
* 🛡️ Antivirus status
* 📊 Risk scores
* 🌍 Geographic security trends
* 📈 Security activity over time

---

## 🎯 Project Objectives

The primary objectives of CyberShield360 are to:

1. Build a realistic cybersecurity analytics dataset.
2. Clean and transform raw data using Python.
3. Store and manage structured security data using SQL.
4. Design a scalable analytical data model.
5. Create meaningful relationships between cybersecurity entities.
6. Develop interactive Power BI dashboards.
7. Implement DAX measures for KPI and risk analysis.
8. Identify cybersecurity trends and high-risk areas.
9. Present complex security information through recruiter-friendly visualizations.
10. Demonstrate an end-to-end **Data Analytics / Business Intelligence workflow**.

---

# 🏗️ End-to-End Data Analytics Workflow

```text
Raw Data
   ↓
Python Data Generation
   ↓
Data Cleaning & Transformation
   ↓
CSV Dataset
   ↓
SQL Database
   ↓
Data Validation
   ↓
Power BI Data Modeling
   ↓
DAX Measures
   ↓
Interactive Dashboard
   ↓
Cybersecurity Insights
```

---

# 🧰 Technology Stack

| Category              | Technologies          |
| --------------------- | --------------------- |
| Business Intelligence | Power BI              |
| Data Visualization    | Power BI              |
| Programming           | Python                |
| Data Processing       | Pandas, NumPy         |
| Database              | MySQL / SQL Server    |
| Database Tools        | MySQL Workbench, SSMS |
| Analytics             | DAX                   |
| Data Modeling         | Star Schema           |
| Data Storage          | CSV, SQL              |
| Development           | VS Code               |
| Version Control       | Git & GitHub          |

---

# 📊 Dataset Overview

CyberShield360 uses a large synthetic cybersecurity dataset designed to simulate enterprise security operations.

| Dataset            | Records |
| ------------------ | ------: |
| Users              |   5,000 |
| Departments        |       8 |
| Countries          |      20 |
| Calendar           |   3,287 |
| Devices            |   8,000 |
| Login Logs         | 100,000 |
| Firewall Logs      | 200,000 |
| Malware            |  30,000 |
| Phishing Emails    |  20,000 |
| Security Incidents |  15,000 |
| Vulnerabilities    |  25,000 |
| Antivirus          |   8,000 |
| Risk Score         |  50,000 |

**Total records:** 500,000+ cybersecurity-related records across multiple datasets.

> **Note:** The dataset is synthetic and intended for analytics, visualization, portfolio demonstration, and educational purposes.

---

# 🗂️ Dataset Components

### 👤 Users

Contains employee/user information such as:

* User ID
* Department
* Country
* Role
* Account status
* Risk-related attributes

### 💻 Devices

Tracks organizational devices and security information.

Example attributes:

* Device ID
* User ID
* Device type
* Operating system
* Location
* Security status

### 🔐 Login Logs

Captures authentication activity.

Used to analyze:

* Successful logins
* Failed logins
* Suspicious authentication
* Login trends
* Geographic activity

### 🔥 Firewall Logs

Provides network security activity.

Used to analyze:

* Allowed traffic
* Blocked traffic
* Attack attempts
* Source/destination information
* Protocol activity

### 🦠 Malware

Tracks malware detection and classification.

Used to identify:

* Malware types
* Detection trends
* Affected devices
* Severity
* Geographic distribution

### 🎣 Phishing Emails

Analyzes phishing-related email activity.

Metrics include:

* Total phishing emails
* Detection rate
* Severity
* Email status
* Target departments
* Time-based trends

### 🚨 Security Incidents

Tracks cybersecurity incidents and their severity.

Used for:

* Incident monitoring
* Severity analysis
* Department-level analysis
* Resolution tracking
* Incident trends

### ⚠️ Vulnerabilities

Provides vulnerability management information.

Analyzes:

* Vulnerability severity
* Affected systems
* Critical vulnerabilities
* Remediation status
* Risk exposure

### 🛡️ Antivirus

Tracks endpoint security and antivirus status.

### 📈 Risk Score

Provides risk-level information for users, devices, and security entities.

---

# 🧠 Data Modeling

The Power BI model follows a **Star Schema approach** to improve analytical performance and maintainability.

### Core Dimensions

* DimUser
* DimDepartment
* DimCountry
* DimDevice
* DimCalendar

### Fact Tables

* FactLoginLogs
* FactFirewallLogs
* FactMalware
* FactPhishingEmails
* FactSecurityIncidents
* FactVulnerabilities
* FactAntivirus
* FactRiskScore

### Conceptual Model

```text
                  DimCalendar
                       │
                       │
DimDepartment ─── FactSecurity ─── DimUser
                       │
                       │
                   DimDevice
                       │
                       │
                  DimCountry
```

Additional cybersecurity fact tables are connected through appropriate dimension keys.

---

# 📈 Power BI Dashboard

CyberShield360 contains multiple analytical dashboard pages designed for different cybersecurity use cases.

## 🏠 1. Executive Security Overview

Provides a high-level view of the organization's cybersecurity posture.

### Key KPIs

* Total Security Incidents
* Critical Incidents
* Total Vulnerabilities
* Phishing Threats
* Malware Detection
* Blocked Firewall Events
* Average Risk Score
* High-Risk Users/Devices

---

# 🎣 2. Phishing Analytics

Analyzes phishing email activity across the organization.

### Key Analysis

* Phishing emails over time
* Severity distribution
* Department-wise phishing activity
* Country-wise phishing trends
* Detection status
* High-risk departments
* Monthly phishing trends

---

# 🔥 3. Firewall Analytics

Provides visibility into network security activity.

### Key Analysis

* Total firewall events
* Allowed vs blocked traffic
* Attack attempts
* Protocol distribution
* Source country analysis
* Destination analysis
* Threat trends over time

---

# 🦠 4. Malware Dashboard

Analyzes malware threats affecting the organization.

### Key Analysis

* Malware detection count
* Malware severity
* Malware type distribution
* Affected devices
* Department-level malware activity
* Malware trend analysis

---

# 🚨 5. Security Incident Dashboard

Provides detailed incident monitoring.

### Key Analysis

* Incident volume
* Incident severity
* Incident status
* Department-wise incidents
* Country-wise incidents
* Resolution trends
* Critical incident monitoring

---

# ⚠️ 6. Vulnerability Dashboard

Provides vulnerability management insights.

### Key Analysis

* Total vulnerabilities
* Critical vulnerabilities
* High-severity vulnerabilities
* Vulnerability status
* Affected systems
* Department-level exposure
* Remediation trends

---

# 📊 7. Risk Score Dashboard

Provides a centralized view of cybersecurity risk.

### Key Analysis

* Average risk score
* High-risk users
* High-risk devices
* Risk distribution
* Department risk comparison
* Country risk comparison
* Risk trends over time

---

# 📐 DAX Analytics

The project uses **DAX (Data Analysis Expressions)** to create analytical measures and KPIs.

### Example Measures

```DAX
Total Incidents =
COUNTROWS(FactSecurityIncidents)
```

```DAX
Critical Incidents =
CALCULATE(
    COUNTROWS(FactSecurityIncidents),
    FactSecurityIncidents[Severity] = "Critical"
)
```

```DAX
Total Phishing Emails =
COUNTROWS(FactPhishingEmails)
```

```DAX
Average Risk Score =
AVERAGE(FactRiskScore[RiskScore])
```

```DAX
High Risk Count =
CALCULATE(
    COUNTROWS(FactRiskScore),
    FactRiskScore[RiskLevel] = "High"
)
```

> These measures demonstrate practical use of **DAX aggregation, filtering, calculated KPIs, and analytical logic**.

---

# 🔍 Key Analytical Capabilities

The dashboard supports:

### Time Intelligence

* Daily trends
* Monthly trends
* Yearly analysis
* Period comparisons

### Geographic Analysis

* Country-level security activity
* High-risk regions
* Threat distribution

### Organizational Analysis

* Department-wise incidents
* Department risk comparison
* Phishing exposure
* Vulnerability distribution

### Threat Analysis

* Malware trends
* Phishing attacks
* Firewall events
* Security incidents
* Vulnerability severity

### Risk Analysis

* User risk
* Device risk
* Department risk
* Overall organizational risk

---

# 🎛️ Interactive Features

The Power BI dashboard includes interactive analytical capabilities such as:

* Date slicers
* Department slicers
* Country filters
* Severity filters
* Threat-type filters
* Drill-down analysis
* Cross-filtering
* Interactive charts
* KPI cards
* Trend analysis

These features allow users to move from **high-level executive KPIs to detailed cybersecurity investigation**.

---

# 🐍 Python Data Processing

Python was used to generate, process, and prepare the cybersecurity datasets.

### Libraries

```text
Python
├── Pandas
├── NumPy
└── Faker
```

### Example Workflow

```python
import pandas as pd
import numpy as np
from faker import Faker

fake = Faker()

# Load dataset
df = pd.read_csv("security_incidents.csv")

# Basic inspection
print(df.head())
print(df.info())

# Missing-value analysis
print(df.isnull().sum())
```

Python was primarily used for:

* Synthetic data generation
* Data preprocessing
* Data validation
* Data cleaning
* CSV generation
* Dataset preparation

---

# 🗄️ SQL Database

SQL was used to store and manage structured cybersecurity data.

### SQL Workflow

```text
CSV Files
   ↓
SQL Database
   ↓
Tables
   ↓
Data Validation
   ↓
Relationships
   ↓
Power BI
```

SQL skills demonstrated in the project include:

* Database creation
* Table creation
* Data loading
* SELECT queries
* Filtering
* Aggregation
* GROUP BY
* JOIN operations
* Data validation
* Relationship management

---

# 📁 Suggested Project Structure

```text
CyberShield360/
│
├── README.md
│
├── data/
│   ├── users.csv
│   ├── departments.csv
│   ├── countries.csv
│   ├── calendar.csv
│   ├── devices.csv
│   ├── login_logs.csv
│   ├── firewall_logs.csv
│   ├── malware.csv
│   ├── phishing_emails.csv
│   ├── security_incidents.csv
│   ├── vulnerabilities.csv
│   ├── antivirus.csv
│   └── risk_score.csv
│
├── python/
│   ├── data_generation.py
│   └── data_cleaning.py
│
├── sql/
│   ├── database_schema.sql
│   ├── table_creation.sql
│   └── analysis_queries.sql
│
├── powerbi/
│   └── CyberShield360.pbix
│
├── screenshots/
│   ├── executive-dashboard.png
│   ├── phishing-dashboard.png
│   ├── firewall-dashboard.png
│   ├── malware-dashboard.png
│   ├── incident-dashboard.png
│   ├── vulnerability-dashboard.png
│   └── risk-dashboard.png
│
└── documentation/
    └── data-model.png
```

---

# 🖼️ Dashboard Preview

Add your Power BI screenshots to the `screenshots` folder and update the image names below.

### Executive Security Dashboard

![Executive Dashboard](screenshots/executive-dashboard.png)

### Phishing Analytics

![Phishing Dashboard](screenshots/phishing-dashboard.png)

### Firewall Analytics

![Firewall Dashboard](screenshots/firewall-dashboard.png)

### Malware Analytics

![Malware Dashboard](screenshots/malware-dashboard.png)

### Security Incidents

![Security Incidents](screenshots/incident-dashboard.png)

### Vulnerability Analytics

![Vulnerability Dashboard](screenshots/vulnerability-dashboard.png)

### Risk Score Analytics

![Risk Dashboard](screenshots/risk-dashboard.png)

---

# 💡 Business Value

CyberShield360 demonstrates how raw cybersecurity data can be converted into **actionable business intelligence**.

The dashboard can help security teams:

* Identify high-risk departments
* Monitor security incidents
* Detect phishing trends
* Track malware activity
* Monitor firewall threats
* Prioritize critical vulnerabilities
* Identify high-risk users and devices
* Understand security trends over time
* Support data-driven cybersecurity decisions

---

# 🔐 Data & Security Disclaimer

This project uses **synthetic cybersecurity data** generated for educational and portfolio purposes.

No real customer information, confidential company data, credentials, or personally identifiable information is included.

The project is intended to demonstrate:

* Data Analytics
* Business Intelligence
* Power BI
* Cybersecurity Analytics
* SQL
* Python
* DAX
* Data Modeling

---

# 🚀 Future Enhancements

Potential improvements include:

* [ ] Real-time cybersecurity monitoring
* [ ] Automated data refresh
* [ ] Power BI Service deployment
* [ ] Row-Level Security (RLS)
* [ ] Automated email alerts
* [ ] Machine Learning-based risk prediction
* [ ] Anomaly detection
* [ ] Threat intelligence integration
* [ ] Azure Sentinel / Microsoft Defender integration
* [ ] Automated ETL pipelines
* [ ] Predictive cybersecurity analytics
* [ ] AI-powered security recommendations

---

# 🎓 Skills Demonstrated

### Data Analytics

* Data Cleaning
* Data Transformation
* Exploratory Data Analysis
* KPI Development
* Trend Analysis
* Business Intelligence

### Power BI

* Dashboard Development
* Data Modeling
* Star Schema
* DAX
* Measures
* KPI Cards
* Slicers
* Drill-down
* Interactive Visualizations
* Power BI Data Analytics

### SQL

* Database Design
* Table Creation
* Data Management
* Joins
* Aggregations
* Data Validation
* Query Development

### Python

* Pandas
* NumPy
* Faker
* Data Generation
* Data Cleaning
* Data Processing

### Cybersecurity Analytics

* Phishing Analysis
* Malware Analysis
* Firewall Monitoring
* Vulnerability Analysis
* Security Incident Analysis
* Risk Score Analysis
* Threat Monitoring

---

# 📌 Resume Project Description

You can use the following description in your resume:

**CyberShield360 – Cybersecurity Analytics Dashboard | Power BI, Python, SQL, DAX**

> Developed an end-to-end cybersecurity analytics solution using Power BI, Python, SQL, and DAX to analyze 500K+ synthetic security records across phishing, malware, firewall logs, vulnerabilities, incidents, devices, and risk scores. Designed a star-schema data model, developed interactive dashboards and KPI measures, and transformed raw security data into actionable insights for threat monitoring, vulnerability management, and organizational risk analysis.

---

# 📈 Resume Bullet Points

* Developed an interactive **Power BI cybersecurity dashboard** analyzing 500K+ synthetic security records across multiple threat domains.
* Built **DAX measures and KPI dashboards** to monitor incidents, phishing threats, malware detection, vulnerabilities, firewall activity, and risk scores.
* Designed a **star-schema analytical data model** with fact and dimension tables for scalable Power BI reporting.
* Used **Python, Pandas, NumPy, and Faker** for synthetic data generation, preprocessing, validation, and dataset preparation.
* Used **SQL** for structured data storage, querying, validation, and analytical data preparation.
* Created interactive Power BI reports with **slicers, drill-downs, cross-filtering, KPI cards, trend analysis, and security analytics**.
* Transformed complex cybersecurity datasets into **actionable business intelligence and risk insights**.

---

# 🔎 ATS Keywords

```text
Power BI
Business Intelligence
Data Analytics
Data Visualization
DAX
SQL
Python
Pandas
NumPy
Data Modeling
Star Schema
ETL
Data Cleaning
Data Transformation
KPI
Dashboard Development
Cybersecurity Analytics
Security Analytics
Risk Analysis
Threat Analysis
Phishing Analytics
Malware Analytics
Firewall Analytics
Vulnerability Management
Security Incident Analysis
Data Analysis
Business Analytics
Interactive Dashboard
Reporting
Data Visualization
SQL Server
MySQL
Git
GitHub
```

---

# 👩‍💻 Author

**Akila E.**

**Software Developer | Data Analytics & Power BI Enthusiast**

### Technical Interests

* Power BI & Business Intelligence
* Data Analytics
* Python Development
* SQL
* Dashboard Development
* Cybersecurity Analytics
* Full-Stack Development

---

# ⭐ Project Highlights

| Area          | Achievement             |
| ------------- | ----------------------- |
| Data Volume   | 500K+ synthetic records |
| Datasets      | 13                      |
| BI Tool       | Power BI                |
| Programming   | Python                  |
| Database      | SQL                     |
| Analytics     | DAX                     |
| Data Model    | Star Schema             |
| Visualization | Interactive Dashboards  |
| Domain        | Cybersecurity Analytics |

---

## 📬 Portfolio

This project is part of my data analytics and software development portfolio, demonstrating practical experience in **Power BI, Python, SQL, DAX, data modeling, visualization, and cybersecurity analytics**.

⭐ **If you find this project useful, consider giving the repository a star.**

---
