---
level:
- Intermediate
tags:
- LiveView
- Diff-Tracking
- Components
title: Optimizing LiveView for Real-Time Applications
speakers:
- _participants/marlus-saraiva.md

---
Phoenix LiveView has a well-deserved reputation for being highly efficient regarding server/client payload exchange and resource consumption. Most of that efficiency relies on keeping track of templates' diffs and components' assigns changes. For most common applications, developers usually don't need to worry about such implementation details. However, when working with real-time applications that demand highly frequent updates, a deeper knowledge on the subject may be the key to avoid performance issues in production. In this talk, we'll discuss the basic concepts behind Liveview's diff tracking and component change tracking, as well as present several techniques that explore those concepts to improve the overall performance of your live views.

**Talk objectives:**	
* Present techniques that explore Liveview's diff tracking and component change tracking to allow developers to improve the performance of their real-time applications.

**Target audience:**
* Anyone working with LiveView or interested on the subject.