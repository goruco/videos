---
speaker: Bryan Reinero
title: Event sourcing
twitter: blimpyacht
year: 2015
youtube_video_id: dOlTRl8gJIs
bio_photo: bryan-reinero
---

Event Sourcing is powerful way to think about domain objects and transaction processing. Rather than persisting an object in it's current state, event sourcing instead writes an immutable log of deltas (domain events) to the database. from this set of events, an object's state is derived, at any point in the past, simply by replaying the event history sequentially.

Event sourcing is a deceptively radical idea which challenges our contemporary notions about transaction processing, while also being a mature pattern with a long history. This talk will take a look at how event processing is used across a spectrum of use cases, including database engines and financial systems, to Google Docs hacks.
