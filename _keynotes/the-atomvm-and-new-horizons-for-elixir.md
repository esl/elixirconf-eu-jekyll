---
tags: 
- AtomVM
- BEAM
- Platforms
title: "The AtomVM and New Horizons for Elixir"
speakers:
- _participants/mateusz-front.md
- _participants/davide-bettio.md
published: false
level: Everyone

---
Elixir owes a lot to the BEAM Virtual Machine. Thanks to its capabilities and guarantees, we can do everything from web development to AI and media streaming, in a concurrent and fault-tolerant way. However, certain environments with limited resources or different constraints, such as microcontrollers, are not suitable for the BEAM. Does it mean we should abandon the idea of using Elixir in these environments? Not anymore. We have AtomVM - an alternative implementation of the BEAM - designed specifically to run on microcontrollers!

That proves an important point: we can run Elixir in different runtimes with different design choices and tradeoffs! That opens up whole new possibilities as we can make Elixir even more versatile than it is today.

With that in mind, a small team at Software Mansion paired with the Atom VM team to run Elixir on a whole new platform. To do so, we needed a deep understanding of the AtomVM internals and augment its feature parity with the BEAM. What have we come up with? We can't wait to share the results with you, and they're very promising!

**Key Takeaways:**
- Learn what AtomVM is and how it differs from the BEAM
- Learn the basics of how Elixir runtimes work
- Learn about previous attempts to run Elixir on different platforms
- Learn how AtomVM makes Elixir more versatile and how you can help

**Read the blog post about Popcorn - Bringing Elixir to the Browser [here](https://blog.swmansion.com/popcorn-bringing-elixir-to-the-browser-8993a58a00be)**
