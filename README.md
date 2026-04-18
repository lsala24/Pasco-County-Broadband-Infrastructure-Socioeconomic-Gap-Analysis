# Pasco County Broadband Infrastructure Gap Analysis

## Project Overview
This ArcGIS Dashboard provides a comprehensive geospatial analysis of the "Digital Divide" in Pasco County, FL. By synthesizing FCC National Broadband Map data with U.S. Census tracts, the project identifies localized service gaps to assist stakeholders in prioritizing infrastructure investment and grant funding.

**Live Project Link:** [View the Interactive Dashboard](https://leospatial.maps.arcgis.com/apps/dashboards/70111911e3cc467d8ceec69fb26f2606)

<img width="1897" height="861" alt="Screenshot 2026-04-18 134855" src="https://github.com/user-attachments/assets/45fb830e-8ed1-430e-b296-6e2701b04ef8" />


## Technical Highlights
* **Arcade Integration:** Developed dynamic expressions to synchronize map symbology with label classes, ensuring data integrity across all zoom levels.
* **Real-Time Analytics:** Configured dashboard indicators to calculate "Fiber Availability" and "Service Gaps" based on the current map extent.
* **Spatial Modeling:** Aggregated building-level service status to census tract geometries to visualize regional socio-economic trends.

## Data Methodology
* **Sources:** FCC National Broadband Map (2024), U.S. Census Bureau (2020).
* **Metrics:** - **Service Gap:** Combined percentage of "Unserved" (<25/3 Mbps) and "Underserved" (<100/20 Mbps) locations.
  - **Fiber Coverage:** Percentage of locations with active Fiber-to-the-Premises (FTTP) connectivity.
* **Tooling:** ArcGIS Online, Arcade Scripting, QGIS (Data Pre-processing).

## How to Use
1. **Navigate:** Use the map to pan and zoom; the bottom indicators will update automatically for the visible area.
2. **Inspect:** Click on individual census tracts to view specific building counts and calculated gap percentages in the pop-up.
3. **Compare:** Utilize the side-by-side map views to compare infrastructure types against socio-economic boundaries.

## Terms of Use
Developed as a professional GIS portfolio project. While data is sourced from public federal records, users should consult official agency portals for regulatory or legal compliance.

---
**Author:** Leonard Lee Sala Jr.  
**Role:** GIS Professional  
**Tools:** ArcGIS Dashboards | Arcade | QGIS
