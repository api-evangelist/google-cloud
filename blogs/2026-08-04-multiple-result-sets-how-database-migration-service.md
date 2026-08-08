---
title: "Multiple result sets: How Database Migration Service automates SQL server to PostgreSQL translation"
url: "https://cloud.google.com/blog/products/databases/automating-postgres-translations-with-database-migration-service/"
date: "2026-08-04"
author: "Assaf Fraenkel"
feed_url: "https://cloudblog.withgoogle.com/rss/"
---
In the Medium blog post, " From MARS to SETOF REFCURSOR: Migrating Multi-Result Stored Procedures to PostgreSQL ," we explored the fundamental architectural differences between SQL Server and PostgreSQL regarding multiple result sets. We looked at how SQL Server natively streams multiple tabular streams from a single execution, whereas PostgreSQL requires a more deliberate strategy using explicit cursor manipulation. If you’re facing a massive database migration with hundreds of these procedures, manually rewriting them is a non-starter.
