---
level:
- Intermediate
tags:
- testing
- OTP
- wtf
audience: "- Experienced Elixir developers who care about testing and anyone who has graduated from 'just using Phoenix' and started looking into some more interesting patterns the ecosystem gives you."
format: Virtual
title: "Testing OTP"
speakers:
- _participants/aaron-cruz.md
key_takeaways: " - Testing Processes is hard. Sometimes incredibly hard. I would like for people to walk away from this talk with more confidence in their testing of the more difficult to test parts of their Elixir systems."

---
For the last two years, I've been working with one of the larger energy companies in Germany. As more renewable energy becomes available and the energy topology grows, it becomes harder to track in the enormous energy network where there might be too much or too little energy flowing. We are building an Elixir system to find these problem spots and stop them before they happen.

We've been able to work inside a monorepo for years because OTP features have made it incredibly simple to model our complex infrastructure in Supervision Trees and Processes.

Testing has been, hands down, the most complex part of using Processes and OTP in Elixir. Whether it's a polling server, an in-memory repo, or trying to do mocks the right way, there are many gotchas and head-scratchers along the way.

If you've ever tried to test anything Process-related and scratched your head thinking "WAT?", you will find your answers in this talk.