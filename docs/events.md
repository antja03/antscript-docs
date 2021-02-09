#### Event
Everything contained in Event exists for all other events.
```javascript
Methods:
  - getContext() : Returns an EventContext
  - getContextId() : Returns 0 (pre) or 1 (post)
  - isCancelled() : Returns whether or not the event is cancelled
  - setCancelled(boolean) : Sets whether or not the event is cancelled
```
# 
#### EventPlayerUpdate

Called before and after the local player updates.
```javascript
Pre/Post: Both
Cancellable: No

Fields:
  - double : posX
  - double : posY
  - double : posZ
  - double : motX
  - double : motY
  - double : motZ
  - float : rotYaw
  - float : rotPitch
  - boolean : sneaking
  - boolean : sprinting
  - boolean : ground
```

<font color="#1e3c96">**Example**</font>

```javascript
function onLocalPlayerUpdate(event) {
  game.printToChat("this is an example")
}
```

# 
#### EventLivingDeath
Called whenever a living entity dies.
```javascript
Pre/Post: Post
Cancellable: No

Fields:
  - int : entityId
```

<font color="#1e3c96">**Example**</font>

```javascript
function onEntityDeath(event) {
  game.printToChat("this is an example")
}
```

# 
#### EventKeyPress
Called whenever a key is pressed in-game
```javascript
Pre/Post: Pre
Cancellable: Yes

Fields:
  - int: keyCode
```

<font color="#1e3c96">**Example**</font>

```javascript
function onIngameKeyPress(event) {
  game.printToChat("this is an example")
}
```

# 
#### EventMouseInput
Called whenever a mouse button is clicked or released in-game
```javascript
Pre/Post: Pre
Cancellable: Yes

Fields:
  - int : mouseState
  - int : mouseButton
```

<font color="#1e3c96">**Example**</font>

```javascript
function onIngameMouseInput(event) {
  game.printToChat("this is an example")
}
```

# 
#### EventHudRender
Called after the hud is rendered
```javascript
Pre/Post: Both
Cancellable: No

Fields:
  - none
```

<font color="#1e3c96">**Example**</font>

```javascript
function onIngameRender(event) {
  game.printToChat("this is an example")
}
```

# 
#### EventScreenKeyPress
Called whenever a key is pressed in a gui
```javascript
Pre/Post: Pre
Cancellable: Yes

Fields:
  - int: keyCode
```

<font color="#1e3c96">**Example**</font>

```javascript
function onScreenKeyPress(event) {
  game.printToChat("this is an example")
}
```

# 
#### EventScreenMouseInput
Called whenever a mouse button is clicked or released in a gui
```javascript
Pre/Post: Pre
Cancellable: Yes

Fields:
  - int : mouseState
  - int : mouseButton
```

<font color="#1e3c96">**Example**</font>

```javascript
function onScreenMouseInput(event) {
  game.printToChat("this is an example")
}
```

# 
#### EventScreenRender
Called when a gui is being rendered
```javascript
Pre/Post: Both
Cancellable: No

Fields:
  - none
```

<font color="#1e3c96">**Example**</font>

```javascript
function onScreenRender(event) {
  game.printToChat("this is an example")
}
```

#
#### EventWorldRender
Called after entites are rendered
```javascript
Pre/Post: Post
Cancellable: No

Fields:
  - none
```

<font color="#1e3c96">**Example**</font>

```javascript
function onWorldRender(event) {
  game.printToChat("this is an example")
}
```