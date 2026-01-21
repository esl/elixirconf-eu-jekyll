---
tags:
  - gust
  - orchestration
  - dags

level: Introductory and overview
title: "Rebuilding Workflow Orchestration in Elixir: The Story of Gust"
speakers:
  - _participants/marcio-klepacz.md

---
A case study on building Gust, a durable workflow orchestration system in Elixir, after getting frustrated with Python/Airflow. I’ll break down what “orchestration” really means, what Airflow does well (and where it gets heavy), then walk through Gust’s core pieces: task, scheduling, retries, logs/observability, and secrets. Finally, I’ll show how OTP supervision and lightweight processes enabled a simpler, more reliable engine with major efficiency and performance gains.

**Key Takeaways:**

- Know what an orchestration system is, what problems it solves, what Airflow and Gust are, and how they differ from a background job library.

**Target Audience:**

- Platform / ML engineers, as well as tech managers.
