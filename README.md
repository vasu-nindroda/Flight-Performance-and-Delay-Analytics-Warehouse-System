# Flight-Performance-and-Delay-Analytics-Warehouse-System



# ✈️ Flight Performance and Delay Analytics Warehouse System

## 📌 Overview

Flight delays are one of the most costly and disruptive challenges in aviation, impacting both airlines and passengers. This project - **Flight Performance and Delay Analytics Warehouse System** - centralizes multi-year U.S. domestic flight data into a **MySQL-based data warehouse** and enables **interactive analytics** using **Power BI dashboards**.

The system integrates data from **2015, 2022, and 2023** (3M+ flight records) through a **Python ETL pipeline**, cleans and normalizes it into a **star schema**, and supports **OLAP queries** for multidimensional insights. Unlike short-term forecasting models, our solution emphasizes **longitudinal analysis**, uncovering **route-specific delay patterns** and operational bottlenecks.

## 🚀 Key Features

* **ETL Pipeline (Python + Pandas):** Automated data extraction, cleaning, transformation, and loading into MySQL.
* **Star Schema Data Warehouse:** Fact and dimension tables supporting fast, scalable OLAP queries.
* **Route-to-Route Delay Analysis:** Identifies persistent delay hotspots across U.S. airports (e.g., ORD, ATL, JFK).
* **Interactive Dashboards (Power BI):** Visual exploration of delays by airline, route, year, and season.
* **Scalable & Extensible:** Designed to integrate future datasets and predictive models.



## 🛠️ Tech Stack

* **Database:** MySQL (Star Schema)
* **Data Processing:** Python (Pandas, SQLAlchemy)
* **Visualization:** Power BI
* **Data Volume:** \~3 million+ flight records

---

## 📊 Results & Insights

* Discovered **consistent route-specific delay hotspots** independent of seasonality.
* Post-COVID surge in 2022 delays attributed to **staff shortages and passenger rebound**.
* Achieved **sub-second query responses** with optimized schema design.
* Dashboards enabled **dynamic filtering**, ranking worst routes, and visualizing geographic congestion.

---

## ⚠️ Limitations

* Static dataset (no real-time feeds).
* Excludes weather and airline-specific performance metrics.
* Limited reliability for low-traffic routes due to sparse data.

---

## 🔮 Future Enhancements

* Integration of **real-time APIs** (FAA, airline data).
* Inclusion of **weather, staffing, and operational factors**.
* **Explainable ML models** for predictive delay analytics.
* Mobile-friendly dashboards with **what-if simulations**.

---

## 👥 Contributors

Group - *Sky-Metrics*

* Dhruv Hiren Paghdal
* **Vasu Satishbhai Nindroda**
* Swar Sanjaykumar Parikh
* Sakshi Jigneshbhai Patel
* Dharmik Patel
* Dhruv Sejalbhai Patel

