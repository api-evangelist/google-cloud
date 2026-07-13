---
title: "Safely run AI-generated code in Cloud Run sandboxes"
url: "https://cloud.google.com/blog/topics/developers-practitioners/google-cloud-run-sandboxes-are-in-public-preview/"
date: "2026-07-09"
author: "Ryan Pei"
feed_url: "https://cloudblog.withgoogle.com/rss/"
---
Here’s a question we hear often at Google Cloud: How do you safely run AI-generated code or untrusted binaries without putting your host application, data, and cloud credentials at risk? In other words, how do you give AI-written programs a safe space to run — one that keeps them completely separate from your trusted programs with higher privileges? Until now, developers had to build complex sandboxing infrastructure using container clusters or pay for specialized third-party microVM runtimes.
