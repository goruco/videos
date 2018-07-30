---
speaker: Kir Shatrov
title: Running Jobs at Scale
year: 2018
youtube_video_id: XvnWjsmAl60
bio_photo: kir-shatrov
---

<p>We hear talk about running 1,000s of RPS on Rails, but what about running 1,000s of jobs per second? Jobs often go unnoticed and have much fewer patterns than controllers or models in Rails. def; perform; end, done!</p> <p>In this talk, you&#39;ll learn the patterns we enforce at Shopify for writing jobs at scale. How do you deal with jobs that run for days or weeks when you fail over data-centers? How can you automatically partition workloads over multiple workers? How can you help developers write idempotent jobs? By giving jobs a bit more structure, we can greatly improve their utility.</p>
