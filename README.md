#  Healthcare  Analysis Dashboard | Power BI Project

## Overview

The **Healthcare Emergency Room Analysis Dashboard** is a Power BI project designed to analyze hospital patient data and improve emergency room performance.

It provides insights into **patient admissions, waiting times, department referrals, demographics, and satisfaction levels**. The goal is to convert raw healthcare data into interactive visuals that support **data-driven decision-making in hospital management**.

---

## Dataset

* **Total Records:** 9,216 patients
* **Columns:** 12 original + calculated fields
* **Time-Based Fields:** Year, Month, Day extracted in Power BI

### Key Data Features

* Patient demographics (Age, Gender, Race)
* Admission details (Status, Date, Department Referral)
* Operational metrics (Waiting Time, Satisfaction Score)
* Hospital performance indicators

---

## Tools & Technologies

| Tool               | Purpose                        |
| ------------------ | ------------------------------ |
| Power BI           | Dashboard development          |
| Power Query Editor | Data cleaning & transformation |
| DAX                | KPI calculations               |
| Data Modeling      | Relationship building          |

---

## Project Steps

### 1. Data Collection

* Imported hospital patient dataset into Power BI
* Verified data structure and column types

### 2. Data Cleaning (Power Query)

* Standardized column formats
* Handled missing values
* Created **Full Name** column
* Extracted date components (Year, Month, Day)

### 3. Data Transformation

* Built calculated columns for analysis
* Structured dataset for time-based insights
* Ensured data consistency for reporting

### 4. KPI Development (DAX)

Created key measures such as:

* Total Patients
* Average Waiting Time
* Average Satisfaction Score
* Total Admissions

### 5. Dashboard Development

* Designed interactive visuals in Power BI
* Added slicers for dynamic filtering (Gender, Age, Department, Month)
* Built KPIs and charts for performance monitoring

### 6. Reporting & Presentation

* Created detailed analytical report
* Built presentation using **Gamma AI**
* Summarized insights and recommendations

---

## Dashboard Features

* KPI Cards:

  * Total Patients
  * Average Waiting Time
  * Average Satisfaction Score
  * Total Departments
  * Case Management Cases

* Interactive Slicers:

  * Gender
  * Age
  * Department Referral
  * Month

* Visualizations:

  * Department-wise referral analysis
  * Gender distribution (donut chart)
  * Monthly patient trends
  * Department satisfaction comparison
  * Detailed patient data table

---

## Key Results

* Total patients analyzed: **9,216**
* Average waiting time: **35.3 minutes**
* Average satisfaction score: **4.2 / 5**
* Neurology department recorded the highest waiting time (~55 minutes)
* Orthopedics achieved the highest patient satisfaction (4.6 / 5)
* Patient visits increased by **11.9% (March → April)**

---

## Key Insights

* Higher patient load directly impacts waiting times in specific departments
* Patient satisfaction varies significantly across departments
* Monthly trends help in better staffing and resource planning
* Demographics play a key role in healthcare service optimization
* Operational efficiency can be improved through data-driven scheduling

---

## Business Recommendations

* Increase staffing in high-wait-time departments (e.g., Neurology)
* Improve resource allocation in high-demand departments
* Monitor satisfaction scores regularly for service improvement
* Use monthly trends for better workforce planning
* Apply demographic insights for personalized healthcare services

---

## How to Run
 ### Clone Repository:
git clone <https://github.com/rajendharbanoth8-byte/Healthcare-Analysis.git><br>
### 1. Open Power BI File

* Load the `.pbix` file in Power BI Desktop

### 2. Load Dataset

* Ensure dataset is properly connected

### 3. Refresh Data

* Click **Refresh** to update dashboard visuals

### 4. Explore Dashboard

* Use slicers (Gender, Age, Department, Month)
* Analyze KPIs and visual insights interactively

---

## Report & Presentation

* A detailed **Power BI report** was created with findings and insights
* A **presentation (PPT)** was built using **Gamma AI** for clear storytelling

---

## Dataset and Dashboard
###1. Dataset <a href=""
### 2.Dashboard
### 3. Dashboard Image

## Repository Structure

```plaintext id="hcare001"
Healthcare-Analysis/
│
├── Dataset/
├── PowerBI/
├── Report/
├── Presentation/
├── Images/
└── README.md
```

---

## Author

**Rajendhar Banoth**<br>
Aspiring Data Analyst | Power BI | Healthcare Analytics
