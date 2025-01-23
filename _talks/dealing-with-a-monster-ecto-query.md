---
tags: database, concurrency, optimization
level: Introductory and overview
title: "Dealing With a Monster Ecto Query"
speakers:
- _participants/mackenzie-morgan.md

---
Once upon a time, there was a gnarly query with a lot of OR cases. It was limiting capacity ahead of a high-traffic day. Could it be optimized? Thanks to a few features of Elixir, the answer was yes! Here’s how the Axios mobile app’s capacity increased 600% the day before the 2020 election, in defiance of the standard "push as much processing to the database as possible" advice.

**Key Takeaways:**
- Sometimes the "usual advice" doesn't fit

**Target Audience:**
- Anyone who deals with databases
