---
experience:
- Intermediate
title: "Advanced Concurrency Patterns in Elixir"
type: in-person full-day training course
venue: NH Málaga
trainers:
- _participants/andrea-leopardi.md
event_date: 22 April

---
Elixir’s concurrency story doesn’t stop at GenServer. In this tutorial, we’ll explore advanced concurrency patterns and building blocks that help you design systems that scale, stay responsive under load, and shut down gracefully.

We’ll look at tools such as PartitionSupervisor and Registry for structuring and locating processes, and discuss when and how to use lower-level primitives like atomics, counters, and persistent_term to optimize performance. We’ll also dive into process pooling strategies, gen_statem for modeling complex workflows, and techniques for designing advanced supervision trees.

Finally, we’ll cover graceful shutdown and lifecycle management - how to make sure your concurrent systems behave predictably not only when things go right, but also when they don’t.

This is an intermediate-level tutorial for developers who are already comfortable with Elixir’s basics and want to go beyond “easy” process/message passing - focusing instead on the kinds of concurrency patterns that draw many people to Elixir in the first place.
