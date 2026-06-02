# Terrorism-Analysis-Dashboard
🧠 Terrorism Insights & Analysis Dashboard (Power BI)
📌 Project Overview
This project analyzes historical terrorism data using Microsoft Power BI to uncover trends, identify impacted regions, and understand terrorism patterns.
It consists of two dashboards:

🌍 Global Terrorism Dashboard
🇮🇳 Terrorism in India Dashboard
The goal is to convert raw terrorism data into interactive, visual, and insightful analytics for better understanding.

🎯 Objectives
Analyze global terrorism trends over time
Identify most affected countries and regions
Understand attack types and weapon usage patterns
Evaluate killed, wounded, and casualty distribution
Provide a detailed analysis focused on India
Demonstrate real-world analytics using Power BI
🗂️ Dataset Description
The dataset contains multiple years of terrorism incident records.

Key Fields
📅 Date, Year, Month
🌍 Country, Region, State, City
💣 Attack Type, Weapon Type, Target Type
🧠 Terrorist Group
⚠️ Killed, Wounded, Casualties (Derived)
📍 Latitude & Longitude
Each entry = one terrorism incident.

🧹 Data Preprocessing
Performed in Power Query:

Removed unnecessary / duplicate fields
Handled missing values
Standardized categories
Converted data types
Removed invalid geo-coordinates
Created calculated fields:
Casualties = Killed + Wounded
Extracted Year, Month, Quarter
🏗️ Data Modeling
Star Schema implemented for performance.

📌 Fact Table
Fact_Incidents
📌 Dimension Tables
Dim_Date
Dim_Country
Dim_AttackType
Dim_TargetType
Dim_WeaponType
Dim_Group
Relationships configured as One-to-Many.

📊 Dashboard Features
🌍 Global Terrorism Dashboard
Global Terrorism Dashboard

✔ KPI Cards
✔ Global Heat Map
✔ Year-wise Trend Line
✔ Attack Type Distribution
✔ Most Affected Countries
✔ Interactive Slicers

🇮🇳 Terrorism in India Dashboard
India Terrorism Dashboard

✔ India-Specific KPIs
✔ India Heat Map
✔ Year-wise Trend
✔ State / City Analysis
✔ Attack Type Distribution
✔ Year & State Slicers

🧬 Key Insights
Terrorism is concentrated in specific regions
South Asia & Middle East impacted significantly
Armed assault & bombings most common
Few countries account for majority cases
In India, incidents are regionally concentrated
Casualties vary widely by attack type
🛠️ Tech Stack
Power BI
Power Query
DAX
Data Modeling (Star Schema)
🚀 Future Scope
Real-time data integration
Machine learning-based predictions
Advanced geospatial heat clustering
Cross-country comparison analytics
Enhanced drilldown & storytelling features
✅ Conclusion
This project demonstrates how terrorism data can be effectively analyzed and visualized using Power BI. The dashboards help in understanding historical trends, regional impacts, and severity insights, supporting better awareness and analytical research.

🙏 Acknowledgement
Dataset sourced from public terrorism databases and refined for academic use.

⭐ If you found this project useful, don't forget to star the repository!
