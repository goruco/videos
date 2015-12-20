---
speaker: Zachary Feldman
title: Home Automation with the Amazon Echo and Ruby
twitter: zachfeldman
year: 2015
youtube_video_id: u1guHGWD1TU
image: zach-feldman
---

The Amazon Echo recently debuted and made a big splash with its incredibly accurate voice recognition, capable of hearing and transliterating commands from 20-30 feet away. Home automation enthusiasts and hackers alike wondered if it would be possible to intercept commands from the device and trigger custom actions. While device traffic is encrypted, the device pushes commands to a history page in a web application. Using Watir WebDriver, which normally is used for feature testing, we've created a proxy that can be run on a Raspberry Pi as well as a modular Ruby framework based on Sinatra to run custom commands, allowing us to control the Hue wireless lighting system, Nest, and even request an Uber!
