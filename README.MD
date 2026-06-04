## 🛒 Sales Performance & Operations Analysis (Power BI)

**Objective:** Engineered an end-to-end operational Business Intelligence solution analyzing an e-commerce ecosystem across 9 relational datasets (Olist Brazil), driving data-backed optimization for sales cycles, supply chain logistics, and customer retention.

### 🖼️ Dashboard Preview
![Dashboard Overview](Sales_Performance_Analysis/screenshots/Sales_Performance_Analysis_2.jpg)

### 🧩 Technical Features & Engineering Architecture
* **Advanced ETL & Data Ingestion (Power Query):** Processed and cleaned 9 complex relational CSV datasets. Standardized data types, handled missing categorical variables, and built structural pipelines to track progressive order states (`orders_created` to `orders_delivered`).
* **Enterprise Star Schema Modeling:** Architected a robust relational model, enforcing one-to-many integrity constraints between dimensional tables (Customers, Products, Vendors) and transactional fact tables, synchronized via a master `Calendar` table.
* **Advanced DAX Engineering & Metrics Segmentation:** Developed an optimized, folder-structured measure architecture to isolate and compute cross-functional enterprise KPIs:
  * **Commercial Analytics:** Programmed time-intelligence DAX for Prior Year (PY) benchmarks, Year-over-Year (YoY %) revenue expansion, conversion rates, and transaction volume velocities.
  * **Supply Chain & Logistics Telemetry:** Automated tracking for shipping bottlenecks, average processing durations (`average_processing_days`), and precise on-time delivery ratios.
  * **Financial & Cash Flow Infrastructure:** Modeled transaction splitting and risk matrices across installment frequencies and one-time payment types.
  * **Customer Sentiment (NPS Cohorts):** Engineered native dimensional DAX formulas to calculate Net Promoter Score (NPS), isolating Promoter/Detractor boundaries and mapping behavioral patterns against metadata like product description length.
* **Executive UX & Dynamic Navigation:** Implemented clean container-based conditional formatting and built a customized tab-switching system (`switch_tab`) to deliver an interface optimized for executive-level business decisions.

### 📂 File Structure
* `Sales_Performance_Analysis.pbix`: High-performance data model and full interactive reporting suite[cite: 3].

### 📊 Project Execution & Metrics
* **Development Workflow:** Requirements Gathering ➔ Power Query ETL & Normalization ➔ Relational Star Schema Design ➔ Advanced DAX Measure Groups ➔ UX/UI Testing.

👉 **[Click here to browse project files](Sales Performance Analysis/screenshots/)**
