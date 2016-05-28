---
layout: post
title:  "The Device"
date:   2014-01-03 06:00:00 -0700
categories: libgdx java mobile android
---
So this here's my second game project that I contributed to while I was in my university's video game development club, otherwise known as the Video Game Development Club [VGDC]. The Device was a fixed camera 2D device defense game, and by device defense game, I mean you defend a device. That's why we called it The Device.

So for what the game is. There's a little machine on the playable field that spits out physical experience points while various monsters of varying designs try to destroy the machine. You control a player character that goes around hitting monsters with a giant wrench and keeping the machine from not exploding. The experience points that the machine spits out can be collected to upgrade your character and skills (which was planned at some point), or consumed by monsters which would then evolve and make your day much worse by having more HP and special skills.

We built this project using Java and libgdx as a graphics library. On this team, we had one producer, three artists, one designer, and five programmers (including myself). Justin, our producer, was essentially the glue for our project (the man kept us from starving through obscene amounts of Taco Bell tacos), and after he got a job doing writing or something, the project kinda fell apart. But before that, we had pretty decent communication between everybody, with designers talking to artists and programmers talking to designers and artists being weirded out by programmers.

The repo linked in this post is actually a fork (or attempted fork, none of us really knew how to use version control back then) of the original project repo, which was scrapped for some reason I can't remember anymore. The original concept started back in 2012, with a slightly different team of people during a Game Jam (think Hackathon, but for game devs). I came onboard around the start of 2013, wrote code, and ate tacos.

[Here it is][device].

For this project, I was in charge of monster AI, evolution of monsters, some level of collision detection, setting up a halfway decent animation system, and player controls and actions. Back when we had two programmers, the other guy took care of sound, the rest of collision detection, asset management, and some level of the mechanics involved in the game. The designer balanced the game and made high level decisions, the artists made spritesheets and static assets, and the producer kept us all on track in terms of tasks completed.

At around the end of the school year in 2013, we actually won the GameSIG collegiate game of the year award. I think I still have a certificate or a trophy or something around here, but they also got us a free copy of Heart of the Swarm for Starcraft II which I never used because I don't have StarCraft.

Overall, this was a pretty good experience. It was my first time working in a team this big, and with decent management, we got a lot done.

[device]: https://github.com/putty174/TheDevice
