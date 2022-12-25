# roboboat_ws_23
Code Repository for InspireNC's Roboboat team

# TODO
- Create controls package
- Implement interface to PX4
- Create CV package

# Installation/Setup
- Running ROS Melodic on Ubuntu 18.04 onboard Jetson TX1
- Simulink model `saildrone.slx` contains software to be deployed on PX4 board.


To install ROS Melodic, follow instructions from the [ROS Installation Guide](http://wiki.ros.org/melodic/Installation/Ubuntu)

Clone workspace and build using `catkin_make`.

# ROS Package Descriptions
## robot_bringup
Contains launch files for each process.

## robot_msgs
Contains custom message definitions.

