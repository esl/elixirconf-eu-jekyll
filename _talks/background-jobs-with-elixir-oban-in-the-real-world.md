---
tags:
  - scale-distributed-oban

level: Intermediate
title: "Background Jobs with Elixir: Oban in the Real World"
speakers:
  - _participants/noelia-lencina.md

---
Background jobs are a staple in any seasoned engineer’s toolbelt. But in an ecosystem where OTP is readily available and concurrency is a first-class citizen, where exactly does a library like Oban fit? And more importantly, what happens when you hit the "scaling wall" of 10 million jobs a day?

Thinking of background processing at this magnitude requires a shift in strategy. It’s no longer just about using the library, it’s about leveraging advanced database techniques and the full power of Distributed Elixir (Erlang). Drawing from a production-proven implementation, we will explore:
- The "Why": A critical comparison of Oban vs. pure GenServers vs. Broadway. When is the overhead of a database-backed queue a feature, and when is it a bottleneck?
- The "How": Solving real-world challenges including strict rate-limiting for brittle external APIs, managing job distribution across a multi-node cluster, and handling dynamic scheduling (from crontabs to self-enqueueing recursive workers).
- The "Cost": Tactical patterns for maintaining Postgres health under high-volume job churn, focusing on index bloat, pruning, and transactional integrity.

**Key Takeaways:**

- 1. The "When" and "Why" of Background Jobs: A clear mental model for choosing between GenServers (ephemeral/fast), Broadway (external stream processing), and Oban (transactional/reliable).

- 2. Specific strategies for managing Postgres health (pruning, indexing, and IOPS) when your job table becomes the busiest part of your database.

- 3. Distributed Patterns: How to orchestrate Oban across a Distributed Erlang cluster (e.g., Fly.io), ensuring workers are distributed correctly without overloading specific nodes.

- 4. Patterns for handling real world scenarios, like implementing rate-limiters for external APIs and building self-healing recursive workers that can survive third-party downtime.

- 5. Dynamic Scheduling: Moving beyond static configs to handle complex business requirements, such as dynamic scheduling and self-enqueueing logic.

**Target Audience:**

- People working with Elixir in production, possibly dealing with large volumes of data and interested in architecture design.
