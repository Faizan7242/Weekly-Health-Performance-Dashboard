# Weekly Health Performance Dashboard

## Overview
This interactive Weekly Health Performance Dashboard was developed to empower district-level health officials in Bihar to effectively monitor and evaluate healthcare facility performance on a weekly basis. It provides a top-down view from district to individual facility level, enabling targeted interventions and better resource management.

<img width="960" alt="Weekly_performance_Home" src="https://github.com/user-attachments/assets/9d27e027-fa7a-4eb1-b752-004c49f9b2bd" />


## Objective
To streamline health monitoring by offering a centralized dashboard where stakeholders can track real-time performance trends across blocks, facilities, and districts — ultimately supporting data-driven decision-making and improved healthcare delivery.

## Data Source
**Bhavya Central Application Database**  
An internal healthcare database that captures real-time OPD activity and timestamps from hospitals across Bihar.

## Tools & Techniques

### Tools
- **SQL (MySQL):** Data extraction, cleaning, and preprocessing
- **Power BI:** Data modeling, visualizations, and interactive dashboard creation

### Techniques
- **Data Cleaning & Transformation:** Using Power Query and Excel to standardize and structure weekly performance datasets
- **DAX Measures & Calculated Columns:** For computing KPIs, trends, and dynamic category flags
- **Drill-down Hierarchies:** Implemented district → block → facility navigation
- **Conditional Formatting:** Visual cues for performance (color-coded status indicators)
- **Interactive Filters & Slicers:** To isolate views by week, indicator, or location
- **Trend Analysis:** Weekly change tracking to support performance review meetings

## Key Features
- Drill-down navigation from district → block → individual facility
- Weekly comparison across key performance indicators (KPIs)
- Visual trend analysis to track improvement or decline
- Color-coded performance categories for quick action prioritization
- Role-based insights tailored for district and facility managers

## Impact
- Enabled proactive performance reviews by health officials
- Promoted accountability and transparency across 38 districts
- Helps identify underperforming blocks/facilities quickly
- Served as a model for standardized weekly reporting in the public health system

---

**Note:**  
This repository contains supporting documentation, SQL scripts, and dashboard snapshots. The dashboard file (.pbix) itself will NOT be uploaded due to internal data policies. Please see the `snapshots/` folder for example visuals.
