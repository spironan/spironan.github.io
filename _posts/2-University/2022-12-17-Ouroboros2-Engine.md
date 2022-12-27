---
layout: post
title: Ouroboros 2
subtitle: Digipen - 3D Custom Game Engine
# cover-img: /assets/img/path.jpg
thumbnail-img: /assets/img/Ouroboros2.ico
share-img: /assets/img/Ouroboros2.ico
tags: [Custom Engine, C++, Architecture, Multithreading]
---

Ouroboros 2 is the game engine created to power my 2 trimester long project in University during my senior year(3rd year).
The game engine has its origins stemming from prior experience from our sophomore project(Ouroboros Engine) and is re-built 
to suit the needs of an even more ambitious 3D game this time round with 7 other programmers.

# Contributions
My main role for the team continued from prior project as the overall Producer and as a Lead Engine Architect. 

A new focus on making sure that this many programmers are able to collaborate effectively with one another took special note and many of my decisions that differed from before came from taking this into consideration. One important enhancement was therefore the use of github actions to allow us to perform continuous integration (CI) and Continuous development (CD) and not be held back by having everyone to manually check each other's work all the time. This automation has improved our workflow significantly and allow us to be more laser focused on our work.

Another important decision this time was to split our work into separate libraries and integrate them to reduce direct dependencies between each other and help isolate and distinct each others contribution to allow for better debugging and integration. My focus this time was on creating a firm architecture that help support the needs of the fundamental game such as the game scene, scene management and a feature complete transform with scenegraph similar to what you'll see in Unreal and Unity. 

Alongside this, another key point was to focus on optimization as the game this time round is significantly more challenging to make with lots of moving parts and a gigantic world all within a single scene (semi-open world) game. Thus a lot of work was put into developing an effective thread pool to help delegate the work and break things down into pieces to allow all cpu core to be utilized for parallel processing of the work which saw dramatic improvements.

# Engine Trailer
Below is the WIP our of game engine after 4 months of work
<iframe width="720" height="405" src="https://www.youtube.com/embed/xNVJsWy4sAU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>