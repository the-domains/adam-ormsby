---
inFeed: true
hasPage: true
inNav: false
inLanguage: null
starred: false
keywords: []
description: "Undertakers is a networked four-player competitive shooter developed during Columbia College Chicago's Large Team 2013 senior capstone project. The year-long (two-semester) sequence was structured as a commercial development project, complete with all production phases (pre-production/concept, production, QA, and release). The object of this free-for-all game is to scour the Wild West town of Abandon to find a bar of gold and hide it from your opponents. The longer the gold stays hidden, the more points you get."
datePublished: '2016-04-02T02:20:33.058Z'
dateModified: '2016-04-02T02:20:19.326Z'
title: Undertakers
author: []
authors: []
publisher:
  name: null
  domain: null
  url: null
  favicon: null
sourcePath: _posts/2016-04-02-undertakers.md
published: true
url: undertakers/index.html
_type: Article

---
# Undertakers

Undertakers is a networked four-player competitive shooter developed during Columbia College Chicago's Large Team 2013 senior capstone project. The year-long (two-semester) sequence was structured as a commercial development project, complete with all production phases (pre-production/concept, production, QA, and release). The object of this free-for-all game is to scour the Wild West town of Abandon to find a bar of gold and hide it from your opponents. The longer the gold stays hidden, the more points you get.
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/8bb9775c-082b-425c-ae09-bcae9c929dd1.png)

## Gameplay and user interface design

I worked with many of my teammates to design the structure of overall gameplay with a focus on the mechanics of retrieving and hiding the gold bar as well as the general win conditions of the game. I designed the main flow for entering and exiting a game of Undertakers, focusing on matchmaking and how the user interface conveyed the process of creating a match. I assisted with the implementation of these game systems as well as others.
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/59a24cad-fb85-4746-ae02-eaf73546430e.png)

Integrated the Mecanim animation system

My biggest role on Undertakers was working with the animation team to develop player movement and character behaviors. We upgraded to a newer version of the Unity 3D game engine halfway through our project, and with that change came a need to integrate the new Mecanim system into our animation pipeline. Working with the animators, I modified our character controller code to support this new system, and I built a brand new animation network to support our character motion.
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/1343a3c8-6ee6-4332-a9ff-a1cc9409bb23.png)

Developed network synchronization structure

After developing the initial network prototype for our game, I was given the responsibility of further building and maintaining our synchronization system on and off throughout the project. I developed an initial structure for passing gameplay and animation data across clients that other programmers used as a guideline for their work, and I assisted when problems arose within that structure. This work was assisted by the use of the Photon Unity 3D Networking Framework purchased for the use of this project.