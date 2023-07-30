# Spatial

## Nested State

### Problems

* Nested state has inherent UI/UX problems
* Nested state is problematic in abstract UIs
* Nested state is even more problematic for 2D spatial UIs
* Nested state is even, even more problematic in first person 3D spatial UIs where element distance can vary and player view can be obstructed

## Solution

> Note: This solution is accidentally applied far more than people realize

* Keep actor state simple
* What would normally be nested state is instead represented as separate actors
  * These actors can be treated as loosely-coupled children of the root actor
* Unlike a nested state UI, the secondary actor approach cleanly integrates with the spatial world and other actors, both visually and in simulation interactions
* 

## Requirements

* Most or all state is visually represented in 3D space
* Most or all state changes are visually represented in 3D space
* At least some of the visuals feel creative, as though the player is creating a work of art by causing certain effects
* Atomic, modal actors
