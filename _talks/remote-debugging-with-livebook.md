---
level:
- Intermediate
tags:
- Livebook
- Remote
- Debugging
title: Remote Debugging with Livebook
speakers:
- _participants/luca-dei-zotti.md

---
Livebook is useful for a wide range of applications. The BEAM ships with a lot of playful goodies for managing distribution but also for manipulating the software itself. Sometimes happens that you have partial access to the software that is running on some premise and partial power over the release lifecycle of the software itself. Still, you need to understand what's going on there, possibly without disrupting the entire system. Who you gonna call?
In this session I'll show, with an example application, how I managed to debug a remote Elixir instance using Livebook, some smartcells and the BEAM's love for developers.

**Talk objectives:**	
* Basic understanding of OTP distribution
* Basic understanding of module reloading
* Livebook+Smartcells for debugging purposes
* eprof, Flamegraphs and other debugging tools

**Target audience:**	
* Company Developers and individual contributors that want a grasp of how easy can be to debug a live instance with limited access using "visual" tools, not only the console