---
tags: TigerBeetle, NIFs, Zig
level: Intermediate
title: "TigerBeetlex: An Elixir and Zig Love Story"
speakers: - _participants/riccardo-binetti.md

---
What if your application database could process financial transactions up to 1000x faster than a general purpose database? That's the goal of TigerBeetle, a distributed financial accounting database designed for mission critical safety and performance.

In this talk I will introduce TigerBeetle and its data model, and show how you can use it in your Elixir applications with TigerBeetlex, an Elixir client built upon its official Zig client.

After exploring the library's API, we'll dive into its internals. You will learn about the details of how binaries are implemented in the BEAM VM, understand NIF resources, and discover how TigerBeetle's non-blocking API pairs perfectly with Elixir's message-passing.

We will also cover some of the tradeoffs in the design of the library (e.g. macros vs code generation, efficient mutability vs familiar immutability) and why these decisions matter for developers aiming to build idiomatic Elixir libraries.

**Key Takeaways:**
- Learn to use TigerBeetle with your Elixir application
- Explore ways to share data between a NIF and Elixir code
- Understand how to identify and navigate design tradeoffs

**Target Audience:**
Programmers who want to use TigerBeetle with their Elixir applications
- Developers who are interested in NIFs and BEAM internals
- Programming Language enthusiasts curious about Zig

