---
level:
- Introductory and overview
tags:
- Video
- AI
- Computer Vision
audience: "- Accelerate other people’s computer vision projects.\n
- Explain some of the pitfalls that ExNVR tries to address."
format: In-person
title: "End to End Computer Vision in Elixir: Making it work in Production"
speakers:
- _participants/walid-salah.md
key_takeaways: " - Priorities to consider when trying to solve for real world constraints.\n
- Developing for embedded devices.\n
- Computer Vision in Elixir (AI & Traditional)."

---
The task was to replace a proprietary video recording platform with an elixir based solution that had to perform in some very harsh physical environment with unreliable power and
bandwidth.
Evercam chose to implement a <a href="https://membrane.stream">membrane.stream</a>-based solution deployed using <a href="https://nerves-project.org">Nerves Project</a> and leveraging <a href="https://livebook.dev">Livebook</a> and the emerging elixir machine learning & computer vision ecosystem.
What we found was that it was relatively easy to put something together very quickly, but to actually make it work in production meant solving a lot of edge case problems.
The resulting project, Ex_NVR has been made open source and is intended to be a kickstart for successful computer vision projects deployed on the edge.