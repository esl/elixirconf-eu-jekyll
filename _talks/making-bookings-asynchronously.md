---
tags:
- Elixir asynchronous services
level: Intermediate
title: "Making Bookings Asynchronously"
speakers:
- _participants/fernando-hamasaki-de-amorim.md

---
Let’s dive into the evolution of an Elixir backend application responsible for hotel online reservations.

This application started small as a minimum viable product (MVP) implementing a synchronous booking flow in the beginning. As the application and the product were growing, also some problems and limitations were faced, incremental steps were taken to improve the booking flow, initially with a simple asynchronous approach using Elixir built-in capabilities, until reaching an event-driven architecture to execute the different processes of the booking flow in a distributed way.

The final result made the entire booking process more reliable, increased the performance of the application, mitigated some issues and improved the customers’ experience.

**Key Takeaways:**

The booking flow used in Vio.com to make online hotel reservations consists of many steps, integrating with several internal and external applications, like hotel providers, payment service providers, fraud protection service and tracking systems. Those steps when executed synchronously and sequentially can have problems in performance, request time, reliability and poor user experience.
For a MVP version a synchronously booking flow was enough. However, as the product grew up, more features were required and the volume of traffic increased, new technical solutions were necessary to meet new requirements.

It will present the evolution of this application, the challenges faced and the technical solutions applied in an incremental way to reach the current state of the application architecture using an event-driven approach.

Some technologies to be mentioned during the presentation:
- Elixir processes
- Tricks using Cowboy
- AWS services: EventBridge, SQS, Scheduler
- Broadway


**Target Audience:**
- Backend Elixir engineers.
