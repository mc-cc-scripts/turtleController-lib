# turtleController-lib

Library for basic turtle-controls

Refuels automaticly, if any fuel blocks are in the Inventory

---

## Main Functions

---

### find a item in the turtle-inventory

`turtleController:findItemInInventory(<table>|<string>): number`

Example

```lua
local coalSlot = turtleController:findItemInInventory('minecraft:charcoal')
```

### Turtle Movement

`function turtleController:tryMove(<string>): boolean`

Example: Going in a cirle

```lua
local success = turtleController:compactMove('f4, u2, b4, d2')
```

---

## Important things to know

---

Feel free to override the current default settings:

```lua
turtleController.freeRefuelSlot = true
turtleController.refuelSlot = 1
turtleController.canBreakBlocks = false
```
