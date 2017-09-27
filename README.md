# eYRC-Navigate-A-Terrain
A leader-follower system for the theme Navigate a Terrain, where a rover would find its way through a 250x250cm maze. 

Used:
1. openCV and numpy to process the maze image and find the path on laptop
2. nodeMCU and esp8266 on the base station in the centre to control the laser that was guiding the rover through the maze
3. Raspberry Pi controls the rover

It is a closed loop problem which requires constant communication so the laptop, nodeMCU and Raspberry Pi communicate with each other using TCP IP socket programming.
