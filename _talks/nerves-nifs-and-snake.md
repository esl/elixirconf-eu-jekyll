---
tags:
  - nerves
  - hardware
  - e-ink

level: Intermediate
title: "Nerves, NIFs, and Snake"
speakers:
  - _participants/gus-workman.md
published: true

---

This talk will walk you through the process I went through of bringing Nerves support to a custom e-ink device. The story walks through the last year or so of development of this project, including a look at how a LiveView-like model for representing stateful systems can be applied to hardware and e-ink displays.

Several NIF libraries were developed for this project. I'll discuss some of the reasons for using NIFs and tips for getting Rustler to play nice with Nerves.

Finally, I'll show you my version of e-ink snake, and we'll talk how you can get started building your own e-ink apps using the open source hardware designed for this project.

**Key Takeaways:**

- This talk will cover the architecture of a Nerves app in production, as well as some of the tips and tricks for Nerves development.

**Target Audience:**

- Not a hardware expert? Never fear! This talk is a great introduction to Nerves for Phoenix and general Elixir developers. I hope it serves as your inspiration for all the cool things you can do with Nerves
