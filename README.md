# Notes
# Questions & Solutions Related to development
Engineered a high-throughput Apache Beam (Java) pipeline on GCP DataFlow using ParDo fusion, custom Coders, pipeline parallelism, and windowing strategies, enabling deterministic schema validation and low-latency ingestion from Oracle SQL into GCS buckets.

Tuned Autoscaling, optimized I/O backpressure, and enhanced DoFn lifecycle management with retry logic, exponential backoff, and dead-letter handling for corrupt/invalid records—achieving ~60% latency reduction and 50% improvement in heap utilization.

Developed a second BigQuery-native ETL framework using partitioned & clustered tables, materialized views, analytical SQL (OVER, QUALIFY, ARRAY) orchestrated via Python DAGs, with fault-tolerant execution and error-replay capabilities for transient query failures.

Both approaches processed 5M+ records sub-5 minutes using predicate pushdown, parallel read APIs, and optimized execution plans, reducing compute cost by ~30% and meeting strict pipeline SLAs.

Authored HLD/LLD designs, implemented IntegrationTest suites, performed EXPLAIN-stage debugging, resolved schema drift issues, and ensured idempotent + exception-safe deployments through rigorous peer reviews.
