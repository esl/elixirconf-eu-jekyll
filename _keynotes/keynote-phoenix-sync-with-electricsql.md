---
tags: Phoenix, sync, Electric
level: Intermediate
title: "Introducing Phoenix.Sync"
speakers:
- _participants/james-arthur.md
published: true

---
This talk introduces Phoenix.Sync, a new library that adds real-time sync to Postgres-backed Phoenix applications.

Software is increasingly being built on sync. It's the secret sauce behind fast, collaborative apps with a great user experience, like Figma and Linear; and the new wave of AI apps and agents that need to run low latency inference on live, local data.

Phoenix has long had a rich set of state transfer and real-time primitives. However, as José outlined in his keynote at ElixirConf US in September 2024, these don't fully solve sync. Particularly the hard challenges of partial replication, fan out and resilient data delivery at scale.

This talk introduces <i>Phoenix.Sync</i>, a new library that realises José's vision of adding real-time sync to Phoenix. It allows you to sync data into both Phoenix.LiveView and frontend web and mobile applications. Using familiar function and macro APIs that integrate with <i>Plug</i> and <i>Phoenix.{Controller, LiveView, Router, Stream} </i>.

**Key Takeaways:**
- Introduce the new https://hexdocs.pm/phoenix_sync library
- Learn how to sync data from Postgres into backend Elixir and LiveView applications.
- Learn how to sync data through Phoenix into front-end web and mobile applications.
- See the type of applications and AI systems you can build with Phoenix and sync.

**Target Audience:**
- Elixir developers.
- Phoenix developers.
- LiveView developers.
- Front-end developers.
- All developers working on:
* realtime / multi-user systems
* web and mobile applications
* AI applications
* AI agents
* local-first software


This talk is suitable for all levels:
- easy to understand and usable by beginners
- interesting for intermediate and advanced
