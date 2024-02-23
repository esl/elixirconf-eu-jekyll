---
level:
- Intermediate
tags:
- Shrinking that works
audience: "- Intermediate Elixir developers who have considered property-based testing. Especially if they have abandoned using it because shrinking did not work as expected."
format: In-person
title: "The Magic of Internal Shrinking for Property Based Testing"
speakers:
- _participants/dennis-palmer.md
key_takeaways: " - The audience will gain familiarity with the limits of traditional shrinking mechanisms and learn the advantages of internal shrinking."

---
Shrinking is the real magic of property-based testing — producing a small, human-readable test case whenever a larger random case causes a test to fail. However, it can be hard to do correctly.

Traditional approaches to shrinking require the shrinking logic to know specific details about the data type being simplified. When generated values are passed through a mapping function or combined in certain ways, it can break a shrinker written with the generated data type in mind.

Internal shrinking is based on the idea that shrinking inputs produces simplified outputs. When the underlying source of randomness is reduced it causes the generators to produce simplified test cases automatically. The final reduced test case is constructed as if the generator had been lucky and produced a small, readable test case by chance.

We will explore the Decorum library, an Elixir property-based testing library with shrinking that just works.
