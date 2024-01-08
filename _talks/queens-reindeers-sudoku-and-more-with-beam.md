---
level:
- Intermediate
tags:
- Solvers constraints optimization
audience: "- Everyone who is interested in BEAM and business decision-making."
format: Virtual
title: "Queens, Reindeers, Sudoku and more with BEAM"
speakers:
- _participants/boris-okner.md
key_takeaways: " - Constraint programming is a prescriptive technology, which means it produces exact solutions to combinatorial problems, as opposed to machine learning, which is a predictive technology. Erlang and Elixir are very good choices for the implementation of competitive Constraint Programming solvers. The field of applications of constraint programming is huge, so developing solvers may significantly contribute to promoting BEAM."

---
Constraint programming is a paradigm for solving combinatorial problems. CP solvers such as Google's OR-Tools, IBM's CPLEX, Gecode, and many others are adopted by the industry for decision-making on a huge range of problems, such as planning, scheduling, and optimization of business processes... Every major programming language has constraint programming tools, so why not have it in Elixir?

In the <a href="https://www.amazon.com/Concepts-Techniques-Models-Computer-Programming/dp/0262220695">book</a> by Peter Van Roy and Seif Haridi, the authors suggest that the constraint programming paradigm can be efficiently implemented using a "maximally concurrent" model, which makes BEAM a great candidate for the implementation of CP solvers.

The project that I'm going to talk about is <a href="https://github.com/bokner/fixpoint">Fixpoint</a>.
 
<a href="https://github.com/bokner/fixpoint/blob/main/livebooks/fixpoint.livemd">LiveBook</a> demonstrates the current capabilities of the Fixpoint solver.