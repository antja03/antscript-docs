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
# 
#### EventLivingDeath
Called whenever a living entity dies.
```javascript
Pre/Post: Post
Cancellable: No

Fields:
  - int : entityId
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
# 
#### EventHudRender
Called after the hud is rendered
```javascript
Pre/Post: Both
Cancellable: No

Fields:
  - none
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
# 
#### EventScreenRender
Called when a gui is being rendered
```javascript
Pre/Post: Both
Cancellable: No

Fields:
  - none
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