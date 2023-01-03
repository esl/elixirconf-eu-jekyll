---
level:
- Introductory and overview
tags:
- Multitenancy
- " Phoenix"
- PostgreSQL
title: Multitenant web applications with Phoenix
speakers:
- _participants/eli-kroumova.md

---
Multitenancy is a software architecture where one instance serves different clients (tenants). This definition is quite general and can be implemented in different ways.  

This talk is about the specific case of web application where each client data is stored independently in the database and served by the same application.  

Phoenix and Ecto already have all we need for the implementation. Ecto prefix option gives us access to PostgreSQL schemas for the data encapsulation and Plug provides a straithforward way to assign the current tenant.  

In this talk we will see how all the pieces fit together in a step by step example.

**Talk objectives:**
* Introduce the concept of multitenant application and show a concrete example for its implementation. The example is based on the Triplex library but the ideas it is based on are general and do not depend on the concrete library used for the implementation.

**Target audience:**
* Phoenix developers
