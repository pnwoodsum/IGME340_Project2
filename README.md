# IGME340_Project2
A simple ARPG game for IPad/IPhone developed in X-Code using Swift 4

Controls
  - Tap on the left side of the screen and drag to move character
    - Virtual joystick will be centered where the tap is initially placed.

Prototype 1:
  - Has a virtual joy stick to move the character.
  - Uses the spritekit camera to change move around a map (made of a single image)

![alt text](https://github.com/pnwoodsum/IGME340_Project2/blob/master/Prototype1/p1_screenshot.png)

Going forward:
  - Tiling map.
  - Character progress (experience through collectibles?)
  - Save Data on close
  - More from initial game doc...


Prototype 2:
  - Implemented infinitely generating tile map
  - Added several helper functions and a swift file to hold game variables
  
![alt text](https://github.com/pnwoodsum/IGME340_Project2/blob/master/Prototype2/Screen%20Shot%202018-04-16%20at%2011.52.40%20PM.png)

Going forward:
  - Character progress
  - Save and load data
  - Optimize map loading/unloading
  - Simple enemies and combat
  - Sounds
  - Art

Development Update 4/29/18
 - The map is now generated procedurally using a perlin noise map based on a seed
 - Collisions with non-pathable tiles (rocks)
 - Animated gold coin collectibles that add to a counter when collected
 - Updated joy stick so initial position changes with large movements
 
![alt text]()
