# Google Cloud Platform GraphQL Schema

## Overview

Google Cloud Platform does not expose a unified public GraphQL API. GCP's primary programmatic interface is REST-based via the googleapis family of endpoints, with client libraries available in multiple languages through the [Cloud SDK](https://cloud.google.com/sdk) and [googleapis GitHub organization](https://github.com/googleapis).

This schema is a conceptual GraphQL representation of the major GCP service domains. It can serve as:

- A reference for teams building GraphQL federation layers on top of GCP REST APIs
- A starting point for internal developer portals that expose GCP resource state through GraphQL
- A companion to tools like [Config Connector](https://cloud.google.com/config-connector/docs/overview), which exposes GCP resources as Kubernetes CRDs

## Service Domains Modeled

The schema spans the following GCP service categories:

- **Compute** — Compute Engine instances, machine types, disks, snapshots, images, networks, subnets, firewalls, load balancers, backend services, instance groups, and autoscalers
- **Storage** — Cloud Storage buckets, objects, storage classes, transfer jobs, and backups
- **Databases** — Cloud SQL, Spanner, Bigtable, Firestore, Memorystore (Redis/Memcached), AlloyDB
- **Kubernetes** — GKE clusters, node pools, Kubernetes nodes
- **Serverless** — Cloud Functions, Cloud Run services, Cloud Run jobs
- **Big Data** — BigQuery datasets, tables, jobs; Dataflow jobs; Pub/Sub topics and subscriptions; Dataproc clusters
- **AI/ML** — Vertex AI endpoints, AutoML models, training jobs, predictions, batch predictions, text embeddings
- **Security & IAM** — IAM policies, service accounts, KMS keys, Secret Manager secrets, Cloud Armor policies, VPC Service Controls access policies
- **DevOps** — Cloud Build triggers and builds, Artifact Registry repositories, container images, Cloud Deploy pipelines, Cloud Source Repositories
- **Networking** — Cloud DNS, Cloud CDN, Cloud NAT, VPN gateways, Interconnect attachments, Cloud Router
- **Observability** — Cloud Monitoring metrics and alert policies, notification channels, dashboards, Cloud Logging entries and sinks, Cloud Trace spans

## Source References

- GCP API Explorer: https://cloud.google.com/apis/explorer
- googleapis GitHub: https://github.com/googleapis
- GCP REST API docs: https://cloud.google.com/apis
- Config Connector CRD reference: https://cloud.google.com/config-connector/docs/reference/overview
- Compute Engine REST API: https://cloud.google.com/compute/docs/reference/rest/v1
- Cloud Storage JSON API: https://cloud.google.com/storage/docs/json_api
- GKE REST API: https://cloud.google.com/kubernetes-engine/docs/reference/rest
- BigQuery REST API: https://cloud.google.com/bigquery/docs/reference/rest
- Vertex AI REST API: https://cloud.google.com/vertex-ai/docs/reference/rest
- Cloud Monitoring API: https://cloud.google.com/monitoring/api/ref_v3/rest

## Schema File

See [google-cloud-schema.graphql](google-cloud-schema.graphql) for the full type definitions.
