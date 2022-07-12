# Marloth Game Design

## Design Tasks

### Defense

* Determine whether a defense-focused game could solve many of my current design woes
  * Keeping in mind that my closest inspirations are not defensive but offensive

## Gameplay

* Immersive Sim
  * With the following differences:
    * Random scenario adjustments
    * Shorter playthroughs
* Survival Horror
* Role Playing Game
* Open World

## Requirements

### Design

* Third-person
* Minimal randomness
* Minimal combat
* Profound
* Realtime yet does not put much weight on reflexes or quick decisions
* Concrete and immersive (Minimally abstract)
* Non-linear

### Technical

* Feasible for a one-man team
* Has a practical MVP
* Fits within the constraints of the Unreal Engine

## Features

### MVP

* Character Growth
* Tactical puzzle solving
* Strategy

### Version 2

* Multi-domain
* Meaningful, significant spatiality
  * Treating locations as characters with distinct personalities
  * Locations being a reflection of their masters
* Unique playthroughs

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

* Hand-crafted map
* Single difficulty
* Short playthroughs

### Nice to Have

* Single map

## Design Challenges

### MVP

#### Limited UI

* UI is always one of the main bottlenecks with games
* For a 3D game, abstract UI is extra challenging

#### Tamed Growth

* Growth is one of my favorite part of games
* Growth is one of the most difficult aspects to tame
* Most games balance growth by crippling it and making it almost an illusion

#### Non-Spatial Progress

* Spatial progress—a term I just made up to represent victory being tied to the player getting to a particular location
* Most of my Marloth games have been trying to avoid or minimize spatial progress—having a world where the player hangs out instead of tries to just get past—but that has never worked out great

#### Scaling Player Count

* I'd like this game to work both as single player and multiplayer

#### Simple AI

* AI can get complicated and require a lot of work and maintenance
  * I enjoy working on complex AI but for the sake of the project I need to keep the AI stupid simple, at least for MVP
* How can the AI be kept simple?

#### Simple Physics

* While basic spatial logic is easy, physics can quickly get messy and hard to tame
* Physical mechanics need to be kept simple

#### Simple Foundation

* Is it is even possible for all of the above criteria to be met with a simple foundation?
  * If not, I've got to scale back my expectations

### Version 2

#### Tamed Randomness

* I want variety of encounters, but randomness has always bitten me
* Randomness is a two-edged sword

#### Integrating Unrelated Domains

#### Restricting Movement

#### Non-Spatial Domains

#### Realtime Discourages Decision Making

## Design Questions

These are less inherent challenges and more unknowns that I have often struggled to answer.

### What is the Primary Activity?

* Can I say pseudo-fighting? (Treating non-combat domains like they are combat?)

### What is the Main Gameplay Loop?

### What are the player goals?

### What are the Loss Conditions?

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

* I've been trying to avoid traditional XP/level systems since I started making Marloth games but there's a reason they are so prevalent in RPGs: they just work.
* Experience provides a universal currency for integrating intrinsic character growth
* Levels provide a clear path for applying experience

## Player Role

### MVP

* Guardian

### Later Versions

* Provider (family)
* Guide
* Hunter
* Artisan
* Counselor
* Merchant
* Gatherer