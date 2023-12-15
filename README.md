Data pipelines are like the heart and soul of efficient data handling, ensuring that information moves smoothly from where it’s stored to where it’s needed. When it comes to tools for managing this process, Apache Airflow shines as one of the most favored and widely used options.

Airflow provides the backbone for orchestrating tasks, but what truly sets it apart is its extensibility and compatibility with a wide range of companion programs.
This project explains how Apache Airflow seamlessly integrates with various tools, including SODA, Astro, Comos, DBT, and many more, to help build efficient and robust data pipelines. 

**ETL Process**

1. Ingest Raw Dataset- Load the CSV data into Google Cloud Storage
2. Quality Check- Data quality control using SODA
3. Run dbt models to transform- Shape the data to obtain fact and dimension tables using dbt with Cosmos as a tools
4. Quality Check- Data quality control using SODA
5. Run dbt models for report- Run all the models to get analytics from the transformed data
6. Quality Check- Final data quality control using SODA
7. Metabase- Create the dashboard, and get insight

**Prerequisites**

Docker,
Astro CLI,
Soda Account,
Google Cloud Account

![image](https://github.com/vidyakailasam/Data_Pipeline_Engineering/assets/43615656/68bbc612-5a6f-4eac-b55d-ad7d7ba8e5b8)
