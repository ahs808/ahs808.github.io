# Robotic Systems Setup Guides

Compilation of guides I've created and regularly reference when setting up robotic projects in Linux.

* [ROS on Raspberry Pi 3B+]
    * Setup guide to install ROS Kinetic and Ubuntu Xenial on a Raspberry Pi 3B+.
* [Time synchronization](tutorials/chrony-setup/chrony-setup.md)
    * Set up chrony to sync clocks between multiple linux computers, this is particularly useful for robotic systems with no internet connection. 
* [Static IP setup](tutorials/static-ip-setup/static-ip-setup.md)
    * Set static IP addresses, important for ROS networking and time synchronization between multiple SBCs (single board computer).
* [Local Git setup]
    * Use Git to push/pull code between a robot, laptop, and Github, where the robot has no internet connection and the laptop acts as a bridge.
* [UDEV rules]
    * How to set static mapping for USB / serial ports in Ubuntu using UDEV rules. This will create sym links to USB devices to avoid issues when accessing a port due to auto enumerating to /dev/ttyUSB0 etc.
* [Systemd service setup]
    * Use a systemd service to auto start and manage your robot code on a Linux based system.
* [ROS realtime plotter]
    * Very basic python plotter script to visualize values from a ROS topic in real time.
* [OTG Ethernet over USB]
    * How to setup ethernet communication over USB between a Raspberry Pi 3B+ and two Raspberry Pi Zeros. 

---
20210704 - ahs808
