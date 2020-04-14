# PalletizingCubesGazebo
Demoing using fetch robot to palletize cubes using Fetch Robot in Gazebo environment


*Requirement:*
-Ubuntu 18.04
-ROS-melodic


Clone this repo in catkin_ws, and install
```
cd ~/catkin_ws/src
git clone https://github.com/AustinJia/PalletizingCubesGazebo.git
cd ~/catkin_ws
catkin_make
source ~/catkin_ws/devel/setup.bash
```

Example code to run manipulation stack
```
roslaunch fetch_gazebo pickplace_playground.launch
roslaunch fetch_gazebo_demo pick_place_demo.launch
```

Example code to run mobile manipulation
```
roslaunch fetch_gazebo playground.launch
roslaunch fetch_gazebo_demo demo.launch
```

Fetch Robot Gazebo github: https://github.com/fetchrobotics/fetch_gazebo

