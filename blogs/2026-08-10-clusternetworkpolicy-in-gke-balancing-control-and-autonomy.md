---
title: "ClusterNetworkPolicy in GKE: Balancing control and autonomy for your microservices"
url: "https://cloud.google.com/blog/products/networking/new-clusternetworkpolicy-in-gke/"
date: "2026-08-10"
author: "Srini Jasti"
feed_url: "https://cloudblog.withgoogle.com/rss/"
---
Managing network security in a multi-tenant Kubernetes environment typically requires balancing two distinct needs: developers need their microservices to communicate effectively, while platform and security teams must maintain compliance, prevent lateral movement, and establish cluster-wide guardrails. Historically, the standard Kubernetes NetworkPolicy has been the primary tool for this. While effective for single-namespace isolation, standard NetworkPolicy is scoped strictly to individual namespaces and designed around developer self-service.
