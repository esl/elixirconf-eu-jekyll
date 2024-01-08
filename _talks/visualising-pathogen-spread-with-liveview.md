---
level:
- Introductory and overview
tags:
- Iterative LiveView Design
audience: "- Teams looking for a design and data-centric perspective on what might work (and not work) introducing Elixir to their practice \n
- Designers and developers who are looking for new ways to find stories in data, and unique tools for interacting with and exploring data \n
- People with scientific or educational backgrounds, curious about using Elixir to build learning tools"
format: In-person
title: "Visualising Pathogen Spread with LiveView"
speakers:
- _participants/kyle-oba.md
key_takeaways: " - LiveView can play an integral role in the iterative design process required to explore and represent complex data. \n
- Phoenix’s abstractions over real-time messaging are a unique toolset, allowing you to explore exciting new ideas. \n
- Elixir’s many strengths allow you some flexibility when introducing it to your team. It improved our APIs performance, allowing us to support larger simulations. Also, Phoenix makes developing new LiveViews very easy, maintaining momentum during the iterative design process."

---
Operation Outbreak is a game designed for students, simulating the spread of a virus using mobile Bluetooth. In simulation, students become "infected", display symptoms, infect others, acquire protection, and may recover.

With Phoenix we allow students to collaborate during the simulation, and collect and visualize simulated viral outbreak data. Students analyze the data from their viral outbreaks, learning how viruses spread, and how their actions play a part in the spread or containment of pathogens.

In this talk you’ll learn about the role LiveView played in the iterative design process required to build highly customized tools for understanding complex data.

LiveView's abstractions over messaging enable rapid prototyping of new, previously inaccessible, ideas. I’ll share our project in support of Operation Outbreak and the Sabeti Lab, including how I introduced Elixir to the design team at Fathom Information Design and improved performance to support larger simulations.
