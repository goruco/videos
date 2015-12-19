---
speaker: James Golick
title: Scaling to Hundreds of Millions of Requests What Worked and What Didn’t
year: 2010
vimeo_video_id: 12814529
---

All over the web, people are discussing the latest scalable database, the newest testing strategy, or even cloud computing. Claims are made about scalability, reliability, and performance. But by definition, most of this hype is simply conjecture. Its authors rarely have the experience to support their claims.

In the process of scaling our ruby, rails, and scala app to 150 million monthly pageviews, we’ve tested a lot of these technologies and ideas. We’ve put several popular and supposedly scalable NoSQL database solutions in to heavy production use. We’ve tried testing frameworks and ideas. We’ve deployed both cloud computing instances and physical hardware. Some things worked - others failed spectacularly.

In this talk, I’ll share our experiences, good and bad. These are some of the topics we’ll cover:

Virtualization and Cloud Computing: Virtualized hardware is the default choice for new ruby deployments. That makes sense - it’s easy to get started, and you only pay for what you need. But when (if ever) does it make sense to move to physical hardware? It might be sooner than you think.

NoSQL: NoSQL is all the rage in the ruby community. There are quite a few solutions, nearly all of them advertised as fast, scalable, reliable. But what is it really like to run and maintain them in production?

Rails Best-Practices: There are certain practices rails developers take for granted. Automated testing and fat models are a given on almost every rails project. But are these really optimal strategies? Are there ways we can write better-designed, more maintainable code?
