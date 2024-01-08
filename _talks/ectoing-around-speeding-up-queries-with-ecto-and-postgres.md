---
level:
- Intermediate
tags:
- Ecto
- Postgres
- Queries
audience: "- Backend Engineers who use queries and Ecto extensively already but are interested in not only making the queries return the desired data but also being performant in high-demand applications. In other words, people who are familiar with both Ecto and SQL but might not have dived deeper into performance optimizations."
format: In-person
title: "Ectoing around: Speeding up queries with Ecto and Postgres"
speakers:
- _participants/filipe-froes.md
key_takeaways: " - How ecto is only a thin layer to interface with the database\n
- Writing queries in ecto is pretty much writing SQL thus Ecto optimisation/bottlenecks tend to be SQL optimisation/bottlenecks as well\n
- How to use Postgre's 'explain analyze' and what to look for in the query plan\n
- How Postgres indexes work and doing lookups and what to keep in mind when creating your indexes (Focus on B-tree indexes)\n
- Some different features of indexes like partial indexes, indexes with 'includes', etc.
- Caveats when creating indexes using 'ecto.migrate'\n
- When to use lateral joins in Postgres and how to use it with Ecto\n
- Other common ecto-specific performance penalties you might fell into if you're not careful using Ecto"

---
A deep-dive into some of the Postgres internals and features focusing on speeding up queries. Using Ecto for practical examples and other visualizations, the aim is to provide a clear understanding of how to analyze, identify issues and finally optimize your queries. We'll also dabble into the details of how indexes lookups, lateral joins and other features of Postgres work to help fixate the knowledge.
