---
level:
- Intermediate
tags:
- Foundational
- Phoenix
- Fun
title: Phoenix Beyond Cowboy
speakers:
- _participants/mat-trudel.md

---
As part of the 1.7 release, Phoenix gained full support for web servers other than Cowboy, including complete support for WebSockets, Channels and LiveView. Phoenix has gone from being fundamentally tied to Cowboy to being a fully standalone, entirely Plug-powered project. Accomplishing this required extensive refactoring of much of the foundational code within the project, which in addition to supporting webservers such as Bandit, also unlocks a number of exciting new potential features with the Phoenix router.

This talk will go into the details of what’s now possible in 1.7, what changes were needed to make this possible, and what’s in store for the future. Along the way we’ll also dive into a few related topics:

* What _is_ a WebSocket anyway?
* Introducing WebSock: a Plug-like API for WebSockets
* How a request makes its way into & through Phoenix
* Cool Phoenix.Router tricks
* Strategies for tackling large-scale changes in popular Open Source projects

Talk objectives:

* Inform people about the changes in Phoenix, Plug & WebSock, and why they should care
* Demystify the inner workings of Phoenix Endpoints and Routers, so that people can understand how their requests are served
* Advocate for lower-level libraries such as Plug, WebSock & Bandit to get more people contributing to them

Target audience:

* Phoenix users of all persuasions