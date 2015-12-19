---
speaker: Matt Duncan
title: High Performance Caching with Rails
year: 2012
vimeo_video_id: 45094725
---

<p>At Yammer, we handle thousands of requests per second for pages which consist of private data that varies based on perspective. This perspective makes it difficult to take advantage of traditional Rails caching techniques. To solve this problem, we've moved almost all of our caching to the data layer.</p>
<p>In this talk, I'll dig into how this type of caching allows us to cache far less data than traditional methods, invalidate fewer records, improve our cache hit rates, and scale to hundreds of thousands of memcache of requests per second with a 98% cache hit rate - all while showing users data differently based on perspective.</p>
