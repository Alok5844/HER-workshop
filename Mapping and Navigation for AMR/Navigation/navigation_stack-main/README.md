# navigation_stack
Ros navigation_stack using AMCL and move_base algorithm 

roslaunch my_navigation amcl.launch
# This will launch amcl algorithm 
The navigation stack required amcl algorithm ADAPTIVE MONTE CARLO LOCALIZATION a probabilisties localization system for a robot.
It take input map,lidar scan, and tranformation message an dout is estimated pose.
# AMCL node sub
scan
tf
initialope 
map
amcl_pose 


roslaunch my_navigation move_base.launch 

# This will launch move_base algorithm 
This move_base will control the robot base by sub to cmd_vel topic the velocity control by move_base.


using hector and gmapping did the map and save it using map_server.

for navigation stack map is required save in map directory 
