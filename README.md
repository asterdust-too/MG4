# MG4
## Devlog
### Prompt Answer

  FloatAnimation starts with declaring all of the different variables used in the script, such as declaring the _moveSpeed and the _switchSpeed, an "up" boolean, and the timer. In Start(), the code makes the timer equal the switchSpeed, and Update(), sets the boundaries of where it moves by making it move up on the y-axis over the amount of time set up by switchSpeed. If _up is true, then it moves. If _up is false, it moves down in the same direction, and the same length. The switch is determined by when _timer runs out of the time specified by _switchSpeed, since they equal each other.

### Process
- Added several spheres named 'Pellet' around the scene
- Gave spheres different tags based on what function I wanted them to ask the player to do (Add, Subtract, Multiply)
- Made fish move backwards with "S" key and Down Arrow, and added "Q" and "E" as up and down.
- Made pellets give you Correct answers based on player input.

## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [City 3D models](https://assetstore.unity.com/packages/3d/environments/simplepoly-city-low-poly-assets-58899)
- [Bite sound effect](https://freesound.org/people/Jofae/sounds/353067/)
