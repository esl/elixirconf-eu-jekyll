---
tags:
  - liveview
  - local-first
  - popcorn

level: Introductory and overview
title: "Let’s Cut the Cord: Bringing LiveView to the Client with Popcorn"
speakers:
  - _participants/mateusz-front.md

---
Phoenix LiveView revolutionized web development by moving state to the server, allowing developers to build rich, interactive experiences without the overhead of complex JavaScript frameworks. But this power comes with a physical constraint: the round-trip time to the server. For high-interactivity features or users on high-latency connections, it can still be a barrier to a truly "instant" feel.

In this talk, we explore a new frontier for the Elixir ecosystem: running LiveView natively in the browser. Local LiveView preserves the programming model we love — functional components, stateful processes, and HEEx templates — but executes them on the client side. By removing the requirement to reach the server for every event, we can achieve sub-millisecond latency and offline capabilities while staying within the Elixir paradigm.

**Key Takeaways:**

- In this session, I will cover:
- Architecture of Local LiveView
- Bridging Local LiveView and server-side LiveView
- Examples & use cases
- The state of Popcorn & what's next

**Target Audience:**

- LiveView users, web programmers
