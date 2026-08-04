---
title: "Minimize idle accelerators: Native RL job interleaving with co-operative time-slicing in llm-d"
url: "https://cloud.google.com/blog/products/containers-kubernetes/introducing-co-operative-time-slicing-for-rl-in-llm-d/"
date: "2026-07-23"
author: "Poonam Lamba"
feed_url: "https://cloudblog.withgoogle.com/rss/"
---
The math behind reinforcement learning (RL) post-training for large language models (LLMs) is notoriously unforgiving. As frontier AI labs push the boundaries of reasoning and coding models using RL post-training algorithms like Group Relative Policy Optimization (GRPO), they routinely hit hard architectural and infrastructure constraints. While much of the industry's focus remains on acquiring raw accelerator capacity, infrastructure efficiency is equally critical for achieving the high velocity needed to run multiple RL jobs and drive models to higher levels of intelligence.
