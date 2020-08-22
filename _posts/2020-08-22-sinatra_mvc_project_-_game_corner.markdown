---
layout: post
title:      "Sinatra MVC Project - Game Corner"
date:       2020-08-22 17:09:18 +0000
permalink:  sinatra_mvc_project_-_game_corner
---


For our latest project we were tasked with creating a MVC web app that utilizes CRUD functions using Sinatra. 
I was inspired after talking to a friend who told me he keeps a list of games he's played in an excel spreadsheet.  I decided to make an app that allows users to keep track of and describe their favorite games. 

I used the ever-generous Corneal gem to set up the tree structure for my app. From there I needed to create my application_controller, games_controller, & users_controller tieing them all together in my config.ru file. Doing so allows them (after making sure they were both inheriting from the application controller) to pass data through each controller. I could have kept everything in the application_controller but my desire for clean, easy to read code pushed me in the right direction. 

Working through setting up satisfactory views folders / files, models, and migrations we're essential to getting Game Corner up and running. I spent many hours fighting errors that turned out to be routed in a bad migration or syntax error. Building this project has taught me how important it is to pre-plan the workings of my code as well as when to call it a night and pick it back up in the morning with a fresh set of eyes. 

Overall, this project was a challenge but one I feel confident has left me a better Software Engineer.

On to the next!

