# Robotic Systems Setup Guides

Compilation of guides I've created and regularly reference when setting up robotic projects in Linux.

* [ROS Noetic on Raspberry Pi 3B+](tutorials/focal-ros-docker/focal-ros-docker.md)
    * Setup guide to install Ubuntu Focal (20.04 Server) and ROS Noetic on a Raspberry Pi 3B+.
  
* [Static IP setup](tutorials/static-ip-setup/static-ip-setup.md)
    * Set static IP addresses, important for ROS networking and time synchronization between multiple SBCs (single board computer).
  
* [Time synchronization](tutorials/chrony-setup/chrony-setup.md)
    * Set up chrony to sync clocks between multiple linux computers, this is particularly useful for robotic systems with no internet connection. 

* [ROS Package Git](tutorials/ros-package-git/ros-package-git.md)
    * Quick guide to creating a new ROS package and connecting it to a github repository for version control.

* [Local Git setup](tutorials/local-git/local-git.md)
    * Use Git to push/pull code between a robot, laptop, and Github, where the robot has no internet connection and the laptop acts as a bridge.
  
* [UDEV rules](tutorials/udev-setup/udev-setup.md)
    * How to set static mapping for USB / serial ports in Ubuntu using UDEV rules. This will create sym links to USB devices to avoid issues when accessing a port due to auto enumerating to /dev/ttyUSB0 etc.
  
* [Systemd service setup](tutorials/service-setup/service-setup.md)
    * Use a systemd service to auto start and manage your robot code on a Linux based system.
  
* [ROS realtime plotter](tutorials/rt-plotter/rt-plotter.md)
    * Very basic python plotter script to visualize values from a ROS topic in real time.
  
* [OTG Ethernet over USB](tutorials/eth-over-usb/eth-over-usb.md)
    * How to setup ethernet communication over USB between a Raspberry Pi 3B+ and two Raspberry Pi Zeros. 

---
20210704 - ahs808
