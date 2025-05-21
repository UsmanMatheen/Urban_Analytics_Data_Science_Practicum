# Urban Analytics: Identifying Optimal Vacant Parcels for Equitable Transit-Oriented Development (ETOD)

## 📍 Project Overview

This project, part of the Data Science Practicum at Illinois Tech in collaboration with the Center for Neighborhood Technology (CNT), aims to identify vacant land parcels across Cook County that are most suitable for Equitable Transit-Oriented Development (ETOD). The analysis integrates multiple spatial, demographic, and mobility datasets to prioritize locations that align with community equity, accessibility, and sustainability goals.

## 🎯 Objectives

- Identify and rank vacant parcels for potential ETOD development.
- Integrate and analyze multiple datasets including vehicle miles traveled (VMT), connected community zones, property valuation, and more.
- Create a scalable geospatial analytics workflow to support policy and planning decisions.

## 🗂️ Datasets Used

- Cook County Vacant Parcels Shapefile
- ChiBlockBuilder (City-Owned Property)
- Cook County Assessed Property Value Data
- VMT Odometer Data (Illinois EPA)
- Connected Communities Program Zones (City of Chicago)
- City of Chicago Zoning Shapefile
- Road Network Shapefiles
- Land Cover and LIDAR Data (optional for future expansion)

## ⚙️ Methodology

1. **Data Cleaning & Integration**  
   Standardized and merged spatial and tabular datasets using Python and QGIS.

2. **Feature Engineering**  
   Derived spatial proximity metrics such as distance to transit, zoning compliance, and VMT scores.

3. **Scoring Model**  
   Developed a composite scoring model to rank parcels based on:
   - Equity indicators (Connected Communities inclusion)
   - Transportation efficiency (low VMT)
   - Development feasibility (zoning match, ownership)

4. **Visualization**  
   Generated thematic maps to highlight top-priority parcels for decision-makers.

## 📌 Key Tools & Technologies

- **Python**: Pandas, GeoPandas, NumPy, Scikit-learn, Matplotlib
- **QGIS**: Spatial data processing and visualization
- **Shapely, Fiona, Pyproj**: Geospatial data handling
- **Git/GitHub**: Version control and collaboration

## ✅ Results

- Identified 300+ high-potential parcels across Cook County suitable for ETOD.
- Developed reproducible code and a scoring pipeline for prioritization.
- Delivered final visuals and analytics insights to CNT stakeholders.
