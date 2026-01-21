---
tags:
  - liveview
  - extended-markdown
  - genui

level: Intermediate
title: "Deterministic LLM UI Rendering in Phoenix LiveView"
speakers:
  - _participants/anthony-leiro.md

---
LLMs are excellent at text and unreliable at UI. This session shows how to extend Markdown into a deterministic UI contract in Phoenix LiveView by introducing custom blocks that represent interactive components not found in standard Markdown (suggestions, insight cards, charts). We’ll stream tokens (SSE), incrementally parse and validate blocks as they arrive, and render only a set of these custom components the moment each block becomes complete—progressively upgrading from plain Markdown to interactivity without flicker.

**Key Takeaways:**

- A concrete “UI contract” pattern: constrained Markdown

- Streaming + incremental parsing in LiveView without full reparses or duplicated UI

- Safe interactive rendering via extended Markdown renderers and strict Hooks/JS boundaries

**Target Audience:**

- Phoenix/LiveView engineers building AI-assisted features, platform teams exposing streaming endpoints, and anyone turning LLM output into maintainable UI instead of best-effort Markdown. LiveView basics assumed; streaming/OTP experience helps.
