# 🗳️ Election Insights Dashboard

### 📊 Real-Time Election Visualization for News Media

**Developed as part of Infosys Springboard Internship**

---

## 🧭 Overview

In today’s fast-paced election environment, news organizations need **accurate and real-time insights** to report results efficiently.
This project transforms **raw election data** into **interactive Power BI dashboards** that help journalists, analysts, and the public explore **vote shares, turnout trends, and constituency-level dynamics** with clarity.

Built using **Power BI**, this solution integrates both **historical and live election data** (via API) to deliver **data-driven storytelling** for news coverage.

---

## 🎯 Objective

To create a **scalable and interactive dashboard** that visualizes Indian election data—enabling users to:

* Analyze **voter turnout**, **party performance**, and **candidate insights**
* Compare **urban vs rural voting behavior**
* Explore **historical trends** across states and constituencies
* Access **real-time updates** through API integration

---

## 🧩 Data & Modeling

### 🔹 Data Sources

* **Historical data:** CSV files (Lok Sabha 1962–2019)
* **Live data:** [Datameet India Election Data API](https://raw.githubusercontent.com/datameet/india-election-data/refs/heads/master/assembly-elections/assembly.csv)

### 🔹 Data Cleaning (Power Query)

* Removed duplicates and nulls
* Standardized text and party names
* Set appropriate data types
* Created calculated columns:

  * `Vote Share (%)`
  * `Result` (Winner/Loser)

### 🔹 Star Schema Design

* **Fact Table:** `fact_votes`
  Contains measurable data like votes, turnout, and margins.
* **Dimension Tables:**

  * `dim_party`
  * `dim_candidate`
  * `dim_constituency`
  * `dim_election_date`

This model enables flexible filtering, aggregation, and trend analysis.

---

## 📈 Dashboards & Key Insights

### 🕰️ Historical Trends

* Visualizes shifts in voter behavior and party dominance across decades.
* Reveals **rising and declining parties** and **regional voting patterns**.

### 👥 Demographic Analysis

* Gender-wise candidate participation (high male dominance).
* Identifies **major political strongholds** and **constituency-level dynamics**.

### 🌾 Rural Voter Dynamics

* Highlights **rural regions’ influence** on national outcomes.
* Shows turnout patterns in high-engagement states like **Nagaland** and **Lakshadweep**.

### 🌆 Urban Voter Landscape

* Examines **urban turnout rates**, which often lag behind rural participation.
* Emphasizes need to boost **urban voter engagement**.

### 🔍 Interactive Features

* **Drill-through pages** allow users to deep-dive into state or constituency data.
* **Dynamic filters and visuals** make exploration intuitive and engaging.

---

## 💡 Tools & Technologies

* **Power BI** (Dashboarding & DAX Calculations)
* **Power Query** (Data Cleaning & Transformation)
* **API Integration** (Live Data Fetching)
* **Star Schema Design** (Data Modeling)

---

## 🏁 Conclusion

This project demonstrates how **data analytics and visualization** can transform complex election data into **actionable insights**.
It empowers journalists, policymakers, and the public to:

* Understand election patterns
* Detect demographic trends
* Enhance transparency in reporting

Ultimately, it bridges **data and democracy** through **interactive storytelling**.

---

## 👥 Contributors

**Team 4 – Infosys Springboard Internship**

* Bhumi Kala
* Santosh SK
* **Srinibas Masanta**
* Vaibhav Yadav

---

## 📂 Files Included

* `Election_Final_Dashboard.pbix` – Power BI dashboard file
* `Election Insights Presentation.pdf` – Project presentation slides
