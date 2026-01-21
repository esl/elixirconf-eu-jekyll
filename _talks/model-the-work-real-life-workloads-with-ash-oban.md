---
tags:
  - ashframework
  - durability
  - workloads

level: Intermediate
title: "Model the Work: Real Life Workloads with Ash & Oban"
speakers:
  - _participants/zach-daniel.md

---
At small scale, you can get away with using `schedule_at` with. When you have a large team, millions of jobs per day, hundreds of complex workflows, that approach breaks down.

In this talk, we look at real production workloads: webhook ingestion and delivery, reminders and notifications, appointment scheduling, order shipment, and fulfillment. These are long-lived, time-based workflows that need to behave predictably across retries, deploys, crashes, and changing requirements.

The core idea is simple: your jobs table is not a domain model. If a piece of work matters, it should exist as application state. A reminder isn’t an Oban job, but a Reminder that moves from unsent to sent. A shipment isn’t a background task, it’s a Shipment with a lifecycle.

We’ll walk through how we model this kind of work using Ash resources, AshStateMachine, and AshOban. This approach comes with huge benefits, as well as a few sharp edges & foot guns that we'll learn to sidestep.

Along the way, we’ll look at how this approach makes systems easier to reason about, safer to retry, and dramatically easier to refactor as requirements evolve, without losing the operational reliability you need at scale.

**Key Takeaways:**

- AshFramework, AshOban, and AshStateMachine offer novel and reliable approaches to building real life durable and reliable workloads.

**Target Audience:**

- This talk is excellent for beginners, and Ash-curious individuals who want to see how it is employed in serious use cases at scale.
