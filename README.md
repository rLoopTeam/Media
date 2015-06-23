

# Files

## `hyperloop/`
### `scene.blend`

Contains all the environment settings for lighting. To use:

1. Link (File > Link) the  `environment` group; it contains a sun light and the ground. Move it up and down to the right place.
2. Link the `hyperloop world` World and set it as the current world (World settings > the globe icon dropdown)

### `materials.blend`

Contains all the materials used (so all materials look the same).

* `clay` is the basic white material used on the road, the cars, etc.
* `hyperloop` is the blue material used for the pylons.
* `hyperloop tube` is the same as `hyperloop`; however, if it's enabled (connect the bottom mix shader to the output surface node), it will turn to glass and then fully invisible as you approach it.

### `car.blend`

Contains an SUV, a sedan, and a tractor-trailer. Intended to be used as a basic, low-res prop.

### `pylon.blend`

Contains the `pylon` group. During 3d editing, a very low-poly version is displayed instead.

### `tube.blend`

Contains the `tube segment` and the `tube segment connection` groups.

### `section.blend`

Contains the `section` group, which is a long chain of pylons and tubes.

### `pod.blend`

Contains the `pod` group. Must be moved vertically to fit properly in the tube.

### `composite.blend`

The hyperloop tube with pylons and a road with cars. To use:

1. `animation camera` is the camera that starts a bit to one side and flies into the tube.
2. `long range camera` is the long-range (tiltshift) camera.
3. `side camera` to get the "glass angled" shot (be sure to enable glass in `materials.blend`

