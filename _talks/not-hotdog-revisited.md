---
audience:
- Advanced
tags:
- Robot Sees Hotdog
title: '"Not Hotdog" Revisited'
speakers:
- _participants/evadne-wu.md

---
In this session, the speaker demonstrates the power of the Elixir ecosystem by replicating the hallowed meme “Not Hotdog” with conventional technology. The session covers the following tasks commonly seen in MLOps and application development in general.  
  
The outline is as follows:

\- Defining the problem  
\- Reviewing the scope of the problem  
\- Arranging the flow of control and data channels  
\- Designing overall system topology  
\- Integrating custom ML models in an Elixir system  
\- Selecting and loading the Model  
\- \[If using Axon.Serving\] Converting the Model for Axon.Serving using axon_onnx  
\- Testing the Model in batched operation  
\- Building a script to submit still frames  
\- Adapting the Model for interactive operation  
\- \[If using Axon.Serving\] Building the backend node with Axon.Serving  
\- \[If not\] Building a custom C Node for high-performance interoperation  
\- Building the video pipeline with Membrane  
\- Creating the overall Pipeline with Membrane  
\- Extracting and converting raw video frames  
\- Creating the backend for request submission  
\- Implementing a rate limiter with backend back-pressure  
\- Providing interactivity with Phoenix LiveView  
\- Creating custom JavaScript hooks & UI elements  
\- Integrating WebRTC feedback into the viewport  
\- Overlaying on-screen annotations with Phoenix LiveView  
\- Review / Compare & Contrast  
\- Testing the Solution  
\- Audience Q&A

**Talk objectives:**
1\. To demonstrate the power of the Elixir ecosystem and the amount of engineering leverage available today  
2\. To promote the art of writing useful, inter-operable programs quickly based on the Unix philosophy.  
3\. To improve upon an ancient meme and bring joy to the community by creating useful & shared experiences.

**Target audience:**
Scenarios:  
\- Perhaps one would like to integrate and run one’s own ML models within Elixir systems?  
\- Perhaps one would like to know how to architecture such systems end-to-end while maintaining good operational hygiene?  
\- Then one should come to this session and see for oneself, how an end-to-end solution can be built.  
  
**Prerequisites:**  
\- It is advised that the audience should have some prior experience in MLOps, however such experience is not required to enjoy the session.  
\- It is advised that the audience should have at least a rudimentary level of understanding of how Deep Learning models work (both training and deployment), having such experience will make the talk more understandable, however such experience is not required as the content focuses on operational concerns rather than the theoretical.