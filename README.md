
<div align="center">

# ⚡ EV Infrastructure Optimization: Geospatial Demand Clustering & CapEx Allocation
### Unsupervised Machine Learning Pipeline & Executive Decision System

[![Python](https://img.shields.io/badge/Python-3.9+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org)
[![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com)
[![Folium](https://img.shields.io/badge/Folium-Geospatial-77B829?style=for-the-badge&logo=leaflet&logoColor=white)](https://python-visualization.github.io/folium/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](LICENSE)

<p align="center">
  <b>Solving urban range anxiety and infrastructure deficits using unsupervised K-Means clustering.</b><br>
  Computes 50 strategic high-utilization charging centroids from geospatial fuel and traffic demand proxies.
</p>

[Explore The Map](https://github.com/iza684/EV-Charging-Location-Optimization/blob/main/EV-Charging-Station-Optimization/visualizations/ev_network_optimization_map.html) • [Power BI Report](https://github.com/iza684/EV-Charging-Location-Optimization/blob/main/EV-Charging-Station-Optimization/visualizations/ev_station_optimization_dashboard.pbix) • [Jupyter Notebook]([notebooks/](https://github.com/iza684/EV-Charging-Location-Optimization/blob/main/EV-Charging-Station-Optimization/notebooks/ev_location_optimization.ipynb))

</div>

---

## 📌 Executive Summary

Rapid EV adoption creates high capital risk when deploying fast-charging infrastructure without demand intelligence. Inefficient site selection causes severe grid strain, prolonged ROI cycles, and commuter "dead zones." 

This project delivers an end-to-end geospatial analytics pipeline that clusters transit density, highway corridors, and existing fuel retail distributions to locate **50 optimal high-throughput EV charging hubs**. The final model guides CapEx allocation by preventing overlapping station cannibalization and minimizing urban infrastructure gaps.

```text
[ Data Ingestion ] ──> [ Preprocessing & Haversine ] ──> [ K-Means ($k=50$) ] ──> [ BI & Spatial Delivery ]
Petrol Hubs & Traffic       Coordinate Filtering/Scaling         Centroid Convergence       Power BI + Folium GIS

```

---

## 🎯 Key Objectives & Analytical Workflow

1. **Demand Proxy Extraction:** Process multi-source geospatial coordinates (fuel retail points, arterial highways, traffic nodes) to mirror natural vehicle concentration.
2. **Infrastructure Deficit Mapping:** Plot operating EV stations against density hotspots to reveal charging deserts.
3. **Centroid Optimization ($k=50$):** Run K-Means clustering via Scikit-Learn to compute optimal hub locations minimizing distance for target commuter clusters.
4. **Interactive GIS & Executive Dashboard:** Export coordinate centroids into a standalone interactive Folium map and an executive Power BI dashboard tracking capacity, coverage distribution, and CapEx priority tiers.

---

## 📊 Dashboard & Geospatial Visualizations

### Executive Power BI Decision Interface

Interactive monitoring dashboard analyzing geographic density, station distribution tiers, and operational planning metrics:

### Spatial Map Legend (`visualizations/ev_hubs_map.html`)

* 🟢 **Green Bolt Pins:** 50 AI-computed optimal charging station centroids.
* 🔵 **Blue Coordinates:** Active operational charging infrastructure.
* 🔴 **Coverage Radius Overlay:** 5 km service buffer delineating underserved arterial routes.

---

## 💡 Key Business Impact & Strategic Insights

* **CapEx Overlap Elimination:** Prevents redundant site construction within competitive radii, focusing financial resources on validated transit choke points.
* **Data-Backed Site Acquisition:** Replaces speculative property leasing with mathematical coordinate targets backed by fuel consumption proxies.
* **Prioritized Phased Rollout:** Categorizes 50 proposed stations into Phase 1 (Dense Urban Infill) and Phase 2 (Highway Corridors) based on cluster density scores.

---

## 🛠️ Technology Stack

| Category | Tools / Libraries | Application |
| --- | --- | --- |
| **Core Environment** | Python 3.9+, Jupyter Notebook | Execution pipeline, exploratory analysis, and scripts |
| **Data Manipulation** | Pandas, NumPy | Geospatial coordinate cleaning, normalization, transformation |
| **Machine Learning** | Scikit-Learn | K-Means clustering, centroid vector extraction, metric tuning |
| **Spatial Visualization** | Folium, Leaflet.js | Interactive vector mapping, clustering layers, boundary polygons |
| **Business Intelligence** | Microsoft Power BI, DAX | Executive KPI reporting, regional slices, operational metrics |

---

## 📁 Repository Architecture

```bash
├── data/
│   ├── raw/                   # Raw coordinate and traffic data feeds
│   └── processed/             # Cleaned coordinates & 50 proposed hub locations (.csv)
├── notebooks/
│   └── ev_location_optimization.ipynb  # End-to-end data processing, EDA & ML pipeline
├── visualizations/
│   ├── ev_hubs_map.html       # Standalone interactive Leaflet/Folium spatial map
│   └── dashboard_preview.png  # High-resolution dashboard telemetry capture
├── requirements.txt           # Environment dependencies and pinned versions
├── LICENSE                    # Standard open-source MIT License
└── README.md                  # Project documentation & business blueprint

```

---

## ⚙️ Quickstart & Execution

```bash
# 1. Clone repository
git clone [https://github.com/iza684/EV-Charging-Station-Optimization.git](https://github.com/iza684/EV-Charging-Station-Optimization.git)
cd EV-Charging-Station-Optimization

# 2. Create virtual environment
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Launch Jupyter Notebook
jupyter notebook notebooks/ev_location_optimization.ipynb

```

---

## 👤 Author & Connect

**Izaan Ansari**

*Data Analyst | Business Intelligence & Machine Learning*

```

```
