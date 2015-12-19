---
speaker: Aaron Quint
title: The Future of Ruby Performance Tooling
year: 2014
vimeo_video_id: 101415184
bio_photo: aaron-quint
---

It's just a fact that as a baseline, Ruby is not the fastest language or platform out there. We've always been comfortable with the trade of raw speed for the thrill and happiness of development.

We can however, be completely left in the dark when an application is in production and needs to grow to meet the requests of a very demanding audience. Ruby 2.1 has begun to provide hope for the future of Ruby, especially large production Ruby applications, by exposing new features and hooks for debugging performance problems. Though Ruby hasn't become as fast as other dynamic languages (yet) at least now we can build and use some of these new tools to make our applications as fast as possible.

I'd like to share an overview of these new features as well as some tooling and problems we've faced at Paperless Post as we've scaled, and how we've tried to use Ruby to solve them.

I'm extremely excited about the potential of Ruby 2.1, not just the tools it exposes, but what it means for the future of Ruby performance tooling. Now that there are a number of people working on Ruby who are concerned about its speed and performance visibility, these tools are only going to get better. I'd like to introduce the new Ruby features, then walk through some custom performance tooling we've been working on through real world examples.

(Some) of the topics I'd like to cover:

* Brief overview of new Generational GC
* Object Space dumps
* Analyzing Object Space dumps
* Using the object allocation maps
* Rblineprof and ppprofiler
* StackProf
* rbtrace and attaching to a Unicorn

I'll also give a sneak preview of some tools we've been working on that are not Open Source (yet) which I'd like to share.
