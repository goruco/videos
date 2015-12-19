---
speaker: Paul Dix
title: Indexing Thousands of Writes Per Second With Redis
year: 2011
vimeo_video_id: 26626837
---

The financial market data application that we're building sustains an average write load of around 10,000 writes per second. Scaling a system to handle this many writes while responding quickly to user requests is quite challenging. Our data store is able to keep the data, but the indexes required to respond to user requests would completely overload it. To solve the problem we moved to storing indexes in Redis. Its functionality and high speed made dealing with this write load manageable.

This talk will cover what types of operations and data structures Redis provides that enable it to ac as an indexing server. It's a case study of using Redis as more than just a key value store or the backend for Resque. I'll cover the design issues with keeping indexes in Redis and making sure that they get updated if there is an outage. Cache warming, data structures, and advanced Redis use are all part of the talk.
