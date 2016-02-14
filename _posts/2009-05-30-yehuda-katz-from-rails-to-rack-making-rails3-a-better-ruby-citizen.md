---
speaker: Yehuda Katz
title: "From Rails to Rack: Making Rails 3 a Better Ruby Citizen"
year: 2009
youtube_video_id: m9eLeL9RdbA
bio_photo: yehuda-katz
---
Rails 3 is on its way, and Yehuda Katz is giving attendees a sneak peek! With the advent of the Rack spec and library, Ruby web frameworks can interact in unprecedented ways. Imagine a Rails application routing to a Sinatra application, or Merb-style exception pages that catch exceptions from Rails or Cloudkit. These are focal points of Rails 3 and Yehuda's talk.

The idea is simple: create a tiny API for interaction between elements of a web application. Instead of requiring special mechanisms for tests, controller instantiation, or CSRF forgery protection, design apps as a collection of such elements strung together into a stack. As with Unix pipes, limiting the interaction between elements makes powerful combinations a snap.

Merb 0.9 was rebuilt from the ground up to take advantage of Rack, and Rails has begun incorporating it as well. Rails 3 will make Rack a fundamental part of the framework.

Join Yehuda and talk about how this powerful idea is informing Rails 3, and how it will change the way you develop.
