# Southern Arm Control Description

This project holds the robot description files the Southern Arm Control workspace. Full documentation for the sac project can be found at [CraigCode1010.com](http://craigcode1010.com) under projects > SAC.

## Installation

To install the Southern Arm Control system download sac_setup from https://github.com/greenpro/sac_setup.git and run the setup.sh script for Ubuntu or the rpiSetup.sh script for Raspian.

## Files
### CMakeList.txt
* This file holds the project configuration for building.

### package.xml
* This file holds the project configuration for building.

## Folders
### launch/
* This file holds the launch files for the project.
* The launch files should not reference launch files form any other project.
* The launch files should not be called directly (they should be called through the sac_launch project's launch files).

### meshes/
* This folder holds the stl mesh files for the robots

### urdf/
* This folder holds the description files for the robots.

## Notes
* Much of the code for the scorbot comes from in this package has been modified from https://github.com/baijuchaudhari/sboter4u.git
