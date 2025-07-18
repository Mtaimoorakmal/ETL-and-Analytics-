# ETL-and-Analytics-


This project implements a modern ETL pipeline from Odoo, API, and DB sources using an orchestrated, multi-layered approach.

### 🔁 ETL Flow:

![ETL Architecture](/images/architechure.drawio.png)

- **Data Source**: Odoo, API, and SQL DB
- **Landing Zone**: Raw data ingestion
- **Staging**: Cleaned, transformed intermediate layer
- **Production**: Final structured tables for reporting
- **Visualization**: Power BI dashboards
- **Orchestration**: Managed via Apache Airflow
