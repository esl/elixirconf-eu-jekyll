---
tags:
  - elixir-ai-agents

level: Intermediate
title: "Legion: Agentic Code Execution with Pure Elixir"
speakers:
  - _participants/dima-mikielewicz.md

---
Most AI agents are trapped in a "chat-and-call" loop, restricted by rigid function-calling interfaces. Legion breaks this cycle. It introduces a paradigm where agents don’t just request actions - they execute them. By allowing LLMs to run vetted Elixir code in isolated sandboxes, Legion enables agents to spawn other agents, exchange messages, and react to events in real-time. There is no new DSL or steep learning curve, Legion turns your pure modules and functions into an autonomous toolbox. You write the limbs - Legion provides the nervous system to orchestrate them.

https://github.com/dimamik/legion

**Key Takeaways:**

- Beyond RPC: Why executing full code snippets creates faster, more capable and efficient agents than single-action function calls.

- Authorization: Why Vault (https://github.com/dimamik/vault) is the most robust way to authorize tool calls at scale.

- The Elixir Advantage: Why the BEAM's isolation and supervision are uniquely suited for autonomous AI systems.

**Target Audience:**

- This talk is for everybody interested in AI Agents, whether with or without prior Elixir experience.
