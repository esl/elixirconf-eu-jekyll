---
audience: []
tags: []
title: Observable Elixir
speakers:
- _participants/bernardo-amorim.md
published: false

---
Either because things went wrong or because you just want to keep improving your system, you need to be able to understand it. An observable system is one that you can infer its internal state by only using its outputs. Join me while we go through my journey of making an Elixir system observable.

**Talk Objectives**

* Understand the high-level view of the "Three Pillars of Observability" (Logs, Metrics and Traces)
* Understand why \`:telemetry\` is such an amazing piece of the BEAM ecosystem
* Understand the value of structured logging and how to implement it
* Know what metrics are and why they are more suited for analyzing trends and storing data for longer than logs
* Know how to setup PromEx as an easy way to have prometheus metrics
* Know what OpenTelemetry is and the current state of OpenTelemetry for the BEAM

**Target Audience**

* Intermediate Elixir developers that are running Elixir in production