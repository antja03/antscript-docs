## Overview
An extensive but easy to use JavaScript API for Minecraft 1.12.2. Currently only featured in Oreo Client ([link](https://oreo.software)) made by anthonyj, Trol and tubz. In order to take full advantage of OreoScript, you should already have a decent understanding of Minecraft and its codebase. 

## Script data
In order for your script to be properly loaded, you need to have an object named data. It must include the name of your script, a brief description and, optionally, the name of your main function.

```javascript
var data = {
	name: "My script",
	description: "Gives you superpowers!",
	main: "main"
}

//Ran when the script is loaded (not toggled)
function main() {

}
```

## Event callbacks
There are several events that you can take advantage of within OreoScript. This is done by defining a function with the corresponding name. A more detailed explanation, as well as a list of all existing events can be found [here](events.md).

```javascript
//Called when the heads up display is rendered
function onHudRender(event) {

}

//Called both before and after the local player updates
function onPlayerUpdate(event) {

}
```