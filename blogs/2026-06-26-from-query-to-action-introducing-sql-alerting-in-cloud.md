---
title: "From query to action: Introducing SQL alerting in Cloud Monitoring Observability Analytics"
url: "https://cloud.google.com/blog/products/management-tools/alert-with-sql-in-cloud-monitoring-observability-analytics/"
date: "2026-06-26"
author: "Joy Wang"
feed_url: "https://cloudblog.withgoogle.com/rss/"
---
Traditional alerting systems often force a compromise: you can either alert immediately on simple, noisy log events, or monitor rigid, pre-configured metrics that fail when faced with data with many unique answers like user sessions or IP addresses. But the most critical system issues — like a 20% spike in error rates for a specific customer or a latency anomaly correlated with database timeouts — are hidden in the aggregates and relationships between these signals. Recently, we announced that you can now use SQL to query logs and traces in Observability Analytics (formerly Log Analytics).
