# ETL-and-Analytics-


## 🔁 ETL Pipeline Architecture

This project implements a modern ETL pipeline that extracts data from Odoo, APIs, and databases, orchestrated using Apache Airflow.

### 📊 Architecture Overview

![ETL Architecture](/images/architechure.drawio.png)

- **Landing Zone**: Raw data is ingested and stored in **AWS RDS**.
- **Staging**: Data is cleaned and transformed in intermediate **RDS tables**.
- **Production**: Final structured tables ready for reporting and analysis in **RDS**.
- **Visualization**: Power BI connects to the RDS production layer via **ODBC** to build dashboards.
- **Orchestration**: Entire pipeline is managed using **Apache Airflow DAGs** for scheduling and monitoring.
