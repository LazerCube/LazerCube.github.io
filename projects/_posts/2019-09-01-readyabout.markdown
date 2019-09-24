---
layout: posts
title: Ready About
author: Elliot
tags: 
- Django 
- Python
- CSS
- Docker
- Rabbitmq
- Nginx
- Web
published: true
about: Created to give small rental boatyards around the UK a simple platform to advertise their boats against others and to give them metrics and marketing information in order to help them increase their holiday bookings.
summary: Referral based boat rental advertising and marketing system.
image: /assets/img/posts/readyabout/readyabout_thumbnail.png
image_preview: /assets/img/posts/readyabout/readyabout_thumbnail_preview.png
source: closed
link: readyabout.co.uk
---

## About

The UK has a large number of holiday boat rental yards many of which are small family run operations running WordPress sites with 3rd party booking systems. However, many still don’t have a great online presence for reasons such as:

- Poor SEO
- Lack of technical knowledge
- Underestimation of a online presence
- Unwillingness to invest both time and money to achieve
- Limitations with their current WordPress sites

So I decided to create ReadyAbout.co.uk, A invite only service that allows members to advertise their boats to a larger audience while providing them tangible metrics that will help them improve their business and gain information on the broader health and opportunities available in the industry in real-time.

---

## Difficulties And Solutions

### Time Management and MVP

One of the main lessons I’ve learnt during the duration of this project is how important it is to manage my time and what to spend my time on. At the start of the project I kept all my ideas, features and to-do list in my head which caused the project to feel overwhelming, leading to months of very little progress. I’d spend weeks working on tangent ideas for the project but never really got any closer to having a finished product. To solve this I’ve switched to using a simple Trello board to keep track of the key tasks that I need to-do in order to get the product to market and keep me on track.

<div class="image-container">
    <img class="gallery-img" src="/assets/img/posts/readyabout/trello-screenshot.jpg">
</div>

Since Implementing this change I’ve seen my productivity increase dramatically and progress towards getting a finished product steadily getting closer.

---

## Notable Features

- **Task schedular** - Rambitmq + Celery
- **Generic promotion system**
- **Related object scoring system** - Gives each object a relative rank compared to other objects of the same type. Score considers the number of unique impressions an object is getting, related objects score, how new the item as well as others to ensure that it’s fair but competitive.
- **Support for 3rd party API’s** - Authorization support for several different request authorization types including, simple tokens and OAuth2
- **Referral link signup**
- **Login**
- **CRUD functions** - Allows members to manage their boats, boatyards and account. (Not using Django admin)
- **Web admin CRUD** - Allows for admin functions, tasks and management (Using Django Admin)
- **Metric Tracking** - Daily, weekly and monthly tracking of data
- **Local and global filtering by URL** - Local views for each location, acting like an independent website for that location while still being on the same system. Enabling local filtering of that locations boatyards, news, area information, FAQ’s, etc.
- **Template switching** - Switch templates for object based on currently viewed location allowing for a custom look and feel for each location.
- **Custom CSS framework** - Built off PureCSS
- **Mutiple docker configs** - For production and development
- **Modern production Stack** - Ngnix + Gunicorn + Postgres
- **Custom django admin theme**

---

## Screenshots

<div class="image-container">
    <img class="gallery-img" src="/assets/img/posts/readyabout/home-dev-screenshot.png">
    <img class="gallery-img" src="/assets/img/posts/readyabout/boat-list-old-screenshot.png">
    <img class="gallery-img" src="/assets/img/posts/readyabout/boat-detail-dev-screenshot.png">
</div>
