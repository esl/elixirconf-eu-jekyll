---
tags:
- Mix Vue & LiveView
level: Intermediate
title: "Why Combining LiveView and a Frontend Library Is a Great Idea"
speakers:
- _participants/jakub-skalecki.md

---
LiveView revolutionized web development by enabling server-rendered, dynamic UI. Just, as our applications grow in complexity, we often find ourselves needing more sophisticated client-side interactions. While LiveView excels at server-driven UI, managing complex client-side state can become challenging.

This talk explores how integrating a frontend library with LiveView offers the best of both worlds: LiveView's powerful server-side model combined with the rich ecosystem of modern frontend frameworks. Using LiveVue as a case study, we'll demonstrate practical patterns for managing client-state, leveraging existing frontend components, and maintaining a clean architecture. You'll learn when and how to introduce a frontend library to complement LiveView, not replace it.

**Key Takeaways:**

Attendees will:
- Learn to identify when introducing a frontend library alongside LiveView makes sense
- Understand patterns for cleanly separating server and client-side concerns
- See practical examples of integrating Vue.js with LiveView using LiveVue
- Gain insights into architectural decisions when mixing frameworks
- What are the treade-offs of that approach
- Take away practical strategies for gradually introducing frontend libraries into existing LiveView applications

**Target Audience:**

This talk is aimed at Elixir developers who:
- Have experience with Phoenix LiveView
- Are facing challenges with increasingly complex client-side interactions
- Want to understand how to effectively combine server and client-side frameworks
- Are interested in modernizing their LiveView applications while maintaining their existing investment
- Have team members with Vue.js (or other frontend framework) experience
