---
tags: liveview reconnection restoring
level: Intermediate
title: "Phoenix LiveView: Mastering Reconnects for a Seamless User Experience"
speakers:
- _participants/giovanni-francischelli.md

---
Phoenix LiveView provides powerful tools to handle real-time interactions and reconnections gracefully. This talk explores how to maximize LiveView’s capabilities to create a seamless user experience during connection drops and recoveries. From basic use cases to handling advanced recovery scenarios, we’ll demonstrate techniques that ensure resilient and polished applications.

Whether you’re new to LiveView or refining an existing application, this session will equip you with practical strategies to leverage LiveView’s lifecycle, customize recovery workflows, and manage ephemeral UI state effectively.

**Key Takeaways:**
- Gain a clear understanding of the Phoenix LiveView lifecycle and its default reconnection behaviour.
- Learn how to delay the “reconnecting…” message for short-lived disconnects to improve UX.
- Explore phx-auto-recover for handling advanced form state recovery during reconnects.
- Master techniques for caching and recovering ephemeral UI state in the DOM during LiveView reconnects.
- Walk away with a practical example wrapping up all the covered techniques.

**Target Audience:**
Anyone writing or wanting to write web applications with Phoenix LiveView. Advanced reconnection issues will need to be handled eventually, specially if mobile usage is a big deal. Knowing how to do them early will surely prevent incidents.
