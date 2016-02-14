---
speaker: Paul Dix
title: Building Web Service Clients with ActiveModel
year: 2010
vimeo_video_id: 12811450
missing_photo: true
---


With the introduction of ActiveModel, Rails is no longer bound by a specific ORM (ActiveRecord). ActiveModel exposes not only a common interface for the Rails 3 model layer, but also a set of tools for building data models. This talk will go over techniques and code for using web services as a model layer with clients that leverage ActiveModel’s functionality.

This talk will cover how to use ActiveModel to write web service client libraries that can be used as a drop in replacement for ActiveRecord based models. This means they will work in form view helpers and with Rails’ routes and url generation. The primary topics will cover validation, serialization, request logic, use in development, and compliance testing.

The list of topics and technologies covered will include: How to write client side validations with ActiveModel::Validations. How to write clear libraries that use ActiveModel::Serializers. How to abstract connection logic and ensure parallel execution and speed (using Typhoeus or a threaded model). How to test your library’s compliance with ActiveModel::Lint coverage.

While there has been some coverage of ActiveModel already in some blog posts, this talk will dive deeper and show how it can be used specifically for writing easy to use, readable, maintainable, and performant web service client libraries.

Attendees should be familiar with Ruby and Rails. Knowledge about asynchronous and threaded programming is helpful, but not required.
