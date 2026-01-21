---
tags:
  - liveview
  - webcomponents
  - interop

level: Introductory and overview
title: "Lit Up LiveView"
speakers:
  - _participants/ido-leshkowitz.md

---
Almost every LiveView developer reaches a point where they need rich client-side interactivity - a textarea that resizes, a drop zone that responds to dragging, a button that manages its own state. These interactions don't need the server, and LiveView isn't designed to handle them.
Web Components are a natural fit for this. Unlike framework-specific solutions, they require no integration layer - just custom HTML elements in your HEEx templates that react to attribute changes, exactly how LiveView already works.
In this talk, I'll share why this solution has worked so well for me and why I enjoy its simplicity. We'll explore how Web Components align with LiveView's model, then build a real component using Lit and integrate it into a LiveView application. You'll leave with patterns you can apply immediately.

**Key Takeaways:**

- Understanding why some UI state belongs on the client and doesn't need to involve the server
- How Web Components integrate natively with LiveView through attributes - no hooks or bridges required
- How to use Lit to build lightweight, reactive Web Components
- Practical patterns for passing data from LiveView to components and handling interactions
- Awareness of gotchas when integrating Web Components with LiveView

**Target Audience:**

- LiveView developers who want to add client-side interactivity to their applications. Attendees should be comfortable with LiveView basics (components, assigns, templates). No prior experience with Web Components or Lit is required.
