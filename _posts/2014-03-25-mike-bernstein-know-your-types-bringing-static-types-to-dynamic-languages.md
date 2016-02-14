---
speaker: Mike Bernstein
title: Know Your Types - Bringing Static Types to Dynamic Languages
year: 2014
vimeo_video_id: 101415185
bio_photo: mike-bernstein
---

After several years of being a professional programmer, I realized that I didn't really know what I was doing, and decided to teach myself Computer Science. After spending a year learning Computer Science from the ground up, I thought I was starting to understand things. Then I came across Haskell.

It fascinated and frustrated me, and I wanted to understand how types worked. I also began wondering - why doesn't Ruby have a modern type system? Do we need one? Do we *want* one? How would it work?

 I ended up coming across three amazing pieces of writing that helped illuminate things for me:

- "Types and Programming Languages" by Benjamin C. Pierce
- "Propositions as Types" by Philip Wadler
- "A Practical Optional Type System for Clojure" - Ambrose Bonnaire-Sergeant

After studying these works, I still can't write Haskell, but I do understand a lot more about what types are. In the course of my research, I also came across two fascinating projects - a static type checker for Ruby, and a type inferencer for Ruby, both experimental projects from the University of Maryland's Programming Languages lab (PLUM). These provocative projects helped me understand how static types could be integrated into dynamically typed languages. While they aren't practical implementations, they made me think. Which is what I'd like to make you do during this talk - think about types, how they could help us, and what we sacrifice by not having an expressive type system in Ruby.
