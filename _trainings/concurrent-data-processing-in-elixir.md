---
experience:
- Between intermediate to advanced *programmers*, with intermediate+ Elixir experience
name: Concurrent data processing in Elixir
type: training
trainers:
- _participants/andrea-leopardi.md
published: false
---
Consuming data and processing it is a central problem in so many systems nowadays. And Elixir is just so good at doing that, and doing it concurrently! Whether you run an event-sourced architecture with applications that react to events, or you have the occasional use case of map/reducing over collections in an optimized way, Elixir has your back. The current ecosystem is full of fantastic tools to help with these problems: GenStage, Broadway, Flow.  
  
In this training, I'll teach you how to use these tools and how to design applications that leverage their power.

**Training objectives:**

You'll be familiar with techniques and strategies to take the most advantage of tools such as GenStage, Broadway, and Flow. You'll also see plenty of examples, such as:

* Concurrent batch processing of jobs (Broadway)
* Reacting to async events in your system, such as AWS S3 uploads (through SNS notifications) (Broadway)
* Event-source systems (Broadway)
* Rate-limiting outgoing requests, whatever "request" means (GenStage)
* Downloading a lot of files in parallel and processing their contents (map/reduce with Flow)

**Training prerequisites:**

Skill include being familiar with Elixir's syntax and concurrency model (processes and OTP). Software is limited to Elixir.
