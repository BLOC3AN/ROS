# ROS
# RPL
Cài RP LIDAR.
B1: cd catkin_ws/src

B2 : git clone https://github.com/tu-darmstadt-ros-pkg/hector_slam
B3: cd ..
    source devel/setup.bash
    catkin_make --pkg hector_mapping
    catkin_make --pkg hector_geotiff_plugins
    catkin_make --pkg hector_trajectory_server
    catkin_make --pkg hector_geotiff

SET UP hector_slam
https://www.youtube.com/watch?v=Qrtz0a7HaQ4&t=214s
https://hackaday.io/project/7284-oscar-omni-service-cooperative-assistant-robot/log/26164-first-foray-into-ros
https://community.husarion.com/t/hector-slam-on-rosbot-pro-2-0/740

