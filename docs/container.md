## Prefix
container.*

## Functions
#### isInContainer() (boolean)
Returns whether or not a container is open
#### getType() (int)
Returns the current containers type
```
Container types
------------------
Chest: 0
Enchantment: 1
Hopper: 2
Merchant: 3
Repair: 4
Beacon: 5
Brewing: 6
Crafting: 7
Dispenser: 8
Furnace: 9
Horse Inventory: 10
Inventory: 11
```
#### getWindowId() (int)
Returns the current container id (-1 if not in a container)
#### getChestName() (String)
Returns the name of the current chest (empty string if the container isn't a chest)
#### getChestDisplayName() (String)
Returns the display name of the current chest (empty string if the container isn't a chest)
#### getSize() (int)
Returns the total number of slots in the current container (-1 if not in a container)
#### getStackInSlot(slot) ([ItemStack](./classes/ItemStack.md))
Returns the stack in the specified slot (null if not in a container)
#### clickSlot(slot, mouseButton, clickType) (void)
Clicks a slot in the current container
```
Mouse Button
--------------
Left: 0
Right: 1

Click type
--------------
Pickup : 0
Quick move: 1
Swap: 2
Clone: 4
Throw: 5
Quick craft: 6
Pickup all: 7
```

