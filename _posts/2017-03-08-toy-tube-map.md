---
layout: post
icon: icon-toy-tube-map.png
title: "Toy Tube Map"
description: "An app built using Google, TFL and custom APIs where tube carriages and their lines can be added to a map of London and watched in real time."
heroku: "https://tube-map.herokuapp.com/"
github: "https://github.com/jackhkmatthews/WDI_PROJECT_2"
image: "toy-tube-map.png"
tags:
  - Node.js
  - Express.js
  - gulp.js
  - MongoDB
  - Mongoose
  - JSON web tokens
  - Bcrypt
  - ES6.
---

## Overview

After considering a few ideas, I decided to try and build my own version of a live tube map, where animated tube carriages would be visible to the user in near real time - informed by TFL's Unified API.

I initially considered mapping and animating all of London's tube carriages simultaneously however decided it to be beyond the scope of the project and almost definitely beyond my current ability. Instead the user would add their own trains to the map by selecting line, origin and destination. The trains would then depart in near real time using information from TFL's unified API.
