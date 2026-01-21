---
tags:
  - liveview
  - state
  - resilience

level: Intermediate
title: "Exploring State Management in Phoenix LiveView"
speakers:
  - _participants/krzysztof-nalepa.md

---
State management in Phoenix LiveView becomes increasingly challenging as applications grow in size and complexity. Some of these challenges are recurring ones familiar from other frontend libraries such as React, where developers often deal with shared state, prop drilling, and synchronizing data across components. Others are unique to LiveView’s server-driven model, including maintaining consistent state across nested LiveViews, coordinating updates, and dealing with state loss during disconnects or deployments.

In this talk, we will explore how these problems are currently addressed within the LiveView ecosystem, examining the tools, patterns, and workarounds developers rely on today. We will also look at how other frontend libraries approach similar challenges and identify which ideas can or cannot be translated into LiveView’s architecture. Finally, we will combine insights from both worlds to outline what simple, predictable, and resilient state management in LiveView could look like.

**Key Takeaways:**

- Attendees will:
- Gain insight into the core state management challenges in LiveView
- Learn how LiveView’s current tools and patterns address these challenges
- See which state management ideas from other frontend libraries can meaningfully inform LiveView development
- Gain a clearer picture of what a simple and resilient approach to LiveView state management could look like

**Target Audience:**

- This talk is for Elixir developers who:
- Build or maintain Phoenix LiveView applications
- Face challenges with managing LiveView state
- Want practical guidance and architectural insights into managing state more effectively in LiveView
