---
speaker: Solomon Kahn
title: BI Tooling with Rails
year: 2014
vimeo_video_id: 101025640
layout: post
---

###Talk Synopsis
Non-technical people in companies need data, but don't have the programming skills to get it themselves. So, it becomes your part-time job to get them data. As your company grows, this problem only gets worse.

We built a (soon to be released as open source) Ruby on Rails app that has completely transformed the way non-technical people at Paperless Post access data. With this 'simple' rails app, we are able to offer sophisticated, on demand, realtime reporting, that takes almost no developer time.

The intended audience is anyone who works at a company with ten or more people, where it starts to becomes very painful that non-technical people don't have access to data.

I'll go over why the current solutions (often getting a developer to run a database query / lots of cronjobs) don't solve this problem well, and how their shortcomings become incredibly painful as an organization grows.

Then, I'll show the tool we built at Paperless Post, which does a really great job solving this problem. It uses some not-commonly-used features of ActiveRecord and erb to take this complicated problem and solve it elegantly.

To say this app has made life better at Paperless Post would be an understatement. At the end of the talk, I hope attendees can go back to their companies, implement our tool, and bring more joy and happiness into their lives.

Here's a step by step outline of the talk:

* The Problem 
* How Most Companies Try To Solve It 
* How Activerecord & erb Create a Better Solution 
* Going Through The Code
* Dashboards, Visualizations and Complex Reports
* Deploying The Application 
* The Social & Political Benefits Within Your Company
