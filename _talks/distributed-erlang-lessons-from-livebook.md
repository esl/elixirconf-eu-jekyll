---
tags:
  - distributederlang-productionpatterns-livebook

level: Intermediate
title: "Distributed Erlang Lessons from Livebook"
speakers:
  - _participants/hugo-barauna.md

---
Livebook runs each notebook on its own BEAM node, connects to Phoenix apps transparently, and spins up runtimes on remote machines, all without EPMD. How?

In this talk, we'll highlight three distributed Erlang techniques from Livebook's source code. For each one, you'll see the real-world Livebook feature first, then the Erlang primitive that powers it, followed by a simple standalone example you can use immediately.

**Key Takeaways:**

- Understand distributed Erlang primitives
- Gain practical patterns for real-world Erlang distributed
- See how a production system uses Erlang distributed

**Target Audience:**

- Elixir developers who want to level up their distributed Erlang knowledge.
