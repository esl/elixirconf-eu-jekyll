---
tags:
  - elixir-python-interoperability

level: Intermediate
title: "Drunk Snakes, Why Python and Elixir Are a Great Pairing"
speakers:
  - _participants/maciej-gryka.md

---
Nobody here needs convincing that Elixir is an amazing programming language. I'm here to insist that Python is _also_ a great fit for some scenarios and that it's pretty easy to combine the two languages to get the most out of them.

We'll start with a brief demo to motivate why you might want to attempt this: a toy language model finetuning system, where the orchestration is done by Elixir and the fine-tuning itself in Python using Unsloth. Then, we'll walk through how to call both Elixir from Python (shelling out & Pyrlang) and Python from Elixir (Pythonx). We'll learn how to easily set up fault-resistant, highly-distributed systems, while taking advantage of a massive ecosystem of existing software. We'll also talk about what kinds of problems might benefit from combining the two ecosystems and which will not.

**Key Takeaways:**

- both Elixir and Python are cool
- they have complimentary strengths
- interoperability between them is good (though maybe not great yet)

**Target Audience:**

- Anyone interested in developing highly-available systems taking advantage of recent AI advances.
