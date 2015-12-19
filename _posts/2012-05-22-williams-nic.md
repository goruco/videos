---
speaker: Nic Williams
title: Deployment - the difference between the 1st month and the next 59
year: 2012
vimeo_video_id: 44807823
---

When you type "cap deploy", "ey deploy", or "git push heroku master" your intent is to deploy your local application source to your running system on the Internet. That seems to be the point - you changed your code, and you want to Just Ship It. But what is your actual objective? Is it really to just "deploy app code changes"? Is this "app-centric" view and user experience satisfactory?

Code deployment is your intent on some occasions. On others you want to change your production environments for applications, or change scale attributes of your system, or change how applications and services within a system communicate with each other, or with remote services (such as facebook).

Is "app-centric deployment" the best mental model and toolchain for shipping changes to productions systems? Or is "environment-centric" or "node-centric", enabled with frameworks like Chef or Puppet, the most powerful & effective model of the system to allow you to deploy and manage change?

Or perhaps we should describe the entire system - all the apps, all the system dependencies, all the interconnections, all the scale attributes - and command it to come into existence? To command the system to go from nothing to v1 to v2 to v3, where each version includes changes in attributes of the system.

Where should configuration/manifests/attributes go? Source code files in the config folder? PaaS configuration or environment variables? Or should components of a system dynamically discover information about itself and configure itself?

Perhaps we need the benefits of a "system-centric" build toolchain, with an "app-centric" user/developer experience to trigger deploys, with a "node-centric" experience for sysadmins.

In this talk, we will reflect on the current state of deploying production systems, including build/deploy toolchains, and continuous deployment. We'll look at the attributes of a complete system, how we explicitly or implicitly describe them and their relationships, and how to orchestrate changes in the system - from app-centric, node-centric and system-centric views.

Let's discuss the difference between deployment in month 1 and living with your system for the next 59 months.
