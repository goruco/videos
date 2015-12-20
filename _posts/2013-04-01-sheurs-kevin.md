---
speaker: Kevin Sheurs
title: Building a Theme Engine w/ Ruby Mustache
year: 2013
twitter: ksheurs
link: kevin.sheurs.com
youtube_video_id: Sh3hrETMPj8
bio_photo: kevin
---

This talk will explore the design and architecture of the [VHX](http://vhx.tv) theme engine, which allows our filmmakers to easily create highly-customizable websites to promote and sell their movies. We’ll walk through the technical and UX decisions that were made to optimize for maintainability, flexibility and future-proofing.

VHX themes are a blend of HTML, CSS, JavaScript and Mustache templates that are parsed by both Ruby and JavaScript. On the Ruby side, our theme engine can take advantage of server-side rendering, caching, and testability; with the JavaScript implementation we can add client-side rendering, live previewing, and enable an offline development environment for theme designers.

We’ll show off the code involved in VHX’s theme engine, advanced code editor (with live previewing through the HTML5 postMessage API), a master/child inheritance system that allows themes to be forked, and piecing it all together in a beautiful, easy-to-use interface.
