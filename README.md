# Bright Coffee Shop Sales Analysis 

An end-to-end data analytics and business intelligence project designed to extract actionable insights from historical sales data. This multi-tool analysis and accompanying executive assets are tailored to assist the CEO in making strategic, data-driven decisions to accelerate revenue growth, optimize store operations, and improve menu performance.

## Repository Structure

* `Bright Coffee Shop Dataset.xlsx` – The central workbook containing clean transactional records, pivot structures, and core metrics.
* `Data Inspection - Bright Coffee Shop.png` – Visual profile detailing initial data schemas, field constraints, and health checks.
* `Project Timeline - Bright Coffee Shop.png` – The chronological roadmap mapping our process out from raw data ingestion to executive delivery.
* `README.md` – This comprehensive project documentation file.

## The Tech Stack & Analytics Workflow

To mirror a robust production data pipeline, this project seamlessly connects four primary tools to take the business from raw data to dynamic executive insights:

### 1. Python (Data Wrangling & Profiling)
* **Purpose:** Initial ingestion, algorithmic data cleaning, and programmatic schema checking.
* **Execution:** Used `pandas` and `numpy` to isolate missing variables, format explicit transaction datetimes, drop duplicates, and perform programmatic data quality inspections (as outlined in the `Data Inspection` profile).

### 2. SQL (Structured Querying & Metric Extraction)
* **Purpose:** Advanced exploratory data analysis (EDA) and business logic segmentation.
* **Execution:** Engineered targeted relational queries to extract high-yield trends such as hourly rush hours, day-of-week sales volume distributions, and customer attachment matrices.

### 3. Microsoft Excel (Ad-Hoc Analysis & Baseline Modeling)
* **Purpose:** Quick data pivoting, tabular summaries, and preliminary calculations.
* **Execution:** Designed flat-table structures to calculate core performance parameters like **Average Transaction Value (ATV)**, unit velocity, and gross revenue splits per store location.

### 4. Power BI (Dynamic Visual Storytelling)
* **Purpose:** Building an interactive Business Intelligence environment for executive tracking.
* **Execution:** Structured an optimized dataset with functional **DAX measures** to construct interactive KPI cards, heat maps mapping hourly sales velocity, and dynamic menu-engineering matrix charts.

## Key Strategic Pillars Analyzed

The final dashboard and summary outputs dive deeply into three operational pillars:

1. **Revenue & Ticket Profiling:** Tracking gross revenue spikes, order frequency, and calculating customer spending baselines across operational quarters.
2. **Menu Engineering & Product Performance:** Isolating high-margin "Stars" from low-margin/low-volume items ("Dogs") to allow for strategic menu pruning and cross-promotional bundling.
3. **Temporal Foot-Traffic Velocity:** Grouping sales rows into precise hourly windows to uncover the exact bounds of the morning commuter rush versus afternoon operational lulls.

## Strategic Recommendations for the CEO

* **Implement Dynamic Bundling:** Leverage item attachment rates to pair low-volume, high-margin pastries with high-velocity morning beverage runs to instantly lift the store’s Average Ticket Size.
* **Optimize Labor Allocations:** Realign staff scheduling blocks to tightly map against the peak morning commuter hours identified in the hourly heat maps, reducing unneeded overhead during afternoon lulls.
* **Streamline Menu Dead-Weight:** Drop underperforming, low-margin products ("Dogs") to optimize storage costs, minimize waste, and speed up employee drink-assembly times.
