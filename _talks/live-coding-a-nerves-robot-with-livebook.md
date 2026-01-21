---
tags:
  - nerves-self-balancing-robot

level: Introductory and overview
title: "Live Coding a Nerves Robot with LiveBook"
speakers:
  - _participants/dennis-palmer.md

---
Several years ago, Dennis started reading the book "Arduino Robot Bonanza" by Gordon McComb. He had assumed that an Arduino was required to build robots like those described in the book, but has since discovered that a Raspberry Pi running Elixir via Nerves, along with Hex packages like Circuits.I2C could do much, if not all, the same things.

Inspired by the Teachbot platform described by McComb, he designed and 3D printed Wobbles, a self-balancing 2-wheel robot powered by Nerves and programmed via Livebook.

In this session, we will see a hands-on demo of using binary pattern matching in a GenServer to read the gyro/accelerometer data via I2C and control the motors to make Wobbles a little less wobbly. Then we'll walk through how to use an ultrasonic distance sensor to help prevent collisions when he starts to move.

**Key Takeaways:**

- Attendees will be inspired by the simplicity of using an Elixir GenServer to combine reading sensors and controlling motors in a robot platform designed for learning and experimentation.

**Target Audience:**

- Elixis enthusiasts of all levels who want to try building their own robots or just see what's possible.
