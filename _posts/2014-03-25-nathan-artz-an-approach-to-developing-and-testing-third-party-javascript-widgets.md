---
speaker: Nathan Artz
title: An Approach to Developing and Testing Third Party Javascript Widgets
year: 2014
vimeo_video_id: 101020271
bio_photo: nathan-artz
---

Google Analytics, Like Buttons, Twitter Widgets, Olark chat boxes; all examples of third party JavaScript elements that are embedded by users in their websites.

Testing third party code once embedded in a page, is often difficult and cumbersome.  Verifying those elements are working properly (or even more basically, are not breaking the page) is difficult to get right.  Clients will often not give you access to their page, or allow you to debug 'live', leaving scope for bugs to creep in.

Complicating matters further, other JavaScripts are often competing to execute on the page (sometimes erroring out), and then you have to make this all work cross-browser!

####So what is the right approach to take?

I will show you how using a Ruby script to generate and minify my JavaScript, and a Node.js proxy server to intercept responses, I am able to safely inject my JavaScript into the page.

In addition to this, I will show you ways to use Rspec/Capybara to come run regression tests that utilize the proxy, and test my JavaScript while it is **live** embedded on client pages.
