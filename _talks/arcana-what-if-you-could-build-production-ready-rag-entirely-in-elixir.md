---
tags:
  - rag
  - nx
  - agent

level: Intermediate
title: "Arcana: What If You Could Build Production-Ready RAG Entirely in Elixir?"
speakers:
  - _participants/george-guimaraes.md

---
In this talk, I'll introduce Arcana (https://github.com/georgeguimaraes/arcana), an open-source library that brings RAG to the BEAM. Using Nx and Bumblebee, Arcana runs embedding models locally, no external APIs needed. Combined with pgvector for vector storage and Phoenix LiveView for the dashboard, you get a complete RAG solution that feels native to Elixir.

We'll cover:
- How RAG works and why it matters for AI applications
- Running embedding models locally with Nx and Bumblebee
- Efficient document chunking strategies
- Vector similarity search with pgvector
- Building agentic RAG pipelines: query expansion, re-ranking, and self-correcting answers
- Pluggable components via behaviour: swap any pipeline step with your own implementation
- Building an evaluation framework to measure retrieval quality

You'll leave with practical knowledge to add semantic search and agentic RAG capabilities to your Phoenix applications, keeping your AI stack simple, fast, and 100% Elixir.

**Key Takeaways:**

- Attendees will learn how to build RAG (Retrieval Augmented Generation) systems entirely in Elixir without relying on external Python services or paid embedding APIs.

- They'll understand how to run embedding models locally using Nx/Bumblebee, implement efficient document chunking, perform vector similarity search with pgvector, and evaluate retrieval quality.

- They'll also learn how to build agentic RAG pipelines that go beyond basic search—with query expansion, re-ranking, and self-correcting answers—using Elixir behaviours to create pluggable, composable components.

- Most importantly, they'll see how Elixir's ecosystem is now mature enough for production AI workloads.

**Target Audience:**

- Elixir developers interested in AI/ML, teams building applications that need semantic search or knowledge retrieval, Phoenix developers wanting to add AI capabilities without leaving the BEAM ecosystem, and anyone curious about RAG architecture patterns.
