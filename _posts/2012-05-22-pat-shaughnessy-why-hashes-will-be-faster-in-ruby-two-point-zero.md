---
speaker: Pat Shaughnessy
title: Why Hashes Will Be Faster in Ruby 2.0
year: 2012
vimeo_video_id: 45095659
---

<p>The upcoming Ruby 2.0 release contains an interesting performance optimization you may not have heard of before: small Hashes are actually implemented as Arrays!</p>
<p>In this micro talk, I'll:</p>
<ul>
  <li>review the basic theory behind hash functions and hash tables,</li>
  <li>show you the new internal data structures that Ruby 2.0 uses to save keys and values, and</li>
  <li>present some performance data that proves this optimization exists and how much time it will actually save you.</li>
</ul>
<p>Do you really need to know how Ruby works internally to be a Ruby devloper? Probably not. But looking "under the hood" is a lot of fun, and someday might help you use the language more competently.</p>
