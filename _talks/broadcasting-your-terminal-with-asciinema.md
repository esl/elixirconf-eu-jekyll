---
tags:
  - asciinema-terminal-streaming

level: Intermediate
title: "Broadcasting Your Terminal with Asciinema"
speakers:
  - _participants/marcin-kulik.md

---
In this talk, we'll take a look under the hood of asciinema server -the server-side component of asciinema suite for recording and live-streaming terminal sessions - and see how Elixir, Phoenix, and BEAM/OTP enable many great features with minimal effort and ceremony.

We'll focus on live terminal streaming, a feature that lets you broadcast terminal sessions on the internet. From stream parsing, through integrating Rust, implementing GenServers that manage live stream state, to LiveView-powered previews (thumbnails), we'll cover the whole pipeline.

**Key Takeaways:**

- The aim is to show the audience how various features provided by Elixir language, Phoenix framework, and BEAM/OTP work well together, enabling us to build awesome software easily.

**Target Audience:**

- People interested in any of:

- real-time streaming solutions
- integration of Rust into Elixir codebases
- data serialization
- case studies
