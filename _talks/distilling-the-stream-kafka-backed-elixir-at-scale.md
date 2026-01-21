---
tags:
  - kafka-practical-production

level: Advanced
title: "Distilling the Stream: Kafka-Backed Elixir at Scale"
speakers:
  - _participants/anton-borisov.md
  - _participants/piotr-rybarczyk.md

---
At Fresha, Kafka is a core part of how many of our Elixir applications are designed and operated.
In this talk, we share how we build Kafka-backed applications in Elixir at scale: the patterns we standardised on, the trade-offs we made and the mistakes we learned from in production.

We'll focus on how Kafka fits into application design rather than treating it as a generic messaging layer, and on how we make its use consistent and safe across teams.

We'll also cover what we had to build and contribute to support this approach, including upstream work on kafka_ex (authentication, new compression codecs and support for newer Kafka APIs and protocol versions) and internal Elixir tooling, which we're in the process of open-sourcing, that encodes core patterns such as partitioning and consumer concurrency, Inbox and Outbox patterns, retries with backoff, dead-letter handling, tracing and operational visibility.

This is a practical, opinionated talk based on real production experience, for teams building serious Kafka-based systems in Elixir.

**Key Takeaways:**

- How to treat Kafka as part of application architecture, not infrastructure

- Where Kafka boundaries should live in Elixir systems and where they should not

- Which reliability guarantees can be enforced centrally and which cannot

- How production failures shape Kafka design choices more than theory

- What standardisation actually buys you at scale (and what it costs)

**Target Audience:**

- Backend engineers, staff/principal engineers and technical leads building distributed systems in Elixir, especially those using or considering Kafka in production.

- Example article where I follow the implementation of SASL auth in kafka_ex: https://medium.com/fresha-data-engineering/adding-authentication-to-elixir-native-kafka-client-trust-but-verify-f7d6d3876cff
