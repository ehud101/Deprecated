# Robil over ROS2 guide
The following will guide you run the Robil project in two states:  
1. With HECTOR-SLAM  
Since HECTOR is built to work in ROS1,This will require you to have both ROS1 and ROS2 environments and run the ROS1_Bridge package.
so you must have both ROS versions installed on your machine.
2. All native ROS2 packages, including the ROS2 SLAM package --> SLAM Toolbox.

# Running Robil with HECTOR-SLAM and ROS-Bridge
since we are required to run both versions simultaneously, we must make sure that each terminal is set with **only one** of the versions environment (variables). It should be absoloutly clean from the other one's.
Therefore, make sure that your terminal is not automatically set with any of ROS's environment variables. means that when you open a new terminal and check the current environment, none is related to ROS.

if it is set automatically try the flollowing:
1. Remove any source command of ROS setup file from .bashrc file or any other file of this kind.
2. Check the folder *opt/ros/melodic/etc/catkin/profile.d*
This folder might be one of the places the o.s is looking for initial setting of environment variables.

Once the terminals are clean follow the steps:
1. clone/download this repository (https://github.com/ehud101/robil4.git)  
These are the main ROBIL files
2. clone/download the repository  (https://github.com/ehud101/ros1_ws.git)  
This is HECTOR-SLAM package modified for ROBIL.  
put the folder in your $HOME directory
3. Open a new teminal and source the file filesToSource/.bashrc_bridge  
This will

## Running the simulation

