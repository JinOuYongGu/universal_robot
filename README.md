# Universal Robot for ur_robot_driver
This is a fork from https://github.com/fmauch/universal_robot

Edited interface service to adapt the new Universal Robot driver:
https://github.com/UniversalRobots/Universal_Robots_ROS_Driver

That new driver uses scaled_pos_joint_traj_controller/follow_joint_trajectory instead of follow_joint_trajectory. So it needs some edit work to make it useable.