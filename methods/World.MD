
# World
**Explanation for every world method available in the ZarScript scripting language**
Access the following methods by doing **world.** and then the following method's name.
## getWorldEntities()
Updates all the entities and returns all the id's for them, you can't use any of the functions bellow before calling this function.
**Returns an array of integers**

**Usage:**
```js
let entities = world.getWorldEntities();
var index = 0;
for(index = 0; index < entities.length; index++) {
	let entity = entities[index];
	// use functions documented below
} 
```
## getEntityHurttime(id)
Hurttime is a number which describes the current player's invulnerability to an another attack, 0 meaning the entity is able receive damage [in ticks]
## getEntityBoundingBox(id)
Returns an array of doubles, which provides the entity bounding box.
[minX, minY, minZ, maxX, maxY, maxZ] (from 0 to 5)
## getEntityPositions(id)
Returns an array of doubles which contain the entity's locations
[posX, posY, posZ] (from 0 to 3]
**getEntityPositions(id)[0]** to access a specific value
## getEntityRotations(id)
Returns an array of floats which contain the entity's rotations
[yaw, pitch] (from 0 to 1]
**getEntityRotations(id)[0]** to access a specific value 
## getEntityDisplayName(id)
Returns players name with color codes
## getEntityName(id)
Returns players name without color codes
## isPlayer(id)
Returns a true/false value if the entity is a player
## getEntityHeldItemName(id)
Returns entity's currently held item's name


