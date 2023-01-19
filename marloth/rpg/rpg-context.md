# Marloth RPG Context

This is a supplemental document for [RPG Design](./rpg-design).

## Motivation for RPG elements

* Character growth and customization is one of my favorite game features

## Problems with RPG elements

* They don't naturally fit into a first person game—first person games a concrete while RPG elements are abstract

* Player growth in any form is hard to balance over time

  * Most games that contain player growth heavily gate it


## Character Classes

I love character class themes and would like to have them, but the question is how generic and how particular should their implementation be?

### Class Systems

There are three main types of class systems in RPGs:

#### Class-Based

* Characters have specific classes and there is little overlap between each class
* Sometimes supports multi-classing
* Usually most skills are intrinsic and are not conferred through equipment
  * Instead, equipment mostly modifies stats
* Usually uses a level system

* Examples:
  * Dungeons and Dragons
  * Diablo II
  * Tales of Maj'Eyal
  * Grim Dawn

#### Domain-Based

* Potential character investment is divided into multiple domains
* Character classes largely define starting domain allocation
* Each domain has one or more numerical values representing the player's investment in that domain
  * Those domain values are either directly invested in or are an indirect sum of the investment in that domain
  * An example of multiple values per domain: some games require the player to invest in both spell power and mana pool size to effectively use magic
* May have starting classes that establish an initial character direction
  * The player can then either follow that direction or deviate from it
* Usually uses a level system
* While a player can invest in many domains, focused builds are usually optimal
* Usually skills are less intrinsic and mostly conferred through equipment
* Examples:
  * System Shock 2
  * Dungeons of Dredmor
  * Path of Exile
  * Dark Souls

#### Upgrade-Based

* Classes are simply starting packages with a collection of starting items (abilities/upgrades)
* Usually only appears in Roguelites and within ability systems that have no foundational domains or themes
  * Some abilities may share a common theme but that is optional per ability
* Usually games with this approach have some classes with unique abilities and some classes with common abilities
* Usually has less control over the direction of character growth over the course of each playthrough
* Usually does not use a level system
* Examples:
  * The Binding of Isaac
  * Ziggurat

### Comparison

#### Criteria

| Name              | Description                                                  |
| ----------------- | ------------------------------------------------------------ |
| Thematic          | How well the system supports stylized groupings of skills    |
| Planning          | How well the system supports the player planning ahead what skills to acquire |
| World integration | To what degree skill acquisition ties into the environment   |
| Adaptability      | How much the player is challenged to adapt their skill selection to circumstances |
| Mutability        | How easy it is for the player to adjust their character configuration during a playthrough |

#### Rating

|                   | Class                                | Domain                               | Upgrade                              |
| ----------------- | ------------------------------------ | ------------------------------------ | ------------------------------------ |
| Thematic          | :green_book::green_book::green_book: | :orange_book::orange_book:           | :closed_book:                        |
| Planning          | :green_book::green_book::green_book: | :orange_book::orange_book:           | :closed_book:                        |
| World integration | :closed_book:                        | :orange_book::orange_book:           | :green_book::green_book::green_book: |
| Adaptability      | :closed_book:                        | :orange_book::orange_book:           | :green_book::green_book::green_book: |
| Mutability        | :closed_book:                        | :green_book::green_book::green_book: | :closed_book:                        |
|                   |                                      |                                      |                                      |
| **Total**         | 9                                    | 11                                   | 9                                    |

## Skill Acquisition

* Choosing new abilities is one of my favorite activities in a game
* Oddly enough, even though trees are very restrictive and I usually prefer more open ended systems, I enjoy skill selection even more when it takes place within a fixed hierarchy

### Skill Trees

#### Pros

Why do I like skill trees so much?  I would expect someone like me to not like them.

* Big picture
  * I like how skill trees give a clear visual representation of how an ability fits within the larger picture and how it relates to other abilities
* Planning ahead
  * Similar to the previous point, a skill tree allows players to plan ahead—if I want to get a later ability I see the earlier abilities I need to acquire first
* Theme visualization
  * I love character class themes, and skill trees can act as showcases, displaying all of the abilities in a single view so the player can get the full force of the theme

#### Cons

* They are not as flexible to develop and expand upon
* Most games with skill trees are released out of the gate with the trees fully fleshed out and fine-tuned to fit within a single UI view
* Skill trees loose some of their appeal when they need scrolling or zooming
* They nearly require a level-based character system
  * It is possible though uncommon to have non-level based skill trees
    * The main example I know of is Dead Space, where the player collects points to invest in multiple trees

## Disadvantages

### Background

* Primarily inspired by GURPS
* Some notable games where player characters can accumulate disadvantages:
  * Mordheim
  * Dungeon Crawl Stone Soup
  * Darkest Dungeon
* Rogue Legacy also prominently features disadvantages though they are only auto-assigned during character creation, not acquired over the course of play

### Motivation

* Disadvantages fit particularly well in survival horror games
* I've toyed around with idea in the past of having characters age and get slowly weaker over the course of a playthrough—I wasn't completely sold on the idea when it was a simple stat loss (gradual decline in max health, speed, etc.) but endlessly accumulated disadvantages sounds more interesting (I may have thought about that before but the foundation of my designs did not support the idea as well as the current foundation.)
  * Part of the motivation for this is the market currently has more than enough power fantasies and I like the idea of anti-power fantasies, which again is more inline with survival horror
    * Part of this motivation is also because I think excessive power fantasizing is unhealthy and is subtly warping cultural values
* All that to say, with the combination of disadvantages and an [intrinsic world](#intrinsic-world), potentially most or all of the scaling difficulty of the game could be simply through disadvantage accumulation
  * The world doesn't get more dangerous, the player traits effectively cause the player to be more dangerous

## Intrinsic World

### Motivation

* Part of the motivation for this is I'm an introvert and I prefer intrinsic features over extrinsic features
  * This direction opens up the possibility to increase how many of the game mechanics are intrinsic
* This idea also aligns with the first Marloth book and similar narratives where the world is partially a manifestation of the protagonist's personality and inner struggles
* Focusing on intrinsic abilities should also add more opportunity for spiritual elements
* Focusing on intrinsic abilities should also leave more room for a multi-domain world, where enemies

## Character Planning

* I love planning in games but this game can't have everything and planning doesn't fit well with the rest of the elements
* Later versions could have supplemental features to better support planning, such as report views visualize future possibilities



## Ability Attachments

### Motivation

* The primary motivation is to have different triggers on abilities

* I like the idea of each upgrade having a type and zero or more attached modifiers
* However, that attachment system could quickly become too complicated
* There are probably a few different ways I could constrain the system to make it simpler

#### Non-Orthogonal

One problem is that base abilities and attachments are non-orthogonal.

Possible solutions:

1. Any ability can be a root or an attachment, they just work differently in each position

2. Root abilities have random attachments and when a player acquires two root abilities of the same type they merge into one ability with their attachments merged as well