# Lu_hector_basic
Hector Slam &amp; RPLidar Launch files for LU UAV project. For simplicity: odom_frame = base_frame = base_link. Base_link is coincident to laser

Replace tutorial.launch in:
 /home/luengr/catkin_ws/src/hector_slam/hector_slam_launch 
 with tutorial_modified.launch

Replace mapping_default.launch in:
 /home/luengr/a_ws/src/hector_slam/hector_mapping
 with mapping_default.launch

Then run:
rplidar.launch (/home/luengr/catkin_ws/src/rplidar_ros)
and
tutorial_modified.launch (/home/luengr/catkin_ws/src/hector_slam/hector_slam_launch )
