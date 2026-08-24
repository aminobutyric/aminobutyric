<div align="center">
  <img src="./assets/profile-header.svg" alt="Amin Pasandideh — Data Engineer" width="100%" />

  <br />

  [![LinkedIn](https://img.shields.io/badge/LinkedIn-aminobutyric-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aminobutyric/)
  [![Email](https://img.shields.io/badge/Email-Let's%20talk-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:aminpasandideh2000@gmail.com)
  [![Location](https://img.shields.io/badge/Tehran%2C%20Iran-open%20to%20relocation-334155?style=flat-square&logo=googlemaps&logoColor=white)](https://www.google.com/maps/place/Tehran/)
</div>

## About me

I am a **Data Engineer** with 1.5+ years of hands-on experience designing, building, and operating production data platforms. My work spans lakehouse architecture, distributed processing, workflow orchestration, data quality, and the infrastructure that keeps it all reliable.

I enjoy turning complex, high-volume data into dependable datasets for machine learning and analytics. My computer science and machine learning background helps me bridge the gap between platform engineering and downstream data consumers.

## Impact at a glance

| | |
|---|---|
| **1B+ records processed** | Built distributed PySpark workflows for recommendation-system training data |
| **Lakehouse, end to end** | Took an on-premises MinIO-based Medallion architecture from proof of concept to production |
| **Production orchestration** | Operated incremental ETL/ELT pipelines with Airflow scheduling, retries, monitoring, and failure handling |
| **Reliable by design** | Established schema, integrity, drift, outlier, lifecycle, backup, and disaster-recovery controls |

## Technical toolkit

**Data engineering**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta%20Lake-00ADD8?style=flat-square&logo=databricks&logoColor=white)
![Apache Kafka (basic)](https://img.shields.io/badge/Kafka-basic-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Trino](https://img.shields.io/badge/Trino-DD00A1?style=flat-square&logo=trino&logoColor=white)

**Databases & storage**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?style=flat-square&logo=clickhouse&logoColor=111827)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![MinIO](https://img.shields.io/badge/MinIO-C72E49?style=flat-square&logo=minio&logoColor=white)
![Parquet](https://img.shields.io/badge/Apache%20Parquet-50ABF1?style=flat-square&logo=apacheparquet&logoColor=white)

**Platform & operations**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=111827)
![GitLab CI/CD](https://img.shields.io/badge/GitLab%20CI%2FCD-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Metabase](https://img.shields.io/badge/Metabase-509EE3?style=flat-square&logo=metabase&logoColor=white)

## What I work on

```mermaid
flowchart LR
    sources["MongoDB · APIs"] --> storage["MinIO<br/>Bronze layer"]
    storage --> processing["Spark · Delta Lake"]
    processing --> serving["ClickHouse · ML"]

    airflow["Airflow orchestration"] -.-> storage
    airflow -.-> processing
    quality["Quality controls"] -.-> processing
    quality -.-> serving
```

- **Lakehouse architecture:** Bronze/Silver/Gold layers, ACID transactions, schema enforcement, versioning, time travel, and curated downstream datasets.
- **Large-scale processing:** distributed joins, aggregations, temporal feature extraction, and business-rule transformations with Spark/PySpark.
- **Data reliability:** validation for missing values, duplicates, outliers, schema drift, and referential integrity, plus Delta Lake `OPTIMIZE` and `VACUUM` lifecycle management.
- **Platform operations:** Dockerized deployments, Linux administration, Nginx, monitoring automation, S3-compatible storage, and `rclone`-based recovery workflows.

## Education

- **M.Sc. in Computer Science — Data Mining**, Shahid Beheshti University · 2025–Present
- **B.Sc. in Computer Science**, Ferdowsi University of Mashhad · 2019–2025

## Beyond the pipeline

My earlier work in machine learning includes feature engineering, supervised and unsupervised modeling, and end-to-end project delivery with scikit-learn, PyTorch, and TensorFlow. That experience shapes how I design datasets and platforms for real ML workloads—not just storage.

<div align="center">
  <sub>Interested in data platforms, distributed systems, and ML infrastructure? <a href="mailto:aminpasandideh2000@gmail.com">Let's connect.</a></sub>
</div>
