# Stealth

## Problems

### Boolean

* The main problem with stealth systems is they are boolean: either the player is seen or he isn't
* Stealth games usually fudge this to some degree, most commonly by giving AI a middle state where they have partially detected the player but will move on if they don't receive confirmation
  * While I don't think this is a bad mechanic, I personally don't enjoy it whenever I am partially spotted—it feels like I failed but was still given a pass
* The main problem with stealth being boolean is there is no numeric integration

## Solutions

### Numeric Integration

* Traditional game combat has a better foundation than traditional stealth systems, where combat relies on health resources and numeric damage
* In such cases, damage is accumulated, allowing multiple damage sources to be integrated through their influence on health
* Perhaps a similar numeric integration system could be applied to stealth?
* Proposal:
  * Player characters have a `Stealth` meter
  * Whenever a player is seen by AI character's, the player's `Stealth` meter is drained
  * As long as a player's `Stealth` meter is greater than zero, AI players don't react to the player
  * `Stealth` does not regenerate but is a resource that must be acquired