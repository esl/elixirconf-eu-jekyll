---
level:
- Intermediate
tags:
- maps
- proxy
- powerful
audience: "- People not knowing Elixir, because they will be able to see a wide array of different features and how Elixir/Phoenix make them much easier & scalable.\n
- People more experimented with Elixir, sharing the knowledge & pushing them a bit more forward :-)\n
- This could be made a fairly technical talk (Postgres PostGIS aggregates, Channels/Presence, proxying..), but I plan to make sure it can be understood by less advanced people."
format: Virtual
title: "Elixir at transport.data.gouv.fr (maps, proxies, and more)"
speakers:
- _participants/thibaut-barrere.md
key_takeaways: "- Sharing a long-term, product oriented real life experience.\n
- How solid Elixir is for versatile needs on a small team with large needs.\n
- Maintenance story.\n
- Full features set that can be approached with Elixir.\n
- All the problems that do not exist, compared to some other stacks."

---
I've been working on <a href="https://transport.data.gouv.fr">https://transport.data.gouv.fr</a> for more than 3 years.

The idea behind this talk is to show how versatile Elixir & the BEAM are, and how they helped us implement a wide array of interesting features more easily, at a lower ops cost too.

We have a lot of stuff going on: maps with 650k points shown, real-time maps showing vehicles with 80+ sources (channels/presence), "business reverse caching proxy" to reduce the load of 3rd party servers, XML query generators with LiveView, on-demand tooling (again using LiveView), data analysis scripts with LiveBook, etc etc.

We also have a strong maintenance process in place, and I want to share how good the maintenance story is.