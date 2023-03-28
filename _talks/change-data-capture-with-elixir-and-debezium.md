---
level:
- Intermediate
tags:
- Elixir
- Distributed Data
title: Change Data Capture with Elixir and Debezium
speakers:
- _participants/vanessa-loviton.md
- _participants/michal-gibowski.md

---
Let’s talk about data in a distributed system. How can we avoid the problem of dual writes, reliably implement a message outbox pattern or expose information to analytics storage in real-time?

Databases distribute data to other nodes via a mechanism called replication. It turns out we can hook into it and make it digestible for our applications!

In this talk, we will learn about Change Data Capture and show how Elixir is a great fit for an application that consumes streams of data originating from database replication.

At Andjaro we do that to implement the Strangler Fig pattern and to feed our analytics data store.

**Talk objectives:**

*   to show challenges when passing state in a distributed system,
*   to introduce Change Data Capture and the Debezium project,
*   to showcase the power of unique capabilities of OTP and Elixir when syncing data between different data systems.

**Target audience:**

*   Elixir programmers interested in distributed systems and event streaming.