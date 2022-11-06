# Marloth Combat

## Goals

1. To reward creative decision making and adaptation more than quick reflexes
2. To embrace and fully leverage the spatial nature of 3D games
3. For the player to be passive, circumventing threats instead of eliminating them
4. To feature combat where the player can be surrounded by enemies of all types and not only survive but also have time to plan and react
5. To maximize and refine the core challenge of the player moving around a dangerous environment before layering on abilities and RPG elements
6. To reward strategy when practical

## Rewarding Decisions

* Most of this will boil down to tactics
* Tactics is not my favorite type of gameplay, but I can still get into it
* I prefer strategy, but that is so much harder to [inject into a game like this](#strategy)

## Spatial Foundation

### What are the most defining aspects of a first person 3D game?

1. Player location
2. Player facing
3. What is and isn't visible to the player
4. Spatial relationship between the player and other objects

First person 3D games are fundamentally concrete, so all of these aspects are concrete.

Features such as player health are more abstract and are injected into first person games.  (That is partially why health is usually displayed in an abstract HUD instead of within the 3D environment.)

### Mobility

* The primary activity of a first person game is moving around
* Moving around is the primary UI of a first person game
  * It is the primary form of interacting with the world
  * It is the primary form of changing what the player sees
    * In essence, moving around in a first person game is the equivalent of changing the query parameters of a report in a business application

* The primary decision that the game should reward is when and where the player moves

### Facing

* Changing facing direction is the second most primary activity of a first person game
* It does not have as big an impact as moving around, but it is still a major and foundational game element
* Turning around is the secondary UI of a first person game
  * When using abilities, it influences which way that ability is directed
    * In some cases it can also affect passive abilities, though that is not common in games
  * Turning around is a secondary form of changing what the player sees
    * If a player could only do one of two things, move around or turn around, moving around would provide a much wider variety of sights to see
      * Unless the entire traversable area of the map was a single room
  * 

## Passive Combat

### Motivation

* I've always disliked how much games relying on eliminating all threats instead of surviving them
  * When I first played DOOM I preferred playing it with respawn
  * I liked how with monster respawning each map was a roller coaster from beginning to end
  * I always felt it was anticlimactic to kill everything before beating a level
  * I used to call that design pattern the "Walk the silent corridors" syndrome
  * Over the years I've learned to appreciate the traditional FPS design a little more and how there is a certain satisfaction in eliminating all of the monsters on a level
    * It's similar to cleaning out all of the imperfections in a product, such as debugging code or refining a work of art
* While I have learned to appreciate more the elimination model, there still is gameplay value to more persistent threats
  * For that matter, persistent threats is almost an unexplored frontier in gaming—I haven't struck gold with it yet but I still suspect there are feature gold veins in that mountain
  * One of the possible opportunities I've considered is the ability to persistently weaken enemies
    * Normally weakening an enemies means less because ultimately you are trying to kill the enemy, after which any weakening is irrelevant
    * Weakening enemies also means less in elimination games because in such games enemies are usually eliminated when first encountered—it's kill or be killed
    * If the threat persists longer and potentially across multiple encounters, weakening them has more long term value
    * This is a larger issue that deserves its own section in an article somewhere, but suffice to say that there are a few challenges with this idea which have prevented me from running with it too far
      * One of the challenges is monster identity—the UX and cognitive weight of weakening individual enemies is harder when all enemies of a particular type are effectively identical
        * Weakening enemies means more when each monster has its own distinct identity, an idea I explored in the past and discarded because it creates more problems than it solves
* For years I've wrestled with not wanting to make game that are all about killing things
  * If a game is going to have violence, I would rather the violence be done to the player, not by the player

### Challenges

* The most immediate challenge to passive combat is there is little precedent for it—most of my inspirations are elimination games and I need to be careful not to think I can remove the wings and expect to still fly
  * I need to methodically analyze and enumerate the benefits of elimination in traditional FPS games
    * Benefits that I need to verify this game can live without
    * In short, I need to precisely measure the cost
    * Possibly some of the benefits can still be achieved through other means
      * Even if there is such a possibility, I still need to clearly define what it is that I am losing and what alternate method is being used to remedy that
  * When I say I have little precedent for passive combat, there are horror games which feature monstrous threats that cannot be eliminated, but those encounters are mainly for flavor and are not intended to be deep tactical challenges
  * There is also the stealth genre, though most stealth games either:
    * Still provide some option of eliminating threats
    * Are puzzle games comprised of elements that only work when featured within hand crafted scenarios

### Benefits of Elimination Style

#### Deadlier enemies

* If enemies normally don't live long after the player sees them, enemies can have attacks that would be unbearable if the player had to face them for more extended periods
* If the game places weight on the quickdraw scenario—whoever shoots first wins, then the game can have very deadly enemies that the player has to kill before the enemy can fire a shot
  * I don't like this style of gameplay and many FPS games fallback on excessive reliance on quickdraw survival, but some of it can spice up gameplay

#### Elimination as a challenge

* The act of elimination can itself be a part of the core game challenge
* Avoiding enemies can also be a challenge, but it is a *different* challenge

#### Accomplishment

* Eliminating threats provides players a certain sense of accomplishment
  * Each slain enemy is a minor achievement
* Bypassing an enemy can also provide a sense of accomplishment, but not to the same degree
  * The achievement of bypassing is more implicit
  * Bypassing is less final
  * Bypassing has less presentation compared to the visuals and audio of an enemy dying
  * Bypassing has less presentation than the corpse left behind as a monument to the player's conquest
    * Corpses in FPS games play a similar role as tokens warriors collect from fallen foes

#### Security

* In pure elimination games, eliminated threats stay eliminated
* There is a certain peace and security from not needing to worry about eliminated threats anymore
* Elimination games have a certain cycle of tension and release—Encounter threats, kill the threats, breath a sigh of relief
* That security is a double-edged sword—it does minimize the tension
* That security is not conducive to survival horror games, leading the genre to usually either avoid or downplay elimination
  * This usually falls into one of the following categories:
    * No elimination (Amnesia: The Dark Descent)
    * Limited elimination through limited ammo (Resident Evil)
    * Respawning threats (Left 4 Dead 2)
* With Marloth's current direction, that cycle still exists but more rarely—It's not until the player returns home that the player can rest easy

#### UX

* Elimination has a very clear boolean visual and cognitive model: Threats are either active or disabled
* Most forms of less permanent disabling requires more nebulous states that are harder to convey and mentally track
  * For example, a player could use an ability that slows down a target enemy.  The enemy could have a visual effect demonstrating the weakness.  That might be clear for a single negative effect, but if different effects are stacked across multiple enemies, it becomes harder to visualize and track who has what weaknesses
    * Only a single weakness ability could be used, but part of the incentive for having a variety of weakening abilities is because a single weakening ability can't compete with the versatility of death, the universal weakness
* Most FPS games still involve health, which is a nebulous state (unless enemies have visible health counters, which is neither common nor cognition friendly) but that still ultimately boils down to enemy death
  * The user story in such cases is the player repeatedly shooting at an enemy, not being entirely sure how close the enemy is to death, then witnessing the sudden resolution of the enemy dying
    * Here the nebulous state is temporary and usually promptly resolved, as opposed to passive combat where any similar states may never have a clear resolution
    * Conversely, players get annoyed when engagements against bullet sponges drag on and it is too unclear how much further damage is required to end the battle

## Surrounded by Enemies

* Possibly a part of the solution for this will be to gauge timing, where enemies are not always threats
  * The pausing monsters are a great example of this
* Another possible part of the solution is for monster quality to translate logarithmically to danger
* In one sense inversely but in another sense still along the same lines of the previous item: one possibility is to have enemies that are not much of a threat by themselves, but become a threat when composed together
  * In a way this looks like an exponential curve, except it can still be logarithmic in that the danger baseline is less than 1 and then two enemies could compose together to form a danger of 1.5.
  * In other words, if serious danger requires composition, composition becomes the primary channel for danger, and may make it easier to gate and control how the element integration translates to threats

### Notes

* This has synergy with the passive combat—it's easier to get surrounded by enemies when they are not getting eliminated

## Minimalism

* Player abilities and RPG elements add a lot to the player experience, but they are not foundational
* The primary activity of the player is moving around—that needs to be the primary interface the player uses to interact with the world, and the the primary decision that is rewarded

### Notes

* This goal is a little redundant and could be rolled into the Spatial Foundation goal except this issue is such a common stumbling block it is critical to highlight
  * Most FPS games don't live up to their potential because the designers become distracted by secondary issues and never invest in properly exploring and understanding the core issues of the problem domain

## Strategy

* Strategy is an optional goal—strategy is so hard to inject into PvE games and I've bombed so many solid game designs by chasing the strategy phantom
* At the same time, I don't want to miss opportunities where strategy could seamlessly nestle within the tactics
* However, since strategy does not naturally fit into PvE games, any strategy nestling will still require creative solutions that won't jump out on their own—I'll need to be looking for them
* In summary: "Keep an eye out for creative ways to inject strategy but don't force it."