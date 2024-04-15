---
level:
- Introductory and overview
tags:
- Ash
- Domain Modeling
- Composition
audience: "- Software developers of all levels"
format: In-person
title: "Ash: The Story of a Function"
speakers:
- _participants/zach-daniel.md
key_takeaways: " - Some common problems folks face when building applications with functions\n
- How Ash can help solve those problems\n
- What’s new with Ash"

---
Imperative code imposes artificial constraints. Once you see this in action, you can't unsee it. This is one of the fundamental ideas behind Ash Framework.

In this talk, we explore how a function evolves over time, and the kinds of issues that you face as you add behavior to your applications. In Phoenix, this most commonly presents as writing "contexts", which contain the functions required for building your application and business logic. Ultimately, Phoenix contexts do not have opinions on how you structure your application, instead delegating responsibility for designing and organizing your application to the developer.

This is where Ash comes in. Ash provides the structures for building, organizing and evolving your application over time to avoid the common pitfalls faced by developers every day. In this way, Ash acts as the missing domain layer for your Phoenix application (or any application). We'll go over these structures and how they address the issues inherent in composing applications out of imperative code.

Finally, we'll end with an update on the status of the project, what's new and what's coming. We've got lots in store, and can't wait for everyone to see it!
