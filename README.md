# [Traml Labs Private Limited](https://www.traml.com/)
I'am [Nagendra Bhat](https://www.linkedin.com/in/nagendrab/), founder and director of Traml Labs. 

I'am a tech enthusiast and integration specialist having more than two decades of Software Development, Maintenance and Support experience.

This repo is an effort to host code samples and learnings during development of Traml Data Platform


# Traml Data Platform 
- Highly Scalable Multi Tenant platform supports zero data loss (RPO)
- Supports Safestore, Transform, Delivery
- Supports Safestore, ETL and Delivery

Following is the list of features of core platform
## Data source
- Originally Traml Data Platform suppored Email/SMTP integration with Google Apps Mail via SMTP adaptor as data source. 
- Now supports Webhook, Messaging like MQs, Solace, Kafka based sources. 
- Batch file
  - Throttling, scaling
  - Multi file logical boundary
  - Replay/Reprocess

## Storage
- For transactional flow, preferes Postgres. 
- Mongo is supported for both transactional and analytics use cases. 
- Object Stores (GCS, S3)

## Interfaces
- Realtime event out for MQ, Kafka, DBs, Object Store (GCS and S3), Webhooks
- On-demand:
  - Batch request/download
  - RESTful APIs
  - RESTful request/event out
  
## Analytics
- Apache Presto
- Big Query

## Data formats
- MIME Multipart
- JSON
- XML
- Avro
- Parquet

## Versioning
- Schema versioning
  - Global at the Platform Level
  - Tenant Specific
- API versioning
 
## Security
- SSL (Mutual TLS wherever feasible)
- Integration with Cloud KMS, Hashicorp Vault
- Workload Idenitfy (GCP)
- IAM (AWS)
- API Keys
- JWT
- Encryption at storage via underlying technologies
- RBAC and ABAC
- Key rotation and compromise management
 
## Optimaziations
- Data compressions via underlying technologies

## Self service
- Tenant management
- Schema registry
- SRE dashboard
- Manual Message Creation with Maker Checker
- Data Life Cycle Management
  - Storage layer
  - Purge
  - Archival
  - Legal Hold (GCS)
