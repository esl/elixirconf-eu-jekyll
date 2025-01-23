---
tags:
- WebAssembly
- Runtime
- Ecosystem
level: Intermediate
title: "Wasmex: Run WebAssembly Programs in Elixir"
speakers:
- _participants/philipp-tessenow.md

---
WebAssembly is a compilation target and execution environment often used in Browsers to speed up intensive algorithms that would be slow in pure JavaScript.
But Elixir can run WebAssembly too and it's about much more just speedy code execution.

In this session, we will talk about wasmex, a WebAssembly runtime written in Elixir. We investigate common use cases of WebAssembly and how they benefit Elixir hosts. If you are interested in running unsafe (user-provided) programs in your Elixir application, or you want to interface with programs written in other programming language, or even in speeding up your algorithms, this talk is for you.

In addition to interesting use cases and examples, we investigate the architecture of wasmex and examine tradeoffs that need to be considered when running WebAssembly payloads.

**Key Takeaways:**
- An introduction to WebAssembly, its main properties and how it can be useful to an Elixir developer
- Discovery of common use cases for WebAssembly and concrete examples of how to apply them to Elixir
- Concrete example on how one can integrate WebAssembly into existing Elixir applications using wasmex
- A glimpse under the hood of wasmex, revealing how it works and where potential limitations are
- Motivation to dig deeper and go explore, as the talk hints at a few open problems and ideas

In general, I want to  spark some excitement about WebAssembly and Elixir. I want to enable the audience to play with new ideas, languages, code distribution concepts through Wasm while still being able to use their favorite language. My goal is to give beginners and seasoned Elixir devs alike a new tool to work with.

**Target Audience:**
- Elixir developers of all levels who may have heard about WebAssembly but never tried it (give them ideas & use cases to explore)
- Seasoned Elixir developers who want to contribute to this space (future & open problems)
- Developers who need to interface with code from different programming languages (that compile into WebAssembly) or have to run user-provided code safely (in a WebAssembly sandbox)
- People who like to play with different programming languages or runtimes, while still connecting this interest to Elixir
