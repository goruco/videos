---
speaker: Mike Dalessio
title: Nokogiri - History and Future
year: 2013
twitter: flavorjones
link: mike.daless.io/
youtube_video_id: qkvEjZ-mGQA
bio_photo: mike
---

Over the past few years, Nokogiri has slowly eclipsed older XML parsing libraries to garner nearly 10 million downloads from [rubygems.org](http://rubygems.org).

But why another XML parsing library? Isn't it boring? And what does "nokogiri" mean in Japanese, anyway?

These questions will be answered, and I'll do a brief dive into all the technologies that we use to make Nokogiri a fast, reliable and robust gem. Topics will include:

* Origins of the project: motivation, problems and impact
* Native C and Java extensions
* FFI, and how to know if it's Right For You
* Debugging tools (valgrind, perftools)
* Packaging tools (mini_portile, rake-compiler)
* Installation issues, and what we're doing to help
* Feature roadmap
