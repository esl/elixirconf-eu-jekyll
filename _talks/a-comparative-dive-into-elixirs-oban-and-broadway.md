---
level:
- Introductory and overview
tags:
- Oban vs. Broadway
audience: "- Devs who have to synchronize data across services on a daily basis. It was requested by users on Elixir Slack #oban channel."
format: In-person
title: "A Comparative Dive into Elixir's Oban and Broadway"
speakers:
- _participants/jakub-hajto.md
key_takeaways: " - This talks aims to demystify when to use which library and to avoid getting into a dead corner, when the solution won't be able to support your product requirements."

---
Delve into the mechanics of Oban's persistent job processing, exploring how it excels in managing long-running, stateful tasks. Contrast this with Broadway's approach, designed to seamlessly handle job streams from external sources, emphasizing parallelism and scalability.

Through a technical lens, we'll explore use cases, performance considerations, and deployment strategies for both libraries. By the end of the session, you'll possess a nuanced understanding of when to leverage Oban's robust persistence and when to tap into Broadway's prowess in handling external job queues.