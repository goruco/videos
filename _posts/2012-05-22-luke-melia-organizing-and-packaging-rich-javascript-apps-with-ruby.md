---
speaker: Luke Melia
title: Organizing and Packaging Rich Javascript Apps with Ruby
year: 2012
vimeo_video_id: 45094222
---

<p>
  More and more developers are facing the challenge of organizing and deploying complex client-side Javascript apps. It turns out there are some excellent solutions to this problem bubbling up in the Ruby ecosystem. I am responsible for two complex Javascript applications at Yapp, and in this micro-talk, I will share a solid solution to this problem using open source Ruby projects.
</p>
<p>
  I will cover:
</p>
<ul>
  <li>Intro to Rake::Pipeline</li>
  <li>This project was recently open sourced by Living Social</li>
  <li>An extension to Rake for dealing with a directory of inputs, a number of filters organized as a pipeline, and a directory of outputs</li>
  <li>Great for describing and executing the build step of a pure client-side application</li>
  <li>Under-documented as yet</li>
  <li>Logical Javascript organization and simple dependency management with mini-spade and Rake::Pipeline</li>
  <li>As rubyists, we love clean, well-organized project directory structure</li>
  <li>Here's how to achieve this for your javascript</li>
  <li>Concatenating &amp; minifying assets</li>
  <li>A solid development environment with Rack, fssm, Puma and Rake::Pipeline</li>
  <li>Puma for using threads to hold requests while your assets are rebuilding</li>
  <li>Bonus: integrate automatic test execution</li>
  <li>fssm for watching your project files and proactively rebuilding assets</li>
</ul>

