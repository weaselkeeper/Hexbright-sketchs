Hexbright-sketchs
=================

Sketches for the hexbright arduino compatible flashlight.
Modified from example sketches from hexbright community.

hexbright_cascade_down.ino
	1st click, Max power, 500+ Lumens
	2nd click, ultra low mode, about 5 lumens
	3rd click, a bit less bright, around 120 Lumens
	4th click, low power, roughly 15 Lumens
	5th click, back to Max power
	Press and hold in any mode, poweroff.

	Press and hold when off, blinking.

hexbright_tilt.ino
	Short press changes mode.
	Short press when pointed up, medium
	Short press when pointed down, very low
	Short press with light held horizontal, high

	long press when pointed up turns off.
	long press when pointed down, firefly mode
	long press when pointed forward, blinking.
	
	
	Enable DEBUG to see debug statements in serial console

hexbright_cascade.ino
	Stock firmware, start low, each click increases intensity until 4th
	click turns off.

hexbright_4step.ino
	Reversal of stock firmware.  Starts bright, each click lowering the
	intensity until the 4th click of the button turns off the light. 
