---
layout: post
title:  "Google Maps Stupidne-, I Mean Battleships"
date:   2015-02-28 08:30:00 -0700
categories: google-maps-api google javascript node.js
---
Alright, so this thing was my attempt at a submission for the Google hackathon, where we were supposed to build a thing that involved parts of the API of any Google product. While everybody else thought about building applications to extend Google docs or something, I immediately went like "naw son, battleships". And so, me and two other people who had no experience in node, or javascript, or web development, set off on our journey to make the dumbest app ever.

We used node.js as the back-end for our application, because I had been working with Ruby on Rails for the job I had at the time, and I wanted to use something different. The front end was straight up CSS, without the use of any frameworks. Which would explain why the product looks like it does (also because we spent all our time working on the functionality). We also used websockets for P2P communication through the application, so that we could broadcast information about hit areas and whatnot to players on the site.

We got a very basic working demo up at the end, but the project wasn't really up to snuff. I had wanted to try and get room support and maybe even chat up by the end of the deadline, but time moved faster than we did.

[Here's the stuff, if you wanna check it out.][dumb]

[dumb]: https://github.com/EyeWumbo/GoogleMapsStupidness
