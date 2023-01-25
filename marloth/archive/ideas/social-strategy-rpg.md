# Social Strategy RPG

## Problems

* How to make a game revolving around dialog choices where:
  * Choices matter
  * Losing is measurable/numeric
  * State and options are generalized (as opposed to being a graph of specialized logic)
  * The player is well-informed (not just guessing at what will happen when certain dialog options are selected)
  * Strategy is rewarded

## Solutions

### Choices Matter

* Every choice needs a price
  * Maybe most choices need composite prices
* Most prices should be communicated to the player
  * Maybe all prices should be communicated to the player
* Price communication should be communicated both at the moment of decision and in the future
* In most cases, price should be more than just opportunity cost
  * In other words, minimize choices that are purely beneficial where the only challenge of the choice is that the options are mutually exclusive
    * This would mean having cases where the player would rather not choose any of the provided options
    * It's like a game of "Would you rather"

### Measurable Loss

* Quantifiable
* Users can see reports of how close they are to losing
* Fungible integration
* Like when your HP reaches zero in combat)
* Not every aspect of losing has to be quantifiable, but its helpful to have some foundational metrics

### Player Information

* The player needs to have more social information available than RPGs normally provide
* Maybe a UI view of the character's mind, containing multiple tabs and many reports
* The player should see primarily current state
  * But also some historical data
  * And possibly even some projections of potential future data
* Maybe the views available would be related to the character's attributes
  * Characters with better memory will see more historical data
    * And immediate data as well (memory is required for current data)
  * Characters with a more strategic intellect will be able to generate projection reports
  * Maybe the character could be an unreliable witness in some cases, and the player will not be sure how far to trust the character's mind
  * I don't know about this though—seems like it would add unpleasant tension where players would be incentivized to invest in other character strengths and take notes, but that's not fun for most people (wouldn't be fun for me)

## Getting Started

* Start with a hand-crafted scenario that is not random
  * Instead of switching to everything being randomly generated, randomness can be gradually inserted into the flow
* What's the simplest form of this game to begin with?
  * From common CRPG dialog options, select a few dialog actions that:
    * Can be used a lot
    * Have both pros and cons for the player
* What if the game engine maintained a decision graph under the hood?
  * Is that possible?
  * As randomness was introduced, it would be tied to and validated by the graph
  * The graph may not need to be comprehensive, just fleshed out enough to cover most cases
    * There could be fringe cases where the player could bypass the graph (solve problems in ways the graph is not considering) as long as those cases weren't extreme and didn't break the gameplay
* 