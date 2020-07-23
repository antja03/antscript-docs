## Prefix
player.*

## Functions
#### getEntityId() (int)
Returns the local players entity id
#### getName() (String)
Returns the local players ingame name
#### getPosition() ([Vector3d](./classes/Vector3d.md))
Returns the local players position
#### getEyePosition() ([Vector3d](./classes/Vector3d.md))
Returns the local players eye position
#### setPosition(x, y, z) (void)
Sets the players position
#### getMotion() ([Vector3d](./classes/Vector3d.md))
Returns the local players motion
#### setMotion(x, y, z) (void)
Sets the local players motion
#### getRotations() ([Vector2f](./classes/Vector2f.md))
Returns the local players pitch and yaw
#### getRotationsToPosition(x, y, z) ([Vector2f](./classes/Vector2f.md))
Returns the required pitch and yaw for the local player to be looking at a position
#### getRotationsToPositionFromPosition(toX, toY, toZ, fromX, fromY, fromZ) ([Vector2f](./classes/Vector2f.md))
Returns the required pitch and yaw for the local player to be looking at a position from a position
#### setRotations(yaw, pitch)
Sets the local players pitch and yaw
#### leftClick() (void)
Left clicks the mouse
#### rightClick() (void)
Right clicks the mouse
#### getHotbarSlot() (int)
Returns the current selected hotbar slot
#### setHotbarSlot(slot) (void)
Sets the current selected hotbar slot. Slot index must be from 0-8
#### sendMessage(message) (void)
Sends a message in chat
#### openInventory() (void)
Opens the local players inventory
#### isInInventory() (boolean)
Returns whether or not the local players inventory is open