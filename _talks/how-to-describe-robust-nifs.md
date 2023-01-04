---
level:
- Intermediate
tags:
- VIRTUAL
- NIFs
- Fault-Tolerant Systems
- Higher Performance
title: 'How to Describe Robust NIFs: : Bridging Elixir and C with Performance for
  Fault-tolerant Systems'
speakers:
- _participants/susumu-yamazaki.md

---
When implementing a system that requires performance, we sometimes use NIFs, a mechanism for calling higher-performance C code from Elixir. NIFs perform better than Port, another mechanism to call C. However, they have the disadvantage that if they crash, the entire Erlang VM will be abnormally terminated, even under Supervisor's control. This defect is a significant obstacle when building fault-tolerant systems.

This talk shows three points to describe robust NIFs:
1. Appropriately set a conditional branch where each function call may return an uncertain value.
2. Perform error handling according to general conventions.
3. Make assertions that specify implicit preconditions and raise exceptions for Supervisor to handle.
This talk also shows how to improve performance even with such robustness and fault tolerance and build NIFs for various platforms.