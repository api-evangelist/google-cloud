---
title: "The Risk of Exposed Cloud Functions and How to Harden"
url: "https://cloud.google.com/blog/topics/threat-intelligence/exposed-cloud-functions-harden/"
date: "2026-07-15"
author: "Mandiant"
feed_url: "https://cloudblog.withgoogle.com/rss/"
---
Written by: Corné de Jong Introduction Mandiant security assessments frequently identify publicly exposed serverless applications that lack authentication, often as a result of specific business requirements. Serverless deployments typically run custom-developed code that incorporates third-party packages, making them targets for a wide range of application-level attacks, including: Local and Remote File Inclusion (LFI/RFI) Command Injection Successful exploitation of these vulnerabilities can grant an attacker full control over the underlying container instance. Such access can serve as a foo
