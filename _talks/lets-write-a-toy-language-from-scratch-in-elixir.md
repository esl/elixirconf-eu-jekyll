---
level:
- Intermediate
tags:
- langdev
- parsing
- diy
audience: "- Developers who did not try writing a toy language yet, or who would like to see how some common problems can be implemented under the hood."
format: Virtual
title: "Let's Write a Toy Language from Scratch in Elixir"
speakers:
- _participants/lucas-sifoni.md
key_takeaways: "You'll have a look on implementing from scratch:\n
- Tokenization\n
- Parser combinators\n
- Pretty printers\n
- AST transformations\n
Which are techniques that can be leveraged in daily work outside of the toy language domain!"

---
Without libraries, we'll see how we can leverage Elixir specificities to easily tokenize, parse, print and interpret a toy language with a few recognizable features (variables, primitive types, closures).

Adding OTP and Phoenix LiveView to the mix, it evolves towards a quirky stateful computation system with basic graphical editing of programs.
