---
tags:
  - microcontrollers--nerves-embedded

level: Intermediate
title: "Testing Concurrency and Fault Tolerance in Elixir/Nerves on a Real-World Audiovisual Sensor Network"
speakers:
  - _participants/marta-habdas.md

---
In my talk, I want to present how Elixir/Nerves performs in a real-world audiovisual sensor network. Using a large number of sensors - some interactive with user input, others environmental - and processing unreliable data can be very challenging, especially for long-running, unattended systems. Sensors can malfunction, and hardware components can fail. As Elixir comes with mechanisms like lightweight processes and isolation, which ensure fault tolerance, it could be a perfect choice in such cases.

As such systems aren’t easy to simulate, I plan to build a real prototype with physical sensors based on an architecture that combines Arduinos (as sensor controllers), Raspberry Pi (as the backbone of the project running Nerves/Elixir for event processing), and an audiovisual output layer. That allows testing the real system’s behaviour under sensor failures, process crashes, and unreliable data. The audiovisual nature of the project provides immediate visibility into the system in real-time. Thus, I’ll present the system during the talk with controlled audience interaction.

**Key Takeaways:**

- How to design fault-tolerant, concurrent systems for unreliable hardware and sensor input
- Practical patterns for using Elixir/Nerves in long-running, unattended microcontroller-based systems
- Strategies for handling noisy data, partial failures, and process crashes in real-world environments

**Target Audience:**

- Elixir developers with basic knowledge of the language
- Engineers interested in Nerves and embedded systems
- Developers working with hardware, sensors, or unreliable data sources
- Artists and creative technologists working with interactive or sensor-based systems
