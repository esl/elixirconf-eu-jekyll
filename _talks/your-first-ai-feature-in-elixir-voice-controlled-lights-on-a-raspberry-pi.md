---
tags:
  - real-world-ai-elixir

level: Intermediate
title: "Your First AI Feature in Elixir: Voice-Controlled Lights on a Raspberry Pi"
speakers:
  - _participants/misael-perez-chamorro.md

---
AI is showing up in everything lately, and as an Elixir engineer it’s not always obvious where to start without falling into the usual toy demos (Is this a banana?). In this talk I’ll share a real app that runs fully locally on a Raspberry Pi: a voice-controlled smart-light system where Elixir owns the whole stack.
We’ll walk through the architecture from end to end. You’ll see how Membrane captures and chunks audio, how a Phoenix LiveView dashboard makes the system easy to observe and tweak, and where Nx/Axon fits when you want small, practical models like wake-word detection and intent classification. I’ll keep it grounded in the “how”: turning a rough prototype into something usable, collecting just enough data to train a first model, and wiring the pieces together so the result feels like a real feature, not a science project.
By the end, you’ll have a clear picture of where Elixir fits in AI/ML today, plus a working smart control device in your house powered by Elixir that you can keep extending as you learn.

**Key Takeaways:**

- Tools to start with: Membrane (audio), Nx/Axon (ML), LiveView (fast UI + feedback).
- A simple learning path: collect a small dataset, train a tiny model, plug it into your app, iterate
- Where Elixir fits: owning the full stack around ML and running practical AI features locally.

**Target Audience:**

- Elixir devs who can build apps today and want a practical on-ramp to adding ML/AI features (locally, on small hardware) without needing deep ML background.
