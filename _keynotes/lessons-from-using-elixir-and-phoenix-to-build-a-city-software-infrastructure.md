---
level:
- all
tags: []
title: Lessons From Using Elixir And Phoenix To Build A City Software Infrastructure
speakers:
- _participants/shankar-dhanasekaran.md

---
I've been involved, for the past 12 years as the chief software architect, in developing the software infrastructure for the city of Auroville, a futuristic city of 50K population with people from all over the world, working and living in harmony for Human Unity. ([https://auroville.org/page/vision-of-the-city](https://auroville.org/page/vision-of-the-city "https://auroville.org/page/vision-of-the-city")). Today the life of every citizen in Auroville, whether they buy a coffee in a restaurant or submit a visa application to stay in Auroville, their interactions are powered by Elixir and Phoenix in the background.

As someone who has been instrumental in moving the majority of the software tools used by the city to Elixir and Phoenix in the last 6 years, this talk will start with presenting a big picture of all the apps used in Auroville that are powered by Elixir/Phoenix and present various lessons learned in the process.

**Keynote objectives:**	
To help developers make design choices in a very complex multi-service business domain in an agile way that doesn't introduce complexity unnecessarily while being flexible enough to change as requirements and conditions change in the business.

In this talk, I will share

1. why we moved to Elixir
2. what were the pitfalls during our migration,
3. what are the advantages we see in this migration
4. What are the analysis paralysis we faced in deciding the architecture of the city infrastructure such as microservices vs monoliths vs umbrella apps
5. Why and how are we training people in Elixir when the talent pool with Elixir skill is low in India?
6. How we are increasing our productivity by moving to Phoenix LiveView for all our new applications
7. why we are betting our next 10 years with Elixir and Phoenix by citing the specific features in the language and framework.

I will share how we use our own version of [Citadel pattern](https://m.signalvnoise.com/the-majestic-monolith-can-become-the-citadel/) using Phoenix Umbrella apps interacting with other services within the umbrella and as well as with external services built in Elixir and in other languages.

This keynote will appeal to software engineers and architects who:  
1\. find themselves split between microservices vs monolith vs Phoenix Umbrella and want to get new perspectives that will help them choose one or more of them for different scenarios.  
2\. want to learn from the experience of an organisation that has tried multiple patterns through trial and error for solving different business needs.  
3\. want to see real-world application of LiveView and Phoenix API powering financial products.