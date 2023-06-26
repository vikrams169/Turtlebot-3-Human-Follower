This repository enables a Turtlebot 3 burger robot to follow a human around in an obstacle-ridden environment. The package uses a Kalman Filter for linear velocity control and a weighted-average-based angular velocity variation technique. Check the 'follower' node of the package for more implementation details. This package is tested and is sure to run in ROS Noetic, but can work in other earlier ROS 1 versions too, by running the appropriate commands to SSH into the Turtlebot.<br><br>

To run the package and enable the Turtlebot to start following (the human initially placed right in front of it), execute the following commands.<br><br>
#### Terminal 1
	[Remote PC] roscore
#### Terminal 2
	[Remote PC] ssh {Name of the Turtlebot}@{IP Address of the Turtlebot}	
	[Turtlebot3] export TURTLEBOT3_MODEL=burger		
	[Turtlebot3] roslaunch turtlebot3_bringup turtlebot3_robot.launch
#### Terminal 3
	[Remote PC] export TURTLEBOT3_MODEL=burger	
	[Remote PC] roslaunch turtlebot3_follow_filter turtlebot3_follow_filter.launch
#### Terminal 4
	[Remote PC] roslaunch turtlebot3_follower turtlebot3_follower.launch
	
# TurtleBot3
<img src="https://github.com/ROBOTIS-GIT/emanual/blob/master/assets/images/platform/turtlebot3/logo_turtlebot3.png" width="300">

## ROS Packages for TurtleBot3 Applications
|Version|Kinetic + Ubuntu Xenial|Melodic + Ubuntu Bionic|
|:---:|:---:|:---:|
|[![GitHub version](https://badge.fury.io/gh/ROBOTIS-GIT%2Fturtlebot3_applications.svg)](https://badge.fury.io/gh/ROBOTIS-GIT%2Fturtlebot3_applications)|[![Build Status](https://travis-ci.org/ROBOTIS-GIT/turtlebot3_applications.svg?branch=kinetic-devel)](https://travis-ci.org/ROBOTIS-GIT/turtlebot3_applications)|[![Build Status](https://travis-ci.org/ROBOTIS-GIT/turtlebot3_applications.svg?branch=melodic-devel)](https://travis-ci.org/ROBOTIS-GIT/turtlebot3_applications)|

## ROBOTIS e-Manual for TurtleBot3
- [ROBOTIS e-Manual for TurtleBot3](http://turtlebot3.robotis.com/)

## Wiki for turtlebot3_applications Packages
- http://wiki.ros.org/turtlebot3_applications (metapackage)
- http://wiki.ros.org/turtlebot3_automatic_parking
- http://wiki.ros.org/turtlebot3_automatic_parking_vision
- http://wiki.ros.org/turtlebot3_follow_filter
- http://wiki.ros.org/turtlebot3_follower
- http://wiki.ros.org/turtlebot3_panorama

## Open Source related to TurtleBot3
- [turtlebot3](https://github.com/ROBOTIS-GIT/turtlebot3)
- [turtlebot3_msgs](https://github.com/ROBOTIS-GIT/turtlebot3_msgs)
- [turtlebot3_simulations](https://github.com/ROBOTIS-GIT/turtlebot3_simulations)
- [turtlebot3_applications_msgs](https://github.com/ROBOTIS-GIT/turtlebot3_applications_msgs)
- [turtlebot3_applications](https://github.com/ROBOTIS-GIT/turtlebot3_applications)
- [turtlebot3_autorace](https://github.com/ROBOTIS-GIT/turtlebot3_autorace)
- [turtlebot3_deliver](https://github.com/ROBOTIS-GIT/turtlebot3_deliver)
- [hls_lfcd_lds_driver](https://github.com/ROBOTIS-GIT/hls_lfcd_lds_driver)
- [robotis_manipulator](https://github.com/ROBOTIS-GIT/robotis_manipulator)
- [open_manipulator_msgs](https://github.com/ROBOTIS-GIT/open_manipulator_msgs)
- [open_manipulator](https://github.com/ROBOTIS-GIT/open_manipulator)
- [open_manipulator_simulations](https://github.com/ROBOTIS-GIT/open_manipulator_simulations)
- [open_manipulator_perceptions](https://github.com/ROBOTIS-GIT/open_manipulator_perceptions)
- [open_manipulator_with_tb3_msgs](https://github.com/ROBOTIS-GIT/open_manipulator_with_tb3_msgs)
- [open_manipulator_with_tb3](https://github.com/ROBOTIS-GIT/open_manipulator_with_tb3)
- [open_manipulator_with_tb3_simulations](https://github.com/ROBOTIS-GIT/open_manipulator_with_tb3_simulations)
- [dynamixel_sdk](https://github.com/ROBOTIS-GIT/DynamixelSDK)
- [dynamixel_workbench](https://github.com/ROBOTIS-GIT/dynamixel-workbench)
- [OpenCR-Hardware](https://github.com/ROBOTIS-GIT/OpenCR-Hardware)
- [OpenCR](https://github.com/ROBOTIS-GIT/OpenCR)

## Documents and Videos related to TurtleBot3
- [ROBOTIS e-Manual for TurtleBot3](http://turtlebot3.robotis.com/)
- [ROBOTIS e-Manual for OpenManipulator](http://emanual.robotis.com/docs/en/platform/openmanipulator/)
- [ROBOTIS e-Manual for Dynamixel SDK](http://emanual.robotis.com/docs/en/software/dynamixel/dynamixel_sdk/overview/)
- [ROBOTIS e-Manual for Dynamixel Workbench](http://emanual.robotis.com/docs/en/software/dynamixel/dynamixel_workbench/)
- [Website for TurtleBot Series](http://www.turtlebot.com/)
- [e-Book for TurtleBot3](https://community.robotsource.org/t/download-the-ros-robot-programming-book-for-free/51/)
- [Videos for TurtleBot3 ](https://www.youtube.com/playlist?list=PLRG6WP3c31_XI3wlvHlx2Mp8BYqgqDURU)
