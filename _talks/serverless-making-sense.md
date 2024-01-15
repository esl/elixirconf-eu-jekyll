---
level:
- Advanced
tags:
- Server-less making sense
audience: "- Platform architects, senior engineers, platform service offerings"
format: In-person
title: "Server-less Making Sense"
speakers:
- _participants/markus-kuhnt.md
- _participants/alexey-nikitin.md
key_takeaways: " - Elixir and the BEAM in particular provide an excellent toolbox to provide scalable and powerful platforms.\n
- With our approach of securely executing custom code, we have proposed a way to extend these platforms in a customer-specific way.\n
- This keeps the powerful core system of the platform as well as the custom extensions in the same system context and avoids unnecessary complication of the usual server-less infrastructures."

---
Server-less has become mainstream, and all relevant cloud platforms offer corresponding runtime environments. Elixir or Erlang can only be used in a roundabout way or lose their charm because they require their own platform.

Starfish.team provides a payment processing platform called Hellgate. Our service can be complemented with extension points to map customer-specific use cases. We have provided server-less / function as a service as an ideal starting point for these extensions.

In this talk, we present an approach for executing customised extensions on the same runtime as our core system. This requires elementary security mechanisms, which we achieve by analysing the code of the functions. In contrast to conventional white listing approaches, we can execute much more specific code (in the sense of a DSL) and prevent malicious calls.
