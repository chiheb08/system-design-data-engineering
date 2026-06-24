# Learning Roadmap

Topics are ordered so each lesson builds on the last.

## Phase 1 — Foundations (you are here)

- [x] **Core System Design Foundations** — statelessness, caching, CAP, message queues, databases, API design
- [ ] Scalability basics — horizontal vs vertical, load balancing, partitioning
- [x] **Data modeling** — fact tables, dimensions, grain, SCDs, star vs snowflake schema
- [ ] Batch vs streaming — when to use each, lambda vs kappa

## Phase 2 — Data Engineering

- [ ] ETL / ELT pipelines — orchestration, idempotency, backfill
- [ ] Data warehouses — Snowflake, BigQuery, Redshift concepts
- [ ] Stream processing — Kafka, Flink, Spark Streaming
- [x] **Apache Iceberg** — open table format, snapshots, time travel, lakehouse maintenance
- [ ] Data quality — contracts, validation, lineage, SLAs

## Phase 3 — System Design Deep Dives

- [ ] Design a metrics pipeline
- [ ] Design a real-time analytics dashboard
- [ ] Design a CDC (Change Data Capture) system
- [ ] Design a data lake / lakehouse — see [Apache Iceberg](docs/data-engineering/apache-iceberg.md)

## Phase 4 — Production & Interview

- [ ] Observability for data systems
- [ ] Cost optimization at scale
- [ ] Mock system design interviews with rubrics
