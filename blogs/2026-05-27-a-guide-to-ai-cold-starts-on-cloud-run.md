---
title: "A Guide to AI Cold Starts on Cloud Run"
url: "https://cloud.google.com/blog/topics/developers-practitioners/a-guide-to-ai-cold-starts-on-cloud-run/"
date: "2026-05-27"
author: "Shir Meir Lador"
feed_url: "https://cloudblog.withgoogle.com/rss/"
---
I saw a developer asking on Reddit if there was any “sane way” to manage Cloud Run cold starts for AI across multiple regions. They were experiencing startup latencies of up to 20 seconds, a frustrating gap where the infrastructure is spinning up while the user waits for a response. The discussion was full of developers who had almost given up on serverless GPUs, with some even migrating back to GKE just to escape the latency.
