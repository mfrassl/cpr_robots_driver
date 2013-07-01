cpr_robots_driver
=================

ROS stack to drive the CPR robots Slider and Mover4, packages cpr_robots_hwinterface and cpr_robots_teleop 
BSD license.


Current Version
-----------------
* July 1st, 2013	   - Debugging, limiting the cartesian acceleration
* June 31st, 2013    - Update, better CAN message check, aligning CAN ids, debugging 
* January 21st, 2013 - Set up

Usage
-----------------
roslaunch teleopSlider.launch in cpr_robots_teleop
See the doc directory

Scope
-----------------
This repository contains ROS packages to move the robot arm Mover4 and the mobile platform Slider, see www.cpr-robots.com

Package cpr_robots_teleop
-----------------
This package reads the keyboard and publishes twist messages with the cartesian velocities for the slider.

Package cpr_robots_hwinterface
-----------------
This package contains the inverse kinematics and the hardware interface to move the real robot according to the twist messages.

