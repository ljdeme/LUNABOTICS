# LUNABOTICS
LunarKnights entry for NASA Lunabotics 2023 Competition

# How to Setup
This package requires Ubuntu 20.04 (either as a VM, container, or actual system). Like all ROS1 packages, it's meant to be placed inside a catkin_ws at path /home/$USER/catkin_ws

1. Clone this repo into ~/catkin_ws/src with ' git clone https://github.com/ljdeme/LUNABOTICS.git '

2. Run the setup script with ' ./setup.sh '

# Directories

## luna_sim
  This directory will contain the launch files, simulation worlds, and configuration files used for RVIZ. This may also contain any scripts we use to make working with the sim easier, and submodules for simulating sensors.

## luna_nav
  This directory will contain configuration and launch files for our navigation stack. Move-base, robot-localization, and slam-toolbox should be configured and launched here.

## luna_vision
  This directory will contain any scripts and plugins we use for computer vision.

## luna_model
  This directory will contain the simulation model for our robot.

## luna_states
  This directory will contain the launch files and scripts for our state machine.
