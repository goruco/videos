---
speaker: Nick Gauthier
title: Grease your Suite Tips and Tricks for Faster Testing
year: 2010
vimeo_video_id: 12705404
missing_photo: true
---

Continuous integration is a great way to keep your code base organized and well tested. But when a test suite takes so long to run that developers stop running it before every commit, they lose their constant feedback loop and quality drops. In this talk we’ll explore methods of speeding up the test suite so that developers can be confident about the code they’ve written before they share it with the team.

We’ll start with quick cheap fixes, like optimizing your operating system, that can yield drastic results (like cutting test time in half!) with no loss of functionality. We’ll also cover methods of writing tests that reduce their run time with gems like fast_context for shoulda. At then end, we’ll move to more involved methods of multi-tasking your test suite to run on all the cores in your workstation and even to setting up a distributed testing cloud to run all your tests in parallel.

Every tactic will be backed up with hard benchmarks from real production code. We’ll show the evolution of a test suite from its full run time of 13 minutes down to a number you won’t believe. By the end of the presentation, attendees will have learned methods that they can apply to their own projects to help speed up their development process.

Attendees should be familiar with testing a rails project. Knowledge of linux/unix is a plus, and knowing shoulda will make the test code easier to read.
