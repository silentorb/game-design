# Inspiration Contrast

## Overview

* There are no games that are similar to the game I want to make
* That's not a good thing
* This document is an attempt to isolate the differences between the games closest to what I want to make and the game I want to make
* There are some games that are in many ways closer mechanics-wise but are not immersive 3D games (real time first or third person), which rules them out
  * I'm only interested in creating an immersive 3D game and have found that it is too big of a gap to act as a starting point
    * In other words, I need to start with an immersive 3D game and port over elements from more abstract games, as opposed to starting with a more abstract game and trying to convert it to an immersive 3D game


## Closest Games

* Alan Wake
* Dark Souls
* Alice: Madness Returns
* Dishonored
* The Witcher 3
* DOOM 2
* Dungeon Defenders

## Contrast Matrix

|                         |                 Design Cost                  |       Alan Wake        |       Dark Souls       |        Alice 2         |       Dishonored       |     The Witcher 3      |        DOOM II         |   Dungeon Defenders    |
| ----------------------- | :------------------------------------------: | :--------------------: | :--------------------: | :--------------------: | :--------------------: | :--------------------: | :--------------------: | :--------------------: |
| **Essential**           |                                              |                        |                        |                        |                        |                        |                        |                        |
| Practical MVP           | :large_orange_diamond::large_orange_diamond: |   :heavy_check_mark:   |   :heavy_check_mark:   | :skull_and_crossbones: | :skull_and_crossbones: | :skull_and_crossbones: |   :heavy_check_mark:   |   :heavy_check_mark:   |
| **Primary**             |                                              |                        |                        |                        |                        |                        |                        | :skull_and_crossbones: |
| Minimal Fighting        | :large_orange_diamond::large_orange_diamond: |   :heavy_check_mark:   | :skull_and_crossbones: | :skull_and_crossbones: |   :heavy_check_mark:   |   :heavy_check_mark:   | :skull_and_crossbones: | :skull_and_crossbones: |
| RPG Character Growth    |                      ⚪                       | :skull_and_crossbones: |   :heavy_check_mark:   | :skull_and_crossbones: |   :heavy_check_mark:   |   :heavy_check_mark:   | :skull_and_crossbones: |   :heavy_check_mark:   |
| Unique Playthroughs     | :large_orange_diamond::large_orange_diamond: | :skull_and_crossbones: | :skull_and_crossbones: | :skull_and_crossbones: | :skull_and_crossbones: | :skull_and_crossbones: | :skull_and_crossbones: | :skull_and_crossbones: |
| Non-linear (Micro)      |                      ⚪                       | :skull_and_crossbones: | :skull_and_crossbones: | :skull_and_crossbones: |   :heavy_check_mark:   |   :heavy_check_mark:   |   :heavy_check_mark:   |   :heavy_check_mark:   |
| Strategy                |                     🔴🔴🔴                      | :skull_and_crossbones: |   :heavy_check_mark:   | :skull_and_crossbones: | :skull_and_crossbones: | :skull_and_crossbones: | :skull_and_crossbones: |   :heavy_check_mark:   |
| Tactical Puzzle Solving | :large_orange_diamond::large_orange_diamond: | :skull_and_crossbones: |   :heavy_check_mark:   | :skull_and_crossbones: |   :heavy_check_mark:   | :skull_and_crossbones: |   :heavy_check_mark:   |   :heavy_check_mark:   |
| **Secondary**           |                                              |                        |                        |                        |                        |                        |                        |                        |
| Multi-domain            |                     🔴🔴🔴                      |   :heavy_check_mark:   | :skull_and_crossbones: | :skull_and_crossbones: |   :heavy_check_mark:   |   :heavy_check_mark:   | :skull_and_crossbones: | :skull_and_crossbones: |
| Minimal reflexes        |                      ⚪                       |   :heavy_check_mark:   | :skull_and_crossbones: | :skull_and_crossbones: |   :heavy_check_mark:   |   :heavy_check_mark:   |   :heavy_check_mark:   |   :heavy_check_mark:   |
| Non-linear (Macro)      |                      ⚪                       | :skull_and_crossbones: |   :heavy_check_mark:   | :skull_and_crossbones: | :skull_and_crossbones: | :skull_and_crossbones: | :skull_and_crossbones: |   :heavy_check_mark:   |
| Non-location reaching   |                     🔴🔴🔴                      | :skull_and_crossbones: | :skull_and_crossbones: | :skull_and_crossbones: | :skull_and_crossbones: |   :heavy_check_mark:   | :skull_and_crossbones: |   :heavy_check_mark:   |
| Single map              |                      ⚪                       | :skull_and_crossbones: |   :heavy_check_mark:   | :skull_and_crossbones: | :skull_and_crossbones: | :skull_and_crossbones: | :skull_and_crossbones: | :skull_and_crossbones: |
| Solid Loss              |                      ⚪                       | :skull_and_crossbones: |   :heavy_check_mark:   | :skull_and_crossbones: | :skull_and_crossbones: | :skull_and_crossbones: | :skull_and_crossbones: |   :heavy_check_mark:   |
| Protecting NPCs         | :large_orange_diamond::large_orange_diamond: | :skull_and_crossbones: | :skull_and_crossbones: | :skull_and_crossbones: | :skull_and_crossbones: | :skull_and_crossbones: | :skull_and_crossbones: |   :heavy_check_mark:   |
| Score                   |                                              |           4            |           7            |           0            |           6            |           6            |           4            |           10           |
| Engine                  |                                              |         Custom         |         Custom         |         Unreal         |         Unreal         |         Custom         |         Custom         |         Unreal         |

