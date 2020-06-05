# turtlebot3-slam
SLAM Algorithms for Turtlebot3

The code was modified from the original at https://github.com/ROBOTIS-GIT/turtlebot3.

## Set-Up

Follow the instructions on https://github.com/Cornell-Tech-Turtlebot/rosinstalls to run the eva-maze.rosinstall file.

## Usage

1. Run  ```export TURTLEBOT3_MODEL=waffle_pi```.

2. Once Gazebo has launched after following the instructions on https://github.com/Cornell-Tech-Turtlebot/maze-simulation 
open a second terminal and run the command: 

  ```roslaunch turtlebot3_slam turtlebot3_slam.launch slam_methods:=gmapping```

  RViz will start. After running the code in https://github.com/Cornell-Tech-Turtlebot/turtlebot3-simulations/tree/eva RViz
  will show the resulting map. To save the map, run the following command on a separate window:
  
  ```rosrun map_server map_saver -f ~/map  ```r
  
## Demo

A demo video together with the resulting SLAM map can be found in https://github.com/Cornell-Tech-Turtlebot/turtlebot3-simulations/tree/eva.
