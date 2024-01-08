---
level:
- Intermediate
tags:
- Upgrade code quality
audience: "- Engineers in team/technical leadership positions, but really anybody with a interest in improving code quality and enforcing best practices over time."
format: Virtual
title: "More Practical Applications of Credo"
speakers:
- _participants/matthew-whitworth.md
key_takeaways: " - Inspired and encouraged to write more linter rules to improve the Elixir community's code quality in general, introducing code quality and idiomatic Elixir as a key priority for the community."

---
The base rules of Credo cover most areas, but how can we take lessons and ideas from other linters and code quality processes from elsewhere and apply them to Elixir to fill those gaps?

This talk is primarily an overview and analysis of the current state of Elixir's linting versus other languages (functional and non-functional), and typical issues seen in a production codebase but not yet caught by linters, finishing with some suggestions (recommendations?) to the community to where code quality processes (including Credo) could go next.

Sections would include:
- a brief exploration of the capabilities of existing linters in other languages
- principles in Elixir that could be enforced by rules currently missing
- analysis of how rules are currently contributed to the community (from where? how often?)
- where do we go next? How do we address what's missing?