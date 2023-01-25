# Marloth Game Design

## Design Tasks

* I still haven't defined the player's primary activity
* Organize documents

## Gameplay

1. Survival Horror
2. Roguelike
3. Role Playing Game
4. Immersive Sim

## Requirements

### Design

* First-person
* Biblical themes
* [Procedurally generated world](./subjects/world-generation.md)
* Minimal combat
* Realtime yet does not put much weight on reflexes or quick decisions
* Concrete and immersive (Minimally abstract)

### Technical

* Feasible for a one-man team
* Has a practical MVP
* Fits within the constraints of Unreal Engine

## Features

* Tactical puzzle solving

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

#### Non-Spatial Progress

* Spatial progress—a term I just made up to represent victory being tied to the player getting to a particular location
* Most of my Marloth games have been trying to avoid or minimize spatial progress—having a world where the player hangs out instead of tries to just get past—but that has never worked out great

#### Scaling Player Count

* I'd like this game to work both as single player and multiplayer

#### Simple Foundation

* Is it is even possible for all of the above criteria to be met with a simple foundation?
  * If not, I've got to scale back my expectations

## Design Questions

These are less inherent challenges and more unknowns that I have often struggled to answer.

### What are the primary activities?

* [Primary activities](./subjects/primary-activities.md)

### What is the Main Gameplay Loop?

1. Wake up
2. Explore the world
3. Gather resources
4. Fight monsters
5. Return home to sleep

### What are the player goals?

### What are the Loss Conditions?

## Game Language

* [First person language](./subjects/first-person-language.md)

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