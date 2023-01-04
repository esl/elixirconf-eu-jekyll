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

- Results can be displayed directly as images
- Share code and dependent modules as a notebook so anyone can run it immediately
- One notebook is one node, so it is easy to understand distributed processing intuitively

This presentation shows a Livebook version of the presentation by Susumu Yamazaki at ElixirConf US 2022.

**Talk objectives:**	
* I would like to present the effectiveness of image processing in Elixir. By doing so, I hope to increase the number of system development projects using Elixir.
* I also hope that Livebook will become more popular than Jupyter for use in data analysis, AI development, and programming education.
* I would also like to increase the opportunities for Livebook to be used in presentations just like mine.

**Target audience:**
* Anyone interested in distributed processing of images.
* Anyone interested in Livebook visualization.