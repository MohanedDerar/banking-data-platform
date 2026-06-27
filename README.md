# Banking Data Platform

End-to-end data engineering project simulating a banking transaction 
platform: ingestion → transformation → streaming fraud detection → 
orchestration, built on AWS.

> 🚧 Work in progress — building in public as part of a structured 
> Data Engineer upskilling roadmap.

## Architecture
(diagram coming)

## Tech Stack
- Ingestion: AWS Glue (PySpark)
- Storage: S3
- Transformation: dbt + Redshift/Athena
- Streaming: Kinesis Data Streams + Lambda
- Orchestration: Amazon MWAA (Airflow)

## Status
- [ ] Synthetic data generator
- [ ] Glue PySpark ingestion job
- [ ] dbt transformation layer + tests
- [ ] Kinesis streaming fraud detection
- [ ] Airflow/MWAA orchestration
- [ ] Architecture diagram