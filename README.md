# MG4
## Devlog Prompt
1.The FloatAnimation script begins by assigning the value of the _switchSpeed variable to _timer within the Start() method, 3.0f by default. The FloatAnimation script then utilizes the Update() method every frame to check if the _up variable is returning true or not. If the _up variable is returning true the FloatAnimation script will perform a positive translation upwards on the fish food gameObject by changing the value of the fish food gameObject’s 
y-axis position during each frame using the formula _moveSpeed * Time.deltaTime. The upwards translation occurs until the _timer variable is less than or equal to 0.0f. Once the _timer variable reaches that point the _timer variable is reassigned the _switchSpeed value to reset the cycle. The _up variable is also assigned the opposite of its value using the ! operator. Changing the _up value to “false” begins a negative translation downwards using the formula  -_moveSpeed * Time.deltaTime. This process continues until the _timer value is less than or equal to 0.0f again, during which the _up variable is assigned the value “true” to begin another positive translation within the cycle.

## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [City 3D models](https://assetstore.unity.com/packages/3d/environments/simplepoly-city-low-poly-assets-58899)
- [Bite sound effect](https://freesound.org/people/Jofae/sounds/353067/)
