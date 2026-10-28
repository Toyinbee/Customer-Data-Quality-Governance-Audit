# Customer Data Quality & Governance Audit
**Power BI Portfolio Project | Safeguard Insurance Limited**

---

## 📌 Project Overview

This project focuses on checking the quality of customer data for a simulated insurance company, Safeguard Insurance Limited.

I used Power Query and Power BI to identify missing information, invalid values, and possible duplicate records. I then created dashboards to present the findings and recommend actions the business could take to improve its data quality.

> 💡 **The goal:** Turn messy customer data into clear findings that support better business decisions.

---

## 🎯 The Business Problem

Customer information is critical to an insurance company. When records contain missing or incorrect details, it becomes difficult to contact customers, maintain accurate records, and produce reliable reports.

Safeguard Insurance Limited needed a clearer way to identify these issues and understand which records required attention.

---

## 💡 Project Objectives

- Identify missing and incorrect customer information
- Flag records that may need further review
- Summarise data quality issues in a Power BI dashboard
- Recommend practical actions to improve data quality
- Highlight simple ways to support better data management

---

## 🛠️ Tools Used

| Tool | Purpose |
|---|---|
| Microsoft Excel | Source dataset |
| Power Query | Prepared the data and created quality checks |
| Power BI | Built the dashboards and presented the findings |
| DAX | Created calculations for the report |
| GitHub | Project documentation and portfolio presentation |

---

## 🔍 What I Did

### 1. Prepared the Data
I worked with a synthetic dataset of 1,250 customer records. I reviewed the fields and prepared checks to identify information that was missing or appeared invalid. The original raw data was preserved throughout so nothing was permanently changed.

### 2. Checked Data Quality
I created flag columns in Power Query for nine types of quality issues:
- Missing names, email addresses, phone numbers, and cities
- Invalid email and phone number formats
- Invalid signup dates and dates of birth
- Invalid premium values
- Potential duplicate records

A master "Needs Review" flag was then created to mark any record that had at least one issue.

### 3. Built the Dashboard
I created two Power BI report pages connected by a navigation sidebar.

**Executive Overview** — for business stakeholders:
- Total records, records requiring review, and records passing checks
- Review rate (%) and passing checks rate (%)
- Customer records by policy type (donut chart)
- Key data quality issues (bar chart)
- Customer records by policy status

**Detailed Quality Analysis** — for the data team:
- Breakdown of missing and invalid data by category
- Invalid dates and premium values
- Potential duplicate records count
- A corrective actions table with priority levels (High/Medium)

### 4. Recommended Improvements
I linked each identified issue to a practical corrective action — from improving data entry validation to assigning ownership of data quality checks and scheduling regular dashboard reviews.

---

## 📊 Key Findings

| Finding | Result |
|---|---|
| Total customer records | 1,250 |
| Records requiring review | 319 (25.5%) |
| Records passing configured checks | 931 (74.5%) |
| Missing email addresses | 87 |
| Missing phone numbers | 72 |
| Potential duplicate records flagged | 60 |
| Invalid email addresses | 44 |
| Missing cities | 33 |
| Invalid phone numbers | 26 |
| Invalid premium values | 16 |
| Invalid signup dates | 12 |
| Invalid dates of birth | 9 |

> ⚠️ **Note:** Issue categories may overlap — a single record can carry more than one flag. The 319 records requiring review represents unique records with at least one issue. Records flagged as potential duplicates must be investigated before any action is taken.

---

## 📸 Dashboard Screenshots

**Executive Overview**



![Executive Overview](/executive-overview.png)



**Detailed Quality Analysis**



![Detailed Quality Analysis](/detailed-analysis.png)


---

## ✅ Recommendations

1. **Introduce mandatory field validation**: Require essential contact information at the point of customer registration
2. **Validate contact formats at entry**: Add format checks for emails and phone numbers to prevent invalid data entering the system
3. **Investigate potential duplicates**: Review the 60 flagged records against additional identifiers before merging or deleting anything
4. **Standardise categories and locations**: Use controlled values for policy types, statuses, and city fields
5. **Apply date and premium business rules**: Define acceptable ranges and verify exceptions against source information
6. **Establish ongoing monitoring**: Refresh the dashboard regularly and assign clear ownership for resolving flagged records

---

## 🔐 Data Governance Considerations

Good data management involves more than correcting errors. This project also considers:
- Controlling who can access and update customer information
- Maintaining consistent data entry rules
- Preserving source data before making any corrections
- Recommending human review before any automated action is taken

---

## 📁 Project Files

| File | Description |
|---|---|
| `README.md` | Project documentation (this file) |
| Full Technical Report | [https://drive.google.com/file/d/1T0jYidD_bneNyo4URzKgJbEc9Sojskgz/view?usp=drivesdk|
| Power BI Report (view-only) | [Add Google Drive link here] |

---

## ⚠️ Project Note

Safeguard Insurance Limited is a simulated business scenario. The dataset contains synthetic customer records created specifically for this portfolio project. This is not an audit of a real insurance company.

---

## 👩🏽‍💻 About Me

**Oluwatoyin Praise Oloruntoba**
Data Analyst | AI Governance & Compliance | Executive Virtual Assistant

📍 Lagos, Nigeria (Open to remote roles)
🔗 [LinkedIn](https://www.linkedin.com/in/oluwatoyin-oloruntoba-779873388) | [Notion Portfolio](https://notion.so/your-portfolio)

---

*This project is part of a growing portfolio demonstrating practical skills in data preparation, Power BI dashboard development, DAX calculations, and data governance.*
