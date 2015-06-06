# State Synchronization Demo

In light of what I've learned since I made the [snapshot interpolation demo](https://github.com/jrimclean/godot-snapshot-interpolation-demo), I have decided to write a new demo for [Godot](http://www.godotengine.org) illustrating a technique called state synchronization.

Both the client and the server run the physical simulation. State snapshots are sent from the server to the client at an adjustable rate. With each update, the physical state on the client is snapped to the new state.

To start a dedicated server with the headless version of Godot type, "godotserver -server" in the project directory.

## Todo:
* Separate sprite state from physics state and use gradual error correction

## License
Copyright (c) 2015 James McLean  
Licensed under the MIT license.