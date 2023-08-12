---
tags: blocks/utility/redstone
---

A **computer** is a block that writes code when used. 

| Block    | Renewable | Stackable | Tool           | Blast Resistance | Hardness | Luminous | Transparent | Flammable | Creative Tab |
| -------- | --------- | --------- | -------------- | ---------------- | -------- | -------- | ----------- | --------- | ------------ |
| Computer | No        | Yes (64)  | Pickaxe (Iron) | 6                | 5        | No       | No          | No        | Redstone     | 

Can be placed only when the block above is air.

# Obtaining
## Breaking

(Times are for unenchanted tools as wielded by players with no status effects, measured in seconds.)

| Meterial    | Seconds |
| ----------- | ------- |
| None (Hand) | 25      |
| Wood        | 25      |
| Stone       | 25      |
| Iron        | 1.25    |
| Diamond     | 0.95    |
| Netherite   | 0.85    |
| Gold        | 0.65    | 

## Crafting
| Name     | Ingredients                                                                            | Crafting recipe           |
| -------- | -------------------------------------------------------------------------------------- | ------------------------- |
| Computer | Redstone, Stone Button, Heart of the Sea, Iron Ingot, Block of Redstone, Nether Quartz | [[computer_crafting.png]] |

# Usage
## Code

Using the computer will result in writing "code". There are 53 lines of code (from 0 to 52). After reaching line 53, a disc with the program will be ejected and line counter drops to 0. The disc can be played in a [Jukebox](https://minecraft.fandom.com/wiki/Jukebox).

Displayed text in chat is visible only to the player, who clicked on the computer. The text is actually simplified lyrics of the resulted disc.

### Redstone

The computer outputs a Redstone signal depending on the current line of code. Signal strength is calculated using this equation: 

$$ redStrength = ( codeLine / 52 ) * 15 $$

## Golem

Player can build "the body" for the computer for the program to "gain additional inputs" causing the resulted program to be affected by "being able to move freely". The golem is constructed by redstone ore in the middle as the core/heart, computer at the top and iron block in the remaining space.

|               |               |               |
| ------------- | ------------- | ------------- |
|               | Computer      |               |
| Block of Iron | Redstone Ore  | Block of Iron |
|               | Block of Iron |               |

# Data values
## ID

| Name     | Identifier | Form         | Translation key                         |
| -------- | ---------- | ------------ | --------------------------------------- |
| Computer | `computer` | Block & Item | `block.piseks_spidk_ii_tweaks.computer` |

# History

| Version | Change          |
| ------- | --------------- |
| 2.1     | Added Computer. | 