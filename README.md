Project Overview

This project simulates an end-to-end data pipeline for Avalanche, a fictional Winter Sports Gear Company.
The pipeline integrates AWS S3, Snowflake, Snowpark, and Python (Pandas) to analyze order history and shipping logs.

⚙️ Tech Stack

☁️ AWS S3 – Raw data storage

❄️ Snowflake – Cloud Data Warehouse

🐍 Snowpark (Python API) – Scalable transformations

📊 Pandas / Python – Cleaning & validation

📒 Jupyter Notebook – Development & testing

🔄 Workflow

1️⃣ Data Ingestion – CSVs uploaded to AWS S3, connected to Snowflake external stage
2️⃣ Data Cleaning & Transformation – Pandas + Snowpark for joins, delay calculation, fact/dim tables
3️⃣ Data Loading – Transformed data stored in Snowflake tables
4️⃣ Analytics – KPIs like average delivery time, top products, and on-time shipment %

📊 Example Insights

🚚 Average delivery time by carrier

⏱️ On-time vs delayed shipment %

🛒 Top-selling products & categories

🌍 Regional sales distribution

📘 Key Learnings

✔️ Hands-on with Snowpark DataFrames for scalable ETL
✔️ Built a real-world style pipeline integrating AWS + Snowflake + Python
✔️ Applied data modeling best practices (fact & dimension tables)

🚀 Future Enhancements

Orchestrate pipeline with Airflow / Step Functions

Add real-time streaming with Kafka/MSK

Visualize results in Power BI / Tableau
