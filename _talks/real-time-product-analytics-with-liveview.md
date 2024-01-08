---
level:
- Intermediate
tags:
- Product
- Analytics
- LiveView
title: Real-time Product Analytics with LiveView
speakers:
-

---
LiveView brought a new paradigm for building real-time web applications, relying on one of the most appreciated feature of Elixir: its runtime, the BEAM. In particular, its observability features are appreciated, mostly for debugging purposes like being able to inspect the system behavior, live, in production.

In this talk, I want to show how those tools can also be used to build better products, enabling real-time analytics & direct feedbacks with users. LiveView now enables the builder to interact with its users, live, while they are using the product.

We will see how to build an internal administration interface, where the builder can interact real-time with users. For example, see which user is online (by listing root LiveViews processes), what are their interactions with the product (through the socket assigns) or how to push them live messages (through @flash messages) or one-off polls regarding their usage of the product or the next feature they want to see built.

**Talk objectives:**	
* The goal is to start a conversation in the community about how we can push the unique abilities of LiveView outside the pure technical standpoint, in the product space. In my humble opinion, I think LiveView adoption could benefit from being seen not only as a technical shift, but also as a new way to build products.

**Target audience:**
* This talk is aimed at Software Engineers with a Product mindset, who want to build the best product for their users. Especially, those who might want to introduce LiveView in their stack but need to convince tech & product management in their company.