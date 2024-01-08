---
level:
- Intermediate
tags:
- Explorer data patterns
audience: "- Anyone who isn't entirely sure what a dataframe is or why they might use one. And anyone who uses them but thinks they're only for data science task. And anybody else, really."
format: In-person
title: "Dataframes are not just for Data Scientists"
speakers:
- _participants/christopher-grainger.md
key_takeaways: " - Dataframes are often relegated to the realm of 'data science', but they're actually a really useful tool for everyday programming tasks. They uncover novel and performant patterns in all sorts of applications and should be part of any developer's toolkit."

---
A dataframe is a tabular, two-dimensional data structure, like an in-memory database table. You might think of them as the weird spreadsheet-like thing that your data scientist colleague gets all excited about.

This talk is about why dataframes are exciting for anybody who works with any kind of data in Elixir, and how you can add them to your developer toolkit. With the Explorer library, we have access to extremely fast dataframes and series (one dimensional, like a list) in Elixir.

We'll cover how to translate common Elixir approaches to data manipulation to composable dataframe operations, how and when you can get a performance boost, and how dataframes can save you round trips to the database or sending heavy payloads to your client.