---
speaker: Andrew Metcalf
title: How to Load 1m Lines of Ruby in 5s
twitter: agmetcalf
year: 2017
youtube_video_id: lKMOETQAdzs
bio_photo: andrew-metcalf
---

Applications written in Ruby, Python and several other popular dynamic languages become very slow to boot as they grow to millions of lines of code. Waiting to reload code in development becomes a major frustration and drain on productivity. This talk will discuss how we reduced the time to boot a service at Stripe from 35s to 5s by statically analyzing dependencies in our codebase to drive an autoloader.
