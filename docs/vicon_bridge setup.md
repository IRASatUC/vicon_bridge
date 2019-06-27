# vicon_bridge setup guide
This is a brief guide to walk you through setting up vicon_bridge with [ROS](http://www.ros.org/)

## Pre-requisites
- **[Ubuntu 16.04](https://tutorials.ubuntu.com/tutorial/tutorial-install-ubuntu-desktop-1604#0)**
- **[ROS-Kinetic](http://wiki.ros.org/kinetic/Installation/Ubuntu)**

## Clone vicon_bridge Package
Open a new terminal
  ```console
  $ cd ~
  $ mkdir -p vicon_ws/src
  $ cd vicon_ws/src
  $ git clone https://github.com/IRASatUC/vicon_bridge.git
  $ cd ~/vicon_ws
  $ catkin_make
  ```
