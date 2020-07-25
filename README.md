hcl_ws

# RoverROS

A repository containing the source code of a Custom Drone with Realsense plugin

## Dependancies:

You will need to install the following:

  ROS Melodic
   
  `sudo apt-get install ros-melodic-realsense2-camera`  from https://github.com/IntelRealSense/realsense-ros
   
   You will need to install mavros to catkin_ws as shown in the mavros official repo for mavros from source
   or you install it from apt package manager.

##Initial Setup
    
    1) go to the src/px4_mavros_launcher/Models folder
    2) copy the iris_realsense_camera folder to your Firmware/Tools/sitl_gazebo/models folder
    
##How to Build the Repo (Fresh Start)

    1) Git clone https://github.com/yuthikasagarage/hcl_ws
    2) Cd hcl_ws
    3) Catkin clean
    4) Catkin_make
    5) source devel/setup.bash
    
##Launching Files For PX4 Firmware and MAVROS starter
These launch files need to be executed 

    1) . ./px4.sh
    2) roslaunch px4_mavros_launcher px4_mavros_starter.launch
   
