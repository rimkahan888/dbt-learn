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

---

## 4️⃣ Core Components of dbt
| **Component** | **Description** |
|--------------|---------------|
| **Models (`.sql` files)** | SQL queries defining data transformations |
| **Seeds** | Load small datasets (CSV) into the warehouse |
| **Snapshots** | Track historical changes in data |
| **Macros** | Reusable SQL code blocks (like functions) |
| **Tests** | Validates data integrity (e.g., uniqueness, nulls) |
| **Documentation** | Auto-generates docs & lineage |
   
---

## 5️⃣ Supported Data Warehouses
- **Snowflake**
- **BigQuery**
- **Amazon Redshift**
- **PostgreSQL**
- **Databricks SQL**

---

## 6️⃣ Basic dbt Commands
dbt init my_project    # Create a new dbt project
cd my_project          # Navigate to the project folder
dbt run                # Run transformations
dbt test               # Run data tests
dbt compile            # Compile SQL queries
dbt docs generate      # Generate documentation
dbt debug              # Debug connection issues
   
   
