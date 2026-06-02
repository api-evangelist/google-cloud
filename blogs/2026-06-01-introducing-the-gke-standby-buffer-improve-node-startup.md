---
title: "Introducing the GKE standby buffer: Improve node startup times without blowing your budget"
url: "https://cloud.google.com/blog/products/containers-kubernetes/gke-standby-buffers-speed-up-autoscaling-for-less-spend/"
date: "2026-06-01"
author: "Eyal Yablonka"
feed_url: "https://cloudblog.withgoogle.com/rss/"
---
Application owners and platform engineers have long faced a difficult choice: spend excessively by over-provisioning to guarantee quick startups, or minimize costs but endure slow cold starts. We are excited to announce a solution to this compromise: Google Kubernetes Engine standby buffers. This builds on the launch of GKE active buffers earlier this year, a native version of the Kubernetes CapacityBuffers API that makes it easy to provision readily available capacity to handle traffic spikes, delivering near-zero startup latency for new pods.
