# ⚡ EV Charging Station Location Optimization

An end-to-end Data Analytics project using **Python, K-Means Clustering, and Power BI** to identify **50 optimal locations** for new EV fast-charging stations based on demand and traffic data.

---

## 🎯 Key Objectives
- Analyze existing EV charging infrastructure and identify coverage gaps.
- Use high-traffic petrol pump coordinates as a demand proxy.
- Apply **K-Means Clustering ($k=50$)** to compute optimal centroid coordinates for 50 new hubs.
- Build an interactive **Folium Map** and an executive **Power BI Dashboard** for decision support.

---

## 🛠️ Tech Stack
- **Languages/Libraries:** Python (Pandas, NumPy, Scikit-Learn, Folium)
- **Visualization & BI:** Microsoft Power BI
- **Environment:** Jupyter Notebook

---

## 📁 Project Structure
```text
├── data/                  # Cleaned datasets & 50 proposed station coordinates
├── notebooks/             # Data cleaning, EDA & K-Means clustering code
├── visualizations/        # Interactive HTML map & Dashboard screenshots
├── requirements.txt       # Python dependencies
└── README.md              # Project documentation
🗺️ Key Deliverables & Visuals
Interactive Folium Map (.html):

🟢 Green Bolt Pins: 50 AI-Proposed Optimal Hubs

🔵 Blue Dots: Existing Operational EV Stations

Power BI Dashboard:

Tracks operational metrics, hub priorities, and geographic coverage.

![Power BI Dashboard](visualizations/dashboard_overview.png)

🚀 How to Run
Bash
# 1. Clone the repository
git clone https://github.com/iza684/EV-Charging-Station-Optimization.git

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run Notebook
jupyter notebook notebooks/ev_location_optimization.ipynb
💡 Business Impact
Eliminates Dead Zones: Places chargers in high-traffic, underserved corridors.

Optimizes CapEx: Prevents overlapping stations and guides investment to high-demand clusters.

Author:Izaan Ansari | https://www.linkedin.com/in/izaan-ansari/