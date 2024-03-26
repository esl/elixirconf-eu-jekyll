---
level:
- Intermediate
tags:
- Nerves
- automotive
- reverse
audience: "- This talk aims to inspire beginners to try out new and crazy ideas and applications of Elixir in the real world, and at the same time should also appeal to more intermediate and advanced practitioners"
format: in-person
title: "Retrofitting a Car and Running it with Elixir"
speakers:
- _participants/marc-lainez.md
- _participants/thibault-poncelet.md
key_takeaways: " - How real-life automotive computing works in practice\n
- Advantages and limitations of using elixir and nerves in an automotive context\n
- Struggles in creating an efficient on-site and remote team workflow when working with a physical product sending messages (an actual car sitting in a garage)"

---
Extending a cars' lifespan is not an easy feat. We need to ask ourselves what makes people enjoy a car today and what technology it should include. This talk shares the current state of our journey in retrofitting a car and building a new and open vehicle control system (OVCS), redesigning the engine controller and infotainment systems with off the shelve components running with Elixir.

We will explain how we reverse-engineered the proprietary CAN bus messages from the car, how we created our own raspberry pi CAN bus hats and how we used nerves to create firmware for the new electric engine controller and infotainment systems.