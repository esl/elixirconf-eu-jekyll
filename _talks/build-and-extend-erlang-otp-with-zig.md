---
level:
- Intermediate
tags:
- Erlang
- OTP
- Ziglang
title: Build and Extend Erlang OTP with Zig
speakers:
- _participants/marcel-lanz.md

---
In this talk, we explore how to build and extend Erlang OTP using Zig, "a general-purpose programming language and toolchain for maintaining robust, optimal and reusable software".

Zig is able to be a gradual catalyser to incrementally improve an existing codebase. Taking Erlang OTP with its modular structure written in C and C++ is a great example of how Zig can be introduced into a non-trivial codebase.

While Erlang OTP is a very active and established open source project that has a great community refining and extending it, it can be intimidating for a younger generation of programmers to contributing. Zig with its modern and simple language can help to attract this younger generation of open source enthusiasts and help to grow and sustain interest in OTP and its great foundation for distributed systems development.

At eigr.io we're dedicated to spread the word of the BEAM. We're committed to help to bring the way Erlang, Elixir and the BEAM works to a younger and a cloud native audience in general.

**Talk objectives:**	
* The audience will understand how Zig and its toolchain can be used to build Erlang OTP with its zero-dependency, drop-in C/C++ compiler that supports cross-compilation out-of-the-box. We'll discover how to implement NIFs in Zig and even how to port an existing OTP application into an equivalent Zig implementation.

**Target audience:**
* The talk would likely be of interest to developers who are familiar with Erlang OTP and are looking for ways to improve their development workflow.
* Similar, the talk could inspire a younger audience of programmers like to participate and contribute to Erlang OTP using a modern and attractive programming language with a clean and concise syntax.