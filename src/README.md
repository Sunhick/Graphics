The program has two modes of execution -

1. **EXPLORE MODE:** which provides a first person navigation in the scene.

2. **DRIVE MODE:** where the user can move the truck around the scene on the road. When the user 
drives off the road, it will be indicated by a text in the lower bottom corner. The status messages includes "On road", "Off road", "Hit by a truck", "Hit by a house" and "Hit by a tree".  The user can drive the truck front, back, steer left and right.

---

Compile:    make
Executable: ./final


## KEY BINDINGS:

| Key   |           Description |
|---------|----------------------|
|0     |          Reset the view / game (DRIVE MODE)|
|X  |             Look down at x-axis|
|Y   |            Look down at y-axis|
|Z    |           Look down at z-axis|
|m  |             Switch between different modes (EXPLORE MODE- first person navigation, DRIVE MODE - drive the truck around the scene with collision detection enabled) |
|s |				Toggle lighting(Enable/disable)|
|+  |             Increase field of view|
|-|               Decrease field of view|
|A  |             Toggle axes visibility|
|Arrow keys |     To look left, right, up and down (EXPLORE MODE)|
|f  |             Move forward into the scene (EXPLORE MODE)|
|b  |             Move backward away from the scene (EXPLORE MODE)|
|w 	|			Increase the speed of the truck / steer forward (DRIVE MODE)|
|z 	|			Decrease the speed of the truck / steer backward(DRIVE MODE)|
|a 	|			Steer left (DRIVE MODE)|
|d | 				Steer right (DRIVE MODE)|
|space | 			Hand brake|
|ESC     |        Quit application|
---

PROUD OF:

1. Scene composition (16 block x 16 block). There are 128 houses and 128 apartment, 256 trees and 256 traffic signs and a windmill. All object are enabled for collision detection except for windmill.
2. Movement of the truck with sound effects esp squealing of the wheel when a hard left/right turn is made.
3. Animation of truck when it hits objects in the scene.
4. Sounds effects.
