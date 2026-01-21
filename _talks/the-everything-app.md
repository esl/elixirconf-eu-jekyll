---
tags:
  - edge-streaming-inference

level: Intermediate
title: "The Everything App"
speakers:
  - _participants/lars-wikman.md

---
Phoenix, LiveView, Membrane, Nerves and Nx. This talk shows a production app that exercises a large amount of the Elixir ecosystem. ExNVR by Evercam is a networked video recorder and an open source project. It streams video from multiple IP cameras to store on disk. We will grab frames from the stream to perform inference. We'll display UI to the user. And we will do it on affordable embedded hardware at respectable speeds.

And we'll learn some things along the way.

ExNVR runs on at least a thousand devices world-wide as part of Evercam.

**Key Takeaways:**

- Experience a production application combining large swathes of the ecosystem to do in-depth work. This is a very good example application that goes way beyond your basic sample app.

- For the tinkerer, you'll be able to hack this system to your needs and will.

- For the web dev, not everything runs on a cloud server. Here is something to sink your teeth into.

- For the aspiring embedded dev, this is a real usage of Nerves that you can put to use.

- For the person looking for challenges, Membrane is awesome and media is hard. There are tons of things to improve, experiment with and explore.

- My desire is that the listener sees the way a full Elixir app is such a neat pluggable set of parts. How the various part make a more compelling whole and how the resiliency of the platform manages the risks of doing everything on a single device.

**Target Audience:**

- Any Elixir developer and probably some others.
