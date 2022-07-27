# Marloth Game Design

## Design Tasks

* I still haven't defined the player's primary activity

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
* Minimize combat where practical
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

#### Indirect Agency

* I love the Peter Molyneux approach to indirect player agency, and that feels like a good fit for this game
* However, that approach is also a two edged sword that has usually turned Molyneux games into novelties that are revered more for their ideas than their results
  * The classic example is Dungeon Keeper: even though it is one of the ultimate "high concept" video games, it is really clunky and I've rarely enoyed actually *playing* it
* If I did go with indirect player agency, how would that work?
  * As is so often the case, I don't have a precedent for this in a third-person game—most games with indirect player agency are god games
  * The closest precendent is again Dungeon Defenders...

#### Tower Defense

* Maybe I should bite the bullet and just make this into a tower defense game?
* Why am I adverse to focusing on towers?
  * They make the game too abstract, even when they are presented as stationary characters
    * How do they make the game abstract?  Are the towers inherently abstract or do they indirectly lead to more abstract gameplay?

  * Focusing on towers tends to naturally lend itself to mindless hordes of cannon fodder
    * In other words, towers work well because they are simple, but that simplicity almost requires an equally simple opposition
    * There may be a way of subverting this

* Why am I adverse to allowing players to place towers where they choose?
  * It almost seems like it gives the player so much freedom that the game becomes all about that freedom
  * In a way, it trivializes the environment
    * The most important aspect of the environment becomes how it statically influences your tower placement options
    * The environment becomes less a thing to be interacted with and more a canvas for towers
  * Maybe part of the issue is unless a tower is placed by a level designer, they don't really tightly integrate with the environment, they are just sitting there
    * For some reason I'm not bothered in the same way by characters and items
      * Maybe part of it is because towers are stationary—since they are stationary it feels like they should have a deeper relationship with their surroundings
      * Maybe that also is part of why player-placed towers feel more abstract

  * It can lead to lots of spatial glitches and whack-a-mole patching of fringe-case bugs
  * Player tower placement reduces the sense of indirect agency
    * No longer is the player subtly influencing their environment—they are directly shaping it
    * Instead of an existing conflict where the player is assisting one of the sides, the player *is* one of the sides

* Would it be possible for the MVP to be tower defense and instead of focusing on that feature throughout later versions, keep the tower defense elements light and instead add additional domains in later installments?
  * Have I ever seen a game successfully pivot like this?
    * If not, maybe I can isolate exactly what the pitfall is and find a solution?
    * The closest example I've seen, which is a major influence on my understanding of defense games, is WarCraft III
      * WarCraft III started off as a traditional RTS game, but most of the appeal for me ended up being its custom maps with their various combinations and mixes of offense and defense
      * Culminating in DotA leaving a larger legacy than the RTS aspects of WarCraft III

#### WarCraft III

* WarCraft III hero siege and AOS maps are the only good example I can think of defense being a versital foundation for many different player activities (and those custom maps are a very good example)
  * I've often found it surprising that WarCraft III hero siege maps haven't been a bigger influence
    * I have seen some games in the genre but none successful
    * This is in contrast to WarCraft III's influence on RTS, tower defense, Moba, and arena battles

#### Extracting Lessons from Hero Defense Maps

* Note: I would use the term "Hero Siege" here except now when I hear that phrase all I think about is that stupid game by the same name
  * that game actually started out as sort of a WarCraft III defense game and switched to being a Diablo II Rogue-lite
  * Hey, I guess that is another example of a game that successfully pivoted, though that wasn't so much an extension (adding new domains alongside the MVP domain) as much as a massive retooling of the core gameplay
    * In other words, they didn't simply adjust course: they backed up
* Players interact with the WarCraft III hero defense maps in the following ways:

##### Hero Placement

* Moving their hero around and having their hero fight
* This worked particularly well because the hero would have partial AI and would engage in battle on their own
* It was nice how the player could give micro-managing controls when they wanted to but by default they could rely on general automation
  * This is similar to the design I've always admired so much about Magic the Gathering, where each turn has so many phases that are normally implicitly skipped but are there when players need them

##### Placing Towers

* Mostly this was in tower-defense-focused maps, but I think there were one or more defense maps that sported tower placement as a supporting feature

##### Hiring Troops

* This wasn't very common, but some hero defense maps had this feature
* It helped mix things up and was easy to implement since it was the default mechanic for WarCraft III, but fit as well in game
  * At least not without a sophisticated UI to manage the troops
  * Off the top of my head I can't think of a first/third person 3D game that pulled off managing NPCs well—I feel like all of my experiences of this were unpleasant

##### Upgrading Defenses

* This is fairly common in hero defense maps
* This usually involved upgrading towers and upgrading barracks
  * The barracks would be periodically spawning new defensive troops
  * The towers would usually be built into the map and not player placed

##### Casting area spells

* Some of the maps like one of the AOS MTG maps featured occasional spell casting such as periodically being able to drop a nuke anywhere on the map
  * Being able to do so was an investment decision—the player did not immediately have this ability and had to choose to invest in such spells instead of other avenues

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