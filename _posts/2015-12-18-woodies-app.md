---
layout: post
title:  "Woodies App"
date:   2015-12-18
categories: Node.js app
---

##Screen Shot

<img src="../../../../../../../images/Woodies.jpg">

##About Woodies

Woodies app for woodworking

Using the pinterest API and scrapping lots of information to get this app working. A place for people who have an interest in woodworking to find information. Easy to find info on the basics for woodworking. Find and save your tools, learn some basic skills, and find project ideas!

Find the app at <a href="https://woodiesapp.herokuapp.com">woodiesapp.herokuapp.com</a>

Using Node.js and express to run this app. Has connected database and tables with postgres.

Found some issues using the pinterest API, not with using it per-se, but some functionality I had hoped for does not exist with their API. Example being that you cannot search for pins by their name, you need to search for pins by their ID. You can search a users pins, which is what I have done, but I have found that 24 hours after you pin, they cannot be accessed through the API. This will cause my app to have issues after I stop pinning to my boards. It is easy to pin to your board and look at pins if you can find them. So that was fun to figure out!

This was 5 days worth of work and if I had more time I would spend it either finding a way to convert the searched pin name to a pin id that would find pins, if that is possible. If I could not get that to work I would go on to try and find a different API that could be used to search for projects.

Hope you find a fun project!
