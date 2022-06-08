---
audience:
- intermediate
tags: []
title: Comparing the Actor model and CSP concurrency with Elixir and Clojure
speakers:
- _participants/xiang-ji.md
published: false

---
One big selling point of the BEAM VM is its from-the-ground-up implementation of the Actor model. CSP, another concurrency paradigm, has gained a lot of traction via Go, while also being embraced by Clojure. There is shared heritage between Elixir & Clojure, as well as between Actor model & CSP. However, radical differences between BEAM and JVM inevitably lead to intriguing divergences. You'll gain a better understanding of these paradigms, and (hopefully) a bit more appreciation of what makes BEAM unique.

  
**Talk objectives:**

* Better understanding of the Actor model
* Better understanding of unique features of the BEAM VM (e.g. process memory space isolation, preemptive scheduling, soft real-time, independent generational garbage collection)
* Better understanding of CSP, of how concurrency challenges are approached in languages such as Go and Clojure.
* Better understanding of the similarities and differences between Elixir and Clojure.
* Better understanding of the strengths and weaknesses of the BEAM VM compared with other runtimes such as the JVM.

**Target audience:**

* People who could benefit from more knowledge of the BEAM VM, with which they can become better Elixir/Erlang developers.
* People who want to learn more about the characteristics of and differences between concurrency paradigms.
* People who are curious about Go's/Clojure's approach to concurrency.
* People who are curious about the contrast between Elixir and Clojure, the BEAM VM and the JVM.