---
tags:
  - liveview
  - loadtesting
  - flame

level: Introductory and overview
title: "A Murder of LiveViews: Distributed Load Testing with AMoC and FLAME"
speakers:
  - _participants/coby-benveniste.md

---
A little over a decade ago, Phoenix proved that it could handle 2 million WebSocket connections. A lot has changed since then, and with LiveView, the paradigm has shifted! Connections aren't the only bottleneck anymore, your LiveView architecture is. How you structure Functional Components, LiveComponents, Streams, and Async Assigns all affect performance under load. How do you know your app can handle real traffic? This talk introduces a distributed approach using AMoC ("A Murder of Crows" from Erlang Solutions) and FLAME to coordinate thousands of users across elastically scaled compute. You'll learn to write scenarios measuring what actually matters for LiveView performance: mount and event round-trip latencies, diff sizes, and LiveView performance across different LiveView patterns. We'll explore the architecture, walk through scenario design, and depending on where progress is at, demonstrate spinning up distributed runners against a live application.

**Key Takeaways:**

- The audience will learn why traditional tools fall short for load testing LiveView based applications and how Elixir and the BEAM can be used to build a distributed architecture that addresses these gaps. The talk covers how AMoC works to coordinate parallel user processes across machines, and how FLAME provides elastic compute that scales from zero. Together, we'll walk through how these tools work together through the BEAM's distribution mechanisms, without any need to create custom mechanisms for coordinating distributed load. Attendees will learn to write scenarios that measure the crucial LiveView metrics under load and walk away with the foundation to implement distributed load testing for their own applications.

**Target Audience:**

- Anyone building production applications with LiveView who wants to understand their performance characteristics under load. The target audience should ideally have familiarity with LiveView, but no prior experience with load testing, distributed systems, or the specific tools is needed, we'll walk through and learn everything together during the talk. Anyone who has wondered "can my app handle real traffic?" will find this relevant.
