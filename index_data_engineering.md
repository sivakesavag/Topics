## Comprehensive List of Data Engineering Topics

**I. Foundations**

1.  **Data Lifecycle & Principles:** ingestion, storage, processing, analytics, governance.
2.  **File Formats:** CSV, JSON, Avro, Parquet, ORC, Delta Lake, Iceberg.
3.  **Batch vs Stream Processing Paradigms (Lambda, Kappa, Lakehouse).**

**II. Data Ingestion & Integration**

4.  **ETL/ELT Patterns:** change data capture (CDC), SCD types, upserts.
5.  **Ingestion Tools:** Kafka Connect, Debezium, Sqoop, Flume, NiFi.
6.  **APIs & Webhooks, FTP/SFTP, message queues (Kafka, Pulsar, RabbitMQ).**

**III. Storage & Management**

7.  **Databases:** RDBMS, NoSQL (key-value, document, columnar), NewSQL.
8.  **Data Lakes & Lakehouses:** HDFS, S3, ADLS, GCS.
9.  **Data Warehouses:** Redshift, BigQuery, Snowflake, Synapse.
10. **Partitioning, Clustering, Compression, Indexing Strategies.**

**IV. Processing Frameworks**

11. **Apache Spark (see Spark doc), Flink, Beam, Hive, Presto/Trino, Druid.**
12. **Workflow Orchestration:** Airflow, Dagster, Prefect, Luigi, Kestra.
13. **Streaming:** Kafka Streams, Flink, Spark Structured Streaming, Kinesis, Pub/Sub.

**V. Transformation & Modeling**

14. **Dimensional Modeling:** star, snowflake, slowly changing dimensions.
15. **Data Vault, Data Mesh, Semantic Layers.**
16. **dbt, SQL-based transformations, lineage, testing.**

**VI. Infrastructure & DevOps**

17. **Infrastructure as Code:** Terraform, CloudFormation, Pulumi.
18. **Containers & Orchestration:** Docker, Kubernetes, Helm.
19. **CI/CD for Data Pipelines, GitOps, Blue-green deploys.**
20. **Monitoring & Observability:** Airflow logs, Grafana, Prometheus, data quality checks (Great Expectations, Soda).**

**VII. Security & Governance**

21. **Access Control (IAM, RBAC, ABAC), Encryption (at rest/in transit).**
22. **Data Catalog & Lineage:** Amundsen, DataHub, Collibra.
23. **Compliance:** GDPR, HIPAA, SOX.

**VIII. Performance Tuning**

24. **Cluster sizing, Spark tuning (shuffle, partitions), caching.**
25. **Cost Optimization, spot instances, serverless (AWS Glue).**

**IX. Emerging Trends**

26. **Real-time analytics, streaming ETL, CDC to lakehouse.**
27. **Data Contracts, DataOps, Reverse ETL, metrics layers.**

**X. Resources:** "Designing Data-Intensive Applications", "Streaming Systems", posts by Netflix, Airbnb, Uber.**
