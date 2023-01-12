---
level:
- Intermediate
tags:
- VIRTUAL
- Livebook
- Distributed Processing
- Image Processing
title: Distributed and Parallel Image Processing on Livebook
speakers:
- _participants/ryo-wakabayashi.md

---
For example, if you want to hide a person's face in a photo, it is common to implement image processing in Python with NumPy and OpenCV.

However, with the advent of Nx and Evision, it has become possible to implement image processing in Elixir. And with Elixir's Flow, you can run your image processing faster and more robustly in a distributed and parallel way.

This presentation will use Livebook to show visually distributed and parallel image processing in Elixir.

Livebook has the below features that effectively demonstrate Elixir image processing and help you learn to implement it.

* Results can be displayed directly as images
* Share code and dependent modules as a notebook so anyone can run it immediately
* One notebook is one node, so it is easy to understand distributed processing intuitively

This presentation shows a Livebook version of the presentation by Susumu Yamazaki at ElixirConf US 2022.

**Talk objectives:**

* Present how Elixir can efficiently perform image processing.
* Show how Livebook can be useful for use in data analysis, AI development, and programming education.
* Encourage people to use Livebook for their presentations.

**Target audience:**

* Anyone interested in distributed processing of images.
* Anyone interested in Livebook visualization.