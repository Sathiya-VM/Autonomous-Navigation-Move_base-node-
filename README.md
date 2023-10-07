# Autonomous-Navigation-Move_base-node
+ The launch folder in this file consists of amcl and move_base nodes.
+ where amcl is for localization and move_base is for path planning & navigation.
+ thus the navigation.launch is used to start multiple nodes(amcl & move_base) at once.
  ## To make use of the complete project use the following commands.
  Before using the following ros commands copy the gazebo.launch file outside the folder in Mobile Robot URDF repository to robot11_description folder , similarly for gmapping and hectormapping launch files.
  
  - roslaunch robot11_description gazebo.launch
  - roslaunch robot11_description gmapping.launch (or)
  - roslaunch robot11_description hectormapping.launch
  - roslaunch navigation navigation.launch 
