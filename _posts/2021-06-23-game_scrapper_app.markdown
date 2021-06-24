---
layout: post
title:      "Game Scrapper App"
date:       2021-06-24 00:25:52 +0000
permalink:  game_scrapper_app
---


Game Scrapper is an app I wrote that, like the name implies, scrapes data from the website "www.alphabetagamer.com". The app iterates over the elements of the website extracting the names and descriptions of games on the first page, creating ruby objects with it and storing them for later use.

The app works with 2 instances of a Person class, one for us(the player) and another for the NPC(Non Playable Character). The player will start with an empty inventory of games, the NPC will have a pre-made list of games scraped from the 5th page of the website.

Note:* The list of games you see on each run of the app can change based on the website's changes, games you see now can be different on another run.*

Upon running the app you will be greeted and prompted to type your name, Player will then be taken to the main menu where they will be able to:


**Buy Game:**
Player will have a list of 5 games(scrapped from Alphabetagamer.com) to choose from to ad to their inventorty

**Trade Game:**
Player will have the hability to trade a game of their choice from their inventory with the NPC, player also chooses which game they want to receive in turn

**Toss Game:**
Player can discard a game from their inventory. NOTE: Toosing a game is permanent, players cannot recover tossed games

**Give game:**
Player can choose to give a game of their choice to the NPC

**Take game:**
Player is able to take a game from the NPC's inventory

**Change your name:**
Changes the player's name, in case you didn't like the name you chose in the beggining or if you made a typo

**View your games:**
Lists the player's inventory and allows them to view a brief descrption of a selected game

**View NPC's games:**
Lets player see the games in the NPC's inventory


This is a very simple app to demonstrate understanding of some basic Ruby coding, working with Array, Hashes, Object oriented ruby, HTML and Nokogiri, and scrapping websites.

I hope you find this app interesting at least and thank you for taking the time to read this.


