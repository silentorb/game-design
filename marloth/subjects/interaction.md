# Interaction

## Traditional

### Definition

* Traditional RPG environment interaction involves:
  * The player activating an interaction command with a preconfigured interactable element in the game world
  * Any interaction more elaborate than opening a door or pulling a lever involves a modal UI view

### Problems

> Note: some of these problems only apply to complex interactions, but simple interactions don't scale well and need the option of falling back on complex interactions.  Very few RPGs have been created that only allow simple interactions.  (Even the lightweight Diablo series still features dialog windows and shop screens.)

* Is non-composable, either in terms of input (commands) or output (effects)
  * A single interaction command either does a single completely different thing for each interactable item, or branches into multiple options through a UI dialog
  * This is a brittle design and has been stretched to the snapping point by most advanced RPGs
* Is abstract
  * Traditional RPG interactions exist outside of the spatial system
  * This overlaps with the lack of composition
* Only supports PC-to-NPC (or non-player actor)
  * In general, RPG environment interactions are rarely player-to-player or NPC-to-NPC
  * This limitation has been tripping up any attempts to make Marloth more of a simulation that has a life apart from the player
* Has no observable effect
  * This overlaps with being abstract
  * If two other characters were to engage in dialog, the player could watch but normally would not be able see any meaningful information about what is happening
  * Some games will have audio or floating text for dialog not involving the player, but that approach is brittle and doesn't scale well
    * Usually this is only used during scripted events or for ambience
    * Even then, I've only ever seen that for dialog, nothing else
      * For example, I've never seen a float UI for an NCP browsing the wares of a shopkeeper
* Only supports two actors
  * Some games will have scripted dialog between more than two characters
    * That is uncommon
  * 