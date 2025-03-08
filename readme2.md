# 📌 Short Notes on dbt (Data Build Tool)

## 1️⃣ What is dbt?
- **dbt (Data Build Tool)** is an open-source analytics engineering tool used for **transforming data** inside a data warehouse.
- It enables **SQL-based transformations**, **modularity**, and **version control** for analytics workflows.

---

## 2️⃣ Key Features of dbt
- **SQL-Driven Transformations**: Write SQL queries to clean, join, and transform data.
- **Modular Development**: Break down transformations into **reusable models**.
- **Data Testing**: In-built testing for **data quality** (e.g., uniqueness, null checks).
- **Version Control with Git**: Track changes in data models using **Git**.
- **Incremental Processing**: Supports **incremental data loads** to optimize performance.
- **Documentation & Lineage**: Auto-generates documentation and **visualizes data dependencies**.

---

## 3️⃣ dbt Workflow
1. **Extract & Load (ELT)**: Data is loaded into the warehouse (e.g., Snowflake, BigQuery).
2. **Define Models**: Create **SQL-based dbt models** (`.sql` files) for data transformations.
3. **Run Transformations**: Use `dbt run` to apply transformations.
4. **Test Data Quality**: Use `dbt test` to validate transformations.
5. **Deploy & Document**: Use `dbt docs generate` to create **lineage diagrams**.
