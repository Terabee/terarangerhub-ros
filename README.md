# DEPRECATION warning

This package will not be supported in the future. To get the latest updates please use [teraranger_array package](https://github.com/Terabee/teraranger_array) with teraranger_one node.

TeraRanger Hub ROS Module
=========================

This is the ROS module for the TeraRanger Hub ranging sensor (www.teraranger.com).


Using module
============

To use the ROS node you just need to:
* Create a ROS Workspace
* Copy the node teraranger_hub package into the workspace src directory
* Compile using: catkin_make 
* Setup environment: source devel/setup.sh
* Run using: rosrun teraranger_hub teraranger_hub_node _portname:=/dev/ttyACM0

If you want to change the operating mode, run
* rosrun rqt_reconfigure rqt_reconfigure 

NB: remember to execute the daemon roscore before running the rosrun command
