---
experience:
- Intermediate
title: "The BEAM for Developers"
type: in-person full-day training course
venue: NH Málaga
trainers:
- _participants/erik-stenman.md
event_date: 22 April

---
This is a full-day, hands-on introduction to the Erlang Runtime System and the BEAM virtual machine.

The course focuses on how the runtime works in practice: processes, message passing, memory management, garbage collection, and scheduling. These mechanisms determine how BEAM systems behave under load, during failures, and over long runtimes.

The goal is to give you a correct mental model of the VM so you can reason about performance, reliability, and system behavior without guesswork.

**What we cover:**
*Thinking in Processes*
How to structure systems as many small, isolated processes that communicate through messages. We use the Gnome Village model to reason about responsibilities, failure isolation, and supervision.

*Data Types and Messaging*
How data is represented in the BEAM. How process heaps work. What actually happens when messages are sent between processes, including copying, binaries, and references.

*Memory and Garbage Collection*
Per-process heaps, generational garbage collection, binary handling, and common sources of memory growth. How to spot and avoid long-term memory problems.

*Scheduling and Concurrency*
Reductions, run queues, and SMP schedulers. How the BEAM balances throughput and latency, and why some workloads behave predictably while others do not.

*Debugging and Observability*
How to inspect live systems using built-in tools. We work with tracing, profiling, and runtime inspection using tools such as Observer and Recon.

*Patterns and Anti-Patterns*
Designs that cause problems in real systems: overloaded mailboxes, large binaries in messages, centralized processes, and hidden bottlenecks. How to restructure systems when these show up.

**Format:**
The day alternates between short theory sections and practical exercises.
You will trace message flows, inspect memory usage, observe scheduler behavior, and analyze small systems to understand their runtime characteristics.
The exercises are designed to build understanding, not to produce a finished application.

**Target audience:**
This course is for developers working with Elixir, Erlang, Gleam, or other BEAM languages.
You should be comfortable writing basic BEAM code and using OTP. No prior knowledge of runtime internals is required.

**Experience level:** Intermediate
**Requirements:** Laptop with the BEAM and your preferred language installed
