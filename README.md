# PDE4430-MOBILE-ROBOTICS
In the final module project. I have simulated a wheeled robot in a Gazebo virtual  environment to move to a specified location. This motion is instructed by a node  which publishes the moving command to drive the robot base.


Dependencies for the package:

Xacro - sudo apt-get install ros-<version>-xacro
	
	
Gazebo - sudo apt-get install ros-<version>-gazebo-ros

	
	
	
To clone:
	
	
	
Git clone https://github.com/suryaexe/PDE4430-MOBILE-ROBOTICS.git
	
	
cd PDE4430-MOBILE-ROBOTICS
	
	
catkin_make
	
	
source devel/setup.bash
	
	
roslaunch trixy world.launch
