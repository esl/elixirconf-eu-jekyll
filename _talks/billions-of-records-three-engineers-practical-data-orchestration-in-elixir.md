---
tags:
  - etl
  - postgres
  - pragmatic

level: Intermediate
title: "Billions of Records, Three Engineers: Practical Data Orchestration in Elixir"
speakers:
  - _participants/silvia-zeamer.md

---
In 2018, we decided to rewrite our Groovy-based data platform in Elixir. Today, we run roughly 25,000 jobs processing 2 billion records per day in a single Elixir/Phoenix application. We (Tolemi) integrate with and combine hundreds of various data sources to provide municipal governments across the USA with daily spatial data insights.


In this talk, I’ll walk through the key design decisions that allowed a team of three to migrate to Elixir, scale to this level while keeping complexity low and enabling implementation developers to contribute to our data pipelines.


We use Elixir’s concurrency model for orchestration, and Elixir as a glue layer that allows databases, containers, and scripts written in other languages (Python, DuckDB, Groovy, R scripts) to be used where they are most effective.


Through a series of practical code snippets and architectural choices, I will share the hard-won lessons and specific performance bottlenecks we overcame to maintain a lean, high-throughput data pipeline.

**Key Takeaways:**

- Design choices that helped us structure an Elixir Phoenix server to support large-scale concurrent spatial data ingestion and processing while optimizing for operational simplicity and maintainability.

**Target Audience:**

- Engineers interested in:
- Using simple Elixir to concurrently process high volumes of data
- Integrating scripts and tools built in different technologies
- Scaling services while limiting complexity and prioritizing maintainability by a small team
