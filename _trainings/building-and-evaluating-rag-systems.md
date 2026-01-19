---
experience:
- Intermediate
title: "Building and Evaluating RAG Systems"
type: in-person full-day training course
venue: NH Málaga
trainers:
- _participants/chris-beck.md
event_date: 22 April

---
Retrieval Augmented Generation (RAG) systems are arguably the simplest and most powerful tool in agent-based AI.

Although they are widely implemented and used in production, their performance in terms of relevance, groundedness, and truthfulness is rarely assessed once they are in use. 

In this workshop, you will learn a set of practical evaluation techniques for RAG systems, ranging from baseline offline metrics to reference-free evaluation for cases where 'the truth' is not known in advance, and finally production monitoring and A/B testing.

We will start with a simple RAG system and evaluate it using methods such as Haystack, covering toolsets such as RAGAS and concepts such as the RAG Triad. 

We will then progress to evaluating with synthetic datasets. You will learn how to generate synthetic question/answer sets using LLM calls, and how to evaluate them with the help of rankers, as well as how to evaluate different embedding models and set cut-off parameters.

Next, we will evaluate the generation part of RAG. You will learn how to set up and use LLM judge methods. 

Finally, we will explore data structures that enable the constant monitoring and A/B testing of production systems.

**Learning outcomes:**
By the end, you will be able to:
- Diagnose RAG performance in terms of relevance, groundedness and truthfulness
- Build an evaluation harness for a simple RAG pipeline
- Use common toolkits (e.g. Haystack, RAGAS) and concepts (e.g. the RAG triad) to measure and debug failures.
- Create and evaluate synthetic datasets (question/answer pairs and hard negatives) when labelled data is scarce.
- compare embedding models, tune retrieval cutoffs and evaluate ranking choices
Evaluate the generation step using LLM-as-judge methods (with guardrails for bias and consistency).
Design data structures and workflows for continuous monitoring, regression testing and A/B experimentation in production.

**Training objectives:**
* Introduction to RAG
* Simple RAG evaluation techniques
* Synthetic dataset creation and evaluation
* How to set up LLM-as-a-judge
* Constant evaluation of RAG systems in production

**Training prerequisites:**
* A linux or mac laptop with Elixir and Postgres installed.
