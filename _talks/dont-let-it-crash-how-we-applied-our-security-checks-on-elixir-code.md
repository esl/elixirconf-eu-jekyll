---
level:
- Intermediate
tags:
- Security
- Vulnerability detection
- Static analysis methods
audience: "- Developers/project leads who care about software security."
format: Virtual
title: "Don’t let it crash - How we Applied our Security Checks on Elixir Code"
speakers:
- _participants/melinda-toth.md
- _participants/daniel-horpacsi.md
key_takeaways: " - We would like to draw your attention to the fact that security problems exist in Elixir/Erlang codes. Their detection can sometimes be done with simple tools, but in many cases, it is not trivial, and they are difficult to identify. Static analysis methods can help with this. We show problems, solution methods and a tool that can help you detect security vulnerabilities in your code."

---
Something to love about the BEAM is the principle of ‘let it crash’: exceptions are isolated and handled by design. However, it would be rash to conclude that all input validation is redundant and unnecessary. EEF curated a list of secure coding principles to help developers create secure systems on the BEAM. But the reality is always messy: Erlang/Elixir projects rarely follow these guidelines, and legacy has been running for years with well-known vulnerabilities.
We presented that static analysis can be useful for detecting critical security issues in new or legacy systems, and showed that we carried out a successful DoS attack based on a vulnerability found in a widely used Erlang software.
In this talk, we will present how we applied our static analysis framework to Elixir programs: what difficulties we encountered, and how we extended our existing tools to detect vulnerabilities in Elixir. We will show some use cases of vulnerabilities we found in open-source Elixir projects.