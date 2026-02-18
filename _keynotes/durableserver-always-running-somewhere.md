---
level: Beginners
title: "DurableServer: Always Running Somewhere"
speakers:
- _participants/chris-mccord.md
published: true
---
What if your processes could survive node failures, move between machines, and pick up where they left off? DurableServer extends the familiar GenServer contract with automatic state persistence, distributed coordination, and cluster-aware recovery. Watch complexity melt away while you get back to thinking in processes and messages. Durability becomes just another thing your processes do.

In many applications, processes represent real things like users, game sessions, rooms, or devices. These need to be guaranteed running somewhere on the cluster, recoverable after crashes, and observable by the rest of the system. We'll explore globally unique processes, state synced to object storage for restoration on any node, capacity-aware placement, sticky routing, and lifecycle events that let your application react as durable processes come and go.

With DurableServer, routing, load balancing, node pinning, and regional placement are solved problems. You stop thinking about them. It all collapses down to something that feels like writing a regular GenServer.
