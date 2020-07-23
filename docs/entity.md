## Prefix
.*

## Examples
#### Loop through entity list
```javascript
var entityList = world.getLivingEntities();
for (var i = 0; i < entityList.size(); i++) {
    var entityId = entityList.get(i);
    //use functions documented below
}
```

## Functions
#### isLiving(id) (boolean)
Returns whether or not the entity is a living entity
#### isPlayer(id) (boolean)
Returns whether or not the entity is a player
#### isLocalPlayer(id) (boolean)
Returns whether or not the entity is the local player
#### getName(id) (String)
Returns the entities name
#### getDisplayName(id) (String)
Returns the entities displayname
#### getHealth(id) (int)
Returns the entities health
#### getArmor(id) (int)
Returns the entities armor
#### getEyeHeight(id) (double)
Returns the entities eye height
#### getPosition(id) ([Vector3d](./classes/Vector3d.md))
Returns the entities position
#### getLastPosition(id) ([Vector3d](./classes/Vector3d.md))
Returns the entities last tick position
#### getPositionDelta(id) ([Vector3d](./classes/Vector3d.md))
Returns the difference between the entities current tick position and last tick position
#### getEyePosition(id) ([Vector3d](./classes/Vector3d.md))
Retismt je entities eye position 
#### getMotion(id) ([Vector3d](./classes/Vector3d.md))
Returns the entities motion
#### getBoundingBox(id) ([BoundingBox](./classes/BoundingBox.md))
Returns the entities bounding box
#### getCollisionBoundingBox(id) ([BoundingBox](./classes/BoundingBox.md))
Returns the entities collision box
#### getDistanceFromPlayer(id) (double)
Returns the entities distance from the local player
#### isInvisible(id) (boolean)
Returns whether or not the entity is invisible
#### isInvisibleToPlayer(id) (boolean)
Returns whether or not the entity is invisible to only the local player
#### isInvulnerable(id) (boolean)
Returns whether or not the entity is invulnerable
#### isAlive(id) (boolean)
Returns whether or not the entity is alive
#### canBeSeen(id) (boolean)
Returns whether or not the entity is behind blocks and cannot be seen by the local player
#### predictPlayerPosition(id, ticks) ([Vector3d](./classes/Vector3d.md))
Predicts and returns the entities position after a certain amount of ticks
#### rayCast(id, distance, yaw, pitch) (boolean)
Returs whether or not the local player would be looking at an entity with a yaw and pitch