### Minimum Design Challenge

:large_orange_diamond::large_orange_diamond:

### Maximum Design Challenge

⚪⚪⚪⚪⚪⚪:large_orange_diamond::large_orange_diamond::large_orange_diamond::large_orange_diamond::large_orange_diamond::large_orange_diamond::large_orange_diamond::large_orange_diamond::large_orange_diamond::large_orange_diamond:🔴🔴🔴🔴🔴🔴🔴🔴🔴

Where the baseline of zero is a modern DOOM variant.

## Game Notes

### Alan Wake

* Even though it fails so much of the criteria, it works so well as an interactive story that looking at the data this way makes me rethink my views and consider whether maybe I could make a game with stripped down mechanics and a focus on setting and story
* Alan Wake has a lot of fighting but I still put it as "minimal fighting" because:
  * Many fights can be avoided and don't require killing
  * Half of the game is travel and story
    * At its heart Alan Wake is really a walking simulator
* It's stretching things a bit to say this can support a practical MVP, but potentially an Alan Wake style game can still be useful as a demo
  * Steam has a handful of critically acclaimed free-or-nearly-free games that last a half hour or less
    * That's never been my cup of tea but I need to start seriously considering options like that or this project will never be practical

### Dark Souls

* Mechanics-wise, this is the closest game to what I am trying to make
* It's stretching things a little to say this can support a practical MVP, but the Souls-like formula has been taken so many directions I think the core essence has been well formalized and proven to be fairly minimal

### Alice: Madness Returns

* Even though Alice 2 fails every criteria in this survey, it's still worth including because at a glance it looks like there's a lot of similarities and is worth clarifying

### Dishonored

* Matches a lot of the criteria but fails an essential ones—a practical MVP
* Dishonored works because it is inefficient—it guzzles resources but has a lot of resources to guzzle

### The Witcher 3

* Similar to Dishonored, the Witcher 3 does not have a minimal core and instead relies on quantity of content and systems

### DOOM II

* The most straightforward and efficient core gameplay with few frills—supports the most practical and rich MVP
* Some great DOOM II Wads are single map but unfortunately I've never liked those as much—DOOM shines the most when it has map progression

### Dungeon Defenders

* It's been a while since I thought of Dungeon Defenders as an inspiration
* After putting this document together and thinking about defense again as possibility, Dungeon Defenders popped into mind
* It's actually closer to the mark than any other inspiration
* I've been partially deterred from Dungeon Defenders because it has a number of design decisions I don't care for but are not actually integral to its model (such as excessive loot and grinding)
* One of the main differences I would consider would be to de-emphasize both tower placement and player combat in favor of environment interaction as a means of defense configuration

## Feature Notes

### Minimal Fighting

* While games like DOOM II are all about combat, I'm toying with the idea of taking traditional combat mechanics and reskinning them with a more symbolic, non-combat domain such as spiritual warfare

