---
tags:
  - liveview
  - case-of-study
  - roi

level: Intermediate
title: "Guaranteed Journeys: Protecting Corporate Accounts with a LiveView Real-Time Dashboard"
speakers:
  - _participants/gabriel-ortuno.md

---
In the world of B2B ride-hailing, reliability is currency. Failing to assign a ride for a corporate client doesn't just annoy a user—it jeopardizes entire enterprise contracts.

At Cabify, our operations team initially relied on a Looker Studio dashboard to manage these critical journeys. The result was frustration: data was stale due to polling, BigQuery costs were mounting, and agents were losing precious seconds waiting for refreshes while VIP clients waited for rides.

We needed a replacement that was real-time, cost-efficient, and reliable. We needed it immediately.

This talk dissects how a single backend developer replaced that legacy solution with a Phoenix LiveView dashboard in just two weeks, achieving a 99% assignment success rate.

**Key Takeaways:**

- The "Build vs. Buy" Tipping Point: Learn how to identify when a generic BI tool (like Looker Studio) becomes a liability. We will show that when "Read-Only" analytics turn into "Read-Write" operations, moving to a custom LiveView app is not just faster—it’s cheaper and safer.

- Velocity without Fragility: Discover how the LiveView architecture allowed a single backend developer to bypass the complexities of API design, state synchronization, and React/JSON glue code to ship a production-hardened internal product in just two weeks.

- From Polling to Push: See the tangible architectural benefits of replacing expensive, laggy polling queries with real-time Phoenix PubSub streams, resulting in immediate data consistency for agents and reduced database load.

**Target Audience:**

- This talk is designed for Engineering Managers and Technical Leads looking for high-ROI strategies to build internal tools with limited resources, as well as Backend Developers eager to leverage LiveView to deliver full-stack, real-time applications without the complexity of a separate frontend codebase.
