---
layout: posts
title: Ready About (WIP)
author: Elliot
tags: 
- Django 
- Python
- CSS
- Docker
- Rabbitmq
- Nginx
- Web
about: Created to give small rental boatyards around the UK a simple platform to advertise their boats against others and to give them metrics and marketing information in order to help them increase their holiday bookings.
summary: Referral based boat rental advertising and marketing system.
image: /assets/img/posts/readyabout/readyabout_thumbnail.png
image_preview: /assets/img/posts/readyabout/readyabout_thumbnail_preview.png
source: closed
---

## About

The UK has a large number of holiday boat rental yards many of which are small family run operations running a WordPress site with a 3rd party booking system. However, many still don’t have a great online presence for reasons such as:

- Poor SEO
- Lack of technical knowledge
- Underestimation of a online presence
- Unwillingness to invest both time and money to achieve
- Limitations with their current WordPress sites

So I decided to create ReadyAbout.com, A invite only service that allows members to advertise their boats to a larger audience while providing them tangible metrics that will help them improve their business and gain information on the broader health and opportunities available in the industry in real-time.

## Difficulties And Solutions (WIP)

- Time Management – Trello, Agile, [More information on Trello structure](https://www.flowji.com/using-trello-to-manage-your-website-project/)
- Django-Summernote - XSS Exploit.
- Scheduling tasks for promotions – Rambitmq + Celery
- API System – Failed original design. Tried to create a generic system to handle any API and map to fields in my database. Switched to manually handling mapping of an API.

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
