---
tags:
- Code Generation
- DX
- AST
level: Intermediate
title: "The Next Dimension of Developer Experience"
speakers:
- _participants/zach-daniel.md

---
Igniter is a project patching and code generation framework for Elixir.

By leveraging AST-based code patching, library authors can provide intelligent installer and upgraders, massively improving the developer experience for getting started with a new Elixir tool. It also standardizes the process of installing and upgrading elixir packages, massively reducing the cognitive overhead of setting up new applications or installing new packages.

Want to set up a new package? mix igniter.install.
Want to upgrade a package and apply any changes suggested by the package authors? mix igniter.upgrade..

We start by exploring the unique capabilities Igniter offers to library and application authors today. After walking through examples, from straightforward to advanced, we’ll discuss how Igniter and similar tools elevate the developer experience. Finally, we’ll map out the exciting future of Igniter and its potential to transform the way we work with our Elixir applications every day.

**Key Takeaways:**
- See the cutting edge in code generation and project patching
- How library authors can implement igniter installers, upgraders and tasks in their own projects
- The utility of igniter for improving the everyday experience of working with Elixir

**Target Audience:**
Any Elixir developer, or library author.
