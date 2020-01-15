# RobotCraft_2019
Work done during RobotCraft 2019 internship

These packags contain basic framework to solve a simple wall maze with the RobotCraft robot (powered by Arduino Mega 2560
and Raspberry Pi 3) in simulator and in the real world.

## Submodule desctiptions
### robotcraft_maze
solves the maze using wall following algorithm, runs in the Stage Simulator.

### robotcraft_maze_pro 
solves the maze using wave propagation algorithm to compute the shortest path, uses wheel odometry for localization, runs in the Stage Simulator.

### robotcraft_maze_pro_real_amcl
solves the maze using wave propagation algorithm to compute the shortest path, uses 2D RPlidar for localization, runs in on the robot (Raspberry Pi 3).

### controllMT
motor control package, runs on Arduino Mega 2560, intefaces with Raspberry Pi 3 using rosserial package.

