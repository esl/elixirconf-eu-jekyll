---
tags:
  - ai-search-scale

level: Intermediate
title: "AI-Powered Search at Scale"
speakers:
  - _participants/jeff-weiss.md

---
At Frame.io (Adobe), we built AI-powered search to help creative professionals find the exact shot or moment across millions of assets. This required two AI integrations: an LLM for natural language queries and vector embeddings for semantic visual search.
Our LLM component uses Meta's Llama 4 via AWS Bedrock, translating queries like "videos of people on beaches from last week" into OpenSearch DSL. For visual search, we generate vector embeddings using Adobe's SearchCut API (CLIP-based models), enabling similarity searches without metadata.
The challenge? Video embedding takes 30+ seconds per asset. Our Oban infrastructure—already split across four instances due to database contention—couldn't handle this load without impacting critical jobs.
Our solution: a multi-stage Broadway pipeline consuming from SQS. A router pipeline handles authorization and versioning, fanning out to dedicated embedding and transcription workers. This provides independent scaling, traffic buffering, and complete isolation from our job system.
You'll learn: practical LLM integration patterns, when to choose Broadway over Oban, and how to build observable AI pipelines in Elixir.

**Key Takeaways:**

- Practical AI integration patterns they can apply immediately
- Decision framework for Oban vs Broadway
- Real production architecture from a major Adobe product

**Target Audience:**

- Primary Audience
- 1. Backend Engineers building search or AI features
- Teams integrating LLMs (OpenAI, Bedrock, Anthropic) into Elixir applications
- Developers implementing semantic/vector search capabilities
- Engineers working with OpenSearch, Elasticsearch, or similar
- 2. Engineers managing high-volume async workloads
- Teams hitting scaling limits with Oban or database-backed job queues
- Developers evaluating Broadway for production use cases
- Anyone processing external API calls at scale
- Secondary Audience
- 3. Tech leads and architects
- Making build-vs-buy decisions for AI/ML integrations
- Evaluating infrastructure patterns for async processing
- Planning feature-gated rollouts of AI capabilities
- 4. Oban users curious about alternatives
- Understanding when Oban is (and isn't) the right tool
- Learning complementary patterns that work alongside Oban
