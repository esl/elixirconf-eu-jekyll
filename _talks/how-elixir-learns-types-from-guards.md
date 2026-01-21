---
tags:
  - type-system
  - guards

level: Intermediate
title: "How Elixir Learns Types from Guards"
speakers:
  - _participants/guillaume-duboc.md

---
Elixir's type system derives type information directly from guard expressions rather than introducing a separate type language. This talk examines the mechanics: how the checker interprets is_* guards as base types, how conjunction and disjunction translate to intersection and union types, and how negation types emerge from clause ordering. We'll look at the inference rules, walk through non-obvious cases, and explore where the current implementation hits its limits.

**Key Takeaways:**



**Target Audience:**


