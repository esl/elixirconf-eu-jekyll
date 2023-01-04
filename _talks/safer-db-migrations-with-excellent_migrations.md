---
level:
- Intermediate
tags:
- Safer Database Migrations
title: Safer DB migrations with excellent_migrations
speakers:
- _participants/artur-sulej.md

---
Have you ever caused downtime of your production due to a bad migration?  
Maybe you've forgotten to add index concurrently to your huge table and locked it?

Our applications very often make use of relational databases – and from time to time we need to change their schema. These operations usually take just a few lines of code – but when not used correctly can cause a long and painful downtime of your production.

I've created an open source library excellent_migrations. It's a static analysis tool for checking safety of database migrations. It automatically detects potentially dangerous or destructive operations. The tool analyses code by traversing Abstract Syntax Tree (AST) of migration files. It also provides a mechanism to silence certain checks, when you are sure that you know what you're doing.

In my session I'll talk about unsafe operations, how excellent_migrations lib works why it's fun to do open source.

GitHub repo: https://github.com/Artur-Sulej/excellent_migrations

**Talk objectives:**

* Educate about unsafe operations in database migrations.
* Present how my open source library (excellent_migrations) solves this problem.
* Show how excellent_migrations lib works under the hood (example interesting bits: traversing and parsing AST and unusual cases for macros).
* Encourage people to create open source in general.

**Target audience:**

* You’ll get the most out of this session, if your Elixir application uses relational database.