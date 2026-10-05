# 🚚 Logistics Risk Analysis & Delivery Performance Dashboard

## 📊 Power BI Data Analytics Project

An interactive Power BI dashboard designed to analyze last-mile delivery performance, identify delivery risks, and understand the major factors contributing to delays.

The project focuses on transforming raw delivery logistics data into actionable business insights using Power BI, DAX, and data cleaning techniques.

---

## 🎯 Project Objective

The main objective of this project is to analyze delivery operations and answer key business questions such as:

- How many deliveries are completed, delayed, and failed?
- What is the overall delivery delay rate?
- Which weather conditions contribute to more delays?
- Which regions have higher delay rates?
- Which delivery partners have higher delay rates?
- How much does actual delivery time exceed the expected delivery time?
- Which deliveries are considered high-risk?
- What factors are associated with delivery delays?

---

## 🛠️ Tools & Technologies

- Power BI
- Power Query
- DAX
- Microsoft Excel
- Data Cleaning & Transformation
- Data Visualization
- Exploratory Data Analysis

---

## 📁 Dataset

The project uses a delivery logistics dataset containing approximately **25,000 delivery records**.

The dataset includes information related to:

- Delivery Partner
- Delivery Mode
- Vehicle Type
- Distance
- Package Weight
- Delivery Time
- Expected Delivery Time
- Delivery Status
- Weather Condition
- Region
- Package Type
- Delivery Cost
- Delivery Rating
- Delay Information

---

# 📄 Dashboard Pages

## Page 1 – Delivery Performance Overview

The first page provides an overall view of delivery operations.

### Key KPIs

- Total Deliveries
- Delivered Deliveries
- Delayed Deliveries
- Delivery Failed
- Delay Rate %
- Average Delivery Time
- Average Delivery Gap

### Visualizations

- Delayed Deliveries by Weather Condition
- Average Delivery Time vs Expected Time by Delivery Partner
- Delay Rate by Region
- Delay Rate by Delivery Partner

### Key Purpose

This page helps users quickly understand the overall delivery performance and identify areas where delays are more frequent.

---

# 📄 Page 2 – Logistics Risk Analysis

The second page focuses on identifying and analyzing delivery risks.

### Key Analysis

- High-Risk Deliveries
- Medium-Risk Deliveries
- Delivery Gap Analysis
- Weather-based Risk
- Regional Risk
- Delivery Partner Risk
- SLA Breach Analysis

### Risk Classification

Deliveries are categorized based on the difference between actual delivery time and expected delivery time.

```text
Delivery Gap = Actual Delivery Time - Expected Delivery Time
