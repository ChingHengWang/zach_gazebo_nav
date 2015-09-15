# zach_gazebo_nav 

##No gazebo, only rviz
##it's 2D navigation display using rviz,move_base's local planner and global planner to send msg for /cmd_ve topic ,and use adv_robotic's base_controller to pick up the command and feedback the /tf and /odom to base_controller

## command 1
	$ roslaunch zach_gazebo_nav adv_robot_mobile.launch  

## command 2
	$ roslaunch zach_gazebo_nav move_base_map_with_obstacle.launch

## command 3
	$ rosrun rviz rviz -d `rospack find zach_gazebo_nav`/nav.rviz

