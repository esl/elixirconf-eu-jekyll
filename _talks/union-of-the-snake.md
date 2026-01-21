---
tags:
  - cross-polination
  - dynamic
  - concurrent

level: Intermediate
title: "Union of the Snake"
speakers:
  - _participants/shannon-selbert.md
  - _participants/parker-selbert.md


---
How do you port a highly concurrent framework from Elixir—a platform with arguably the best concurrency story in the industry—to Python, a language with a flawed one at best? In this talk, we'll show how we tried, and along the way managed to prove "Virding's First Rule of Programming".

This goes deeper than wrestling with mutability or the emotional burden of imperative loops. We'll dig into the techniques we used to work around Python's concurrency limitations in order to implement a BEAM-inspired architecture, including:

* Supervising autonomous objects
* Monitoring object lifecycles
* Replicating GenServers with async loops
* Communicating without native distribution

You'll have a renewed appreciation for Elixir: an expressive syntax, fantastic tooling, and a community that converges on a shared set of fundamental abstractions. Nothing clarifies the strengths of a system quite like trying to rebuild it elsewhere.

Come and learn how we blended Elixir's sensibilities with Python's semantics to build the best async, concurrent, distributed background job framework we could manage—and what we learned in the process.

**Key Takeaways:**

- How BEAM primitives apply to other languages without the same tools or paradigms
- Why the standardization and ubiquity of tools in the Elixir ecosystem are a strength

**Target Audience:**

- Elixirists from an OOP background, perhaps who have dabbled in Python. Also people newer to the BEAM that want to understand how some of the OTP primitives work, and why they exist in the first place.
