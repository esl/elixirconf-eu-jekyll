---
level:
- Intermediate
tags:
- Gaming
- Backend
- Message passing
audience: "- Elixir developers\n
- Game developers\n
- Aspiring game developers"
format: In-person
title: "Lambda - An Open Source Backend for Videogames built in Elixir"
speakers:
- _participants/manuel-camejo.md
- _participants/federico-carrone.md
key_takeaways: " - How to handle communication across a large number of clients.\n
- How to handle state so that there’s a single source of truth to prevent cheating."

---
LambdaClass is building a scalable, fault-tolerant open source game backend using Elixir and Rust. With over a decade of experience building backend systems, we set out to compete in the gaming market. We hoped there would be a cost-efficient and reliable backend solution available to build upon, but after a quick glance at the market, we knew we had to build our own. Although we still have ways to go, we have a working solution that we’re already building games upon. And to help others on the same journey, we decided to not only open-source the backend but all of the game code and game assets, from 3D models to music.
The particular challenge we had to solve was building a solution where a centralized server, which holds the source of truth for the game state, exchanges messages with a large amount of clients, and updates its state in real time. We’ll go through our many iterations, explain our decision-making process and show how our game improved as its backend matured.