# Marloth Game Design

## Design Tasks

* I still haven't defined the player's primary activity

## Gameplay

1. Survival Horror
2. Roguelike
3. Role Playing Game
4. Immersive Sim

## High-Level Requirements

### Design

* First-person
* Biblical themes
* [Procedurally generated world](./subjects/world-generation.md)
* Minimal combat
* Realtime yet does not put much weight on reflexes or quick decisions
* Concrete and immersive (Minimally abstract)

### Technical

* Feasible for a one-man team
* Fits within the constraints of Unreal Engine

## Features

* Automatic simulation
* Indirect agency
* Character growth
* Invisible actors and happenings
* Things happening outside the players' vision?
* Avoiding dangers
* Local co-op

## Non-goals

* Constant busy work
  * It's okay for the player to wait for things
* Athletic world traversal
  * The traversal in the game will be simple and limited
  * No jumping, grappling hooks, or wall climbing


## Design Challenges

#### Non-Spatial Progress

* Spatial progress—a term I made up to represent victory being tied to the player getting to a particular location
* Most of my Marloth games have been trying to avoid or minimize spatial progress—having a world where the player hangs out instead of tries to just get past—but that has never worked out great

#### Scaling Player Count

* I'd like this game to work both as single player and multiplayer

#### Simple Foundation

* Is it is even possible for all of the above criteria to be met with a simple foundation?

## Design Questions

These are less inherent challenges and more unknowns that I have often struggled to answer.

### What are the primary activities?

* [Primary activities](./subjects/primary-activities.md)

### What is the Main Gameplay Loop?

1. Wake up
2. Explore the world
3. Avoid dangers
4. Interact with the world
5. Return home to rest
6. Review, upgrade, and plan

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

### Range-Based Logic

* Physical mechanics can be hard to control, but one of the simplest spatial mechanics to leverage is the distance one object is from another

### Character Growth

* Upgrade-based system