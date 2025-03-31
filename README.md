# Data Flow: Centralized Dashboard with Power BI

This data flow was designed and built to connect multiple data sources into a centralized **Power BI** dashboard. The goal was to create a streamlined and automated reporting system that enables the team to **monitor business performance in near real-time**.

---

## Key Objectives

- Integrate data from various platforms (e.g., **Grab**, **Foodpanda**, **Lineman**, internal tools).
- Clean, transform, and model data for consistency and accuracy.
- Automate refresh cycles to reduce manual work and manual error.
- Visualize KPIs across **brands**, **stores**, and **platforms** in a single dashboard.

---

## Flow Overview

The data pipeline includes the following stages:

### Data Sources
- Raw data pulled from:
  - Food delivery platforms
  - Google Sheets
  - Internal databases

### Data Cleaning & Transformation
- Standardizing metrics and formats
- Unifying store identifiers across platforms
- Handling missing or inconsistent values

### Data Modeling
- Creating relationships between key datasets:
  - Sales Data
  - Store Master Info
  - Commission & Fee Structures

### Power BI Integration
- Loading the cleaned and modeled data into **Power BI**
- Building interactive reports and dashboards for stakeholders

---

## Diagram Preview


---

## Notes
- Built entirely by me (Jay) to improve visibility and reduce manual reporting tasks for the business intelligence team.
- Designed to scale as new brands and data sources are onboarded.
