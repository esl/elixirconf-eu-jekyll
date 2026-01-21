---
tags:
  - liveview-hooks-widgets

level: Intermediate
title: "Hooked on Widgets: A Better Pattern for Reusable LiveView Components"
speakers:
  - _participants/jakub-lambrych.md

---
Building reusable, stateful widgets in Phoenix LiveView has been challenging. LiveComponents can't access the process mailbox for PubSub integration, while embedded LiveViews create performance overhead and complex communication patterns. This talk presents a battle-tested alternative: combining function components with LiveView hooks to create truly independent widgets.

You'll learn how to leverage `attach_hook/4` to build widgets that manage their own state, handle events, subscribe to PubSub, and seamlessly integrate into any LiveView — without coupling to parent implementations. Through a real-world notification widget example, we'll demonstrate how this pattern delivers the best of both worlds: LiveComponent-like behavior with direct mailbox access.

**Key Takeaways:**

- Attendees will learn to build production-ready widget architectures using function components and LiveView hooks. They'll understand when to choose this pattern over LiveComponents or embedded LiveViews.

**Target Audience:**

- This talk appeals to intermediate and advanced Phoenix developers who have experienced the limitations of LiveComponents when building complex, reusable UI components with real-time requirements. It's particularly valuable for teams maintaining large LiveView applications with multiple interactive widgets (notifications, chat, dashboards, calendars), architects designing component libraries, and developers migrating from embedded LiveView patterns.
