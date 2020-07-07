# Universal Robot for ur_robot_driver
Edited interface service to adapt the new Universal Robot driver:
https://github.com/UniversalRobots/Universal_Robots_ROS_Driver

The driver uses scaled_pos_traj_controller/follow_joint_trajectory instead of follow_joint_trajectory. So it needs some edit work to make it useable.