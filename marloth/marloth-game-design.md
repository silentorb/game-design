# Marloth Game Design

## Design Tasks

* I still haven't defined the player's primary activity

## Gameplay

1. Survival Horror
2. Roguelike
3. Role Playing Game
4. Immersive Sim

## Requirements

### Design

* First-person
* Procedurally generated world
* Minimal combat
* Realtime yet does not put much weight on reflexes or quick decisions
* Concrete and immersive (Minimally abstract)

### Technical

* Feasible for a one-man team
* Has a practical MVP
* Fits within the constraints of Unreal Engine

## Features

### MVP

* Tactical puzzle solving

### Version 2

* Character growth

## Tensions

Ties conflicting requirements together

### Tactical Puzzle Solving and Concrete

* There's a certain depth of tactics and strategy that I have mostly only ever experienced in games with more abstract UIs
  * Be the UI truly abstract, 2D, and/or turn-based
* Immersive 3D games struggle to have the same depth of tactics and strategy
  * Some notable exceptions are:
    * DOOM 2
    * Dark Souls
    * Team games like TF2 and Paladins

### Independent Essentials

Essential requirements that don't complicate the design, don't get in the way of other requirements, and don't make the game more difficult to create.

* Single difficulty
* Short playthroughs

## Design Challenges

### MVP

#### Non-Spatial Progress

* Spatial progress—a term I just made up to represent victory being tied to the player getting to a particular location
* Most of my Marloth games have been trying to avoid or minimize spatial progress—having a world where the player hangs out instead of tries to just get past—but that has never worked out great

#### Scaling Player Count

* I'd like this game to work both as single player and multiplayer

#### Simple Foundation

* Is it is even possible for all of the above criteria to be met with a simple foundation?
  * If not, I've got to scale back my expectations

### Version 2

#### Restricting Movement

## Design Questions

These are less inherent challenges and more unknowns that I have often struggled to answer.

### What are the Primary Activities?

#### Summary

1. Navigation
2. Exploration
3. Avoiding dangers
4. Gathering resources

#### Navigation

* At first glance, navigating around a 3D world sounds boring
* Yet that is one of the primary actions of a first person shooter, and when I think about it, if the environment is interesting then I do enjoy walking around it
* This is in part how walking simulators have become a viable genre
* Some games, particularly third-person action games, make navigation very involved and elaborate
* I want to keep navigation simple, but squeeze every ounce of significance from it
* There is a danger that navigation as a primary activity may prove boring for me and I'll lose interest, but I think this is going to work
* I've been fighting against this for years, and yet at the end of the day one of my biggest drives is to make a cool 3D world and how I love seeing 3D worlds from different angles, why wouldn't moving around that world be important?

#### Exploration

* Exploration isn't normally something I look for in a game
* Yet I've avoided hand crafted maps and repeatedly gravitated toward procedurally generated maps
* Occasionally in a game I will get into exploration
  * Playing Minecraft is probably when I've enjoyed exploration the most
    * It would be worth listing other games that piqued my exploration interest

#### Avoiding dangers

* Out of all of the primary activities, this is the one that immediately interests me the most
* I love engaging enemies in non-lethal, indirect means, and I feel like action games focus too much on permanently destroying threats instead of surviving them
* Indirect solutions also lend themselves better to tactics and strategy
  * When a game is about promptly killing everything in sight, threats become short term problems with little long-term impact beyond the question of how much player ammo and health they drained

#### Gathering Resources

* This is something I never look for in games and rarely enjoy—I'm not a hunter/gatherer
* However, resource gathering keeps coming back as a perfect ingredient for rounding out this recipe
* Once again, maybe I can isolate the games with resource gathering which I enjoyed the most, and see if there are ways I can make the resource gathering more fun for someone like me

### What is the Main Gameplay Loop?

1. Wake up
2. Explore the world
3. Gather resources
4. Fight monsters
5. Return home to sleep

### What are the player goals?

### What are the Loss Conditions?

## Game Language

### As a first person 3D game, what are the most defining, inherent aspects of the game?

First person 3D games are fundamentally concrete, so all of these aspects are concrete.

1. Player location
2. Player facing
3. What is and isn't visible to the player
4. Spatial relationship between the player and other objects
5. Light and darkness (Relates to the previous two items)

Features such as player health are more abstract and are injected into first person games.  (That is partially why health is usually displayed in an abstract HUD instead of within the 3D environment.)

## Design Solutions

### Surrealism

* Placing characters within unrealistically close proximity
* Artificial barriers to maintain balance
* Unnatural mechanics that join domains that would otherwise be unrelated
* Making abstract domains more concrete and spatial than they normally are

### Spatial Integration

* Focusing on elements and mechanics primarily interacting spatially instead of abstractly
  * This is the opposite of what I've often been planning—making an abstract game with a spatial veneer
    * I've been fighting the spatial nature and that has just never worked well—I have a spatial world and need to leverage it

### Range-Based Logic

* Physical mechanics can be hard to control, but one of the simplest spatial mechanics to leverage is the distance one object is from another

### Experience and Level System

* ~~I've been trying to avoid traditional XP/level systems since I started making Marloth games but there's a reason they are so prevalent in RPGs: they just work.~~
* ~~Experience provides a universal currency for integrating intrinsic character growth~~
* ~~Levels provide a clear path for applying experience~~

A traditional level system made more sense with fixed worlds and is less needed with a Roguelike.  Levels are actually uncommon in action roguelikes.

## ~~Player Role~~

### ~~MVP~~

* ~~Guardian~~

### ~~Later Versions~~

* ~~Provider (family)~~
* ~~Guide~~
* ~~Hunter~~
* ~~Artisan~~
* ~~Counselor~~
* ~~Merchant~~
* ~~Gatherer~~