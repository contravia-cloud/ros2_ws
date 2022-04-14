mkdir ros_opencv_ws  
cd ros_opencv_ws/  
mkdir src  
cd src/  
source /opt/ros/galactic/setup.bash  
ros2 pkg create opencv_rviz_tutorial --build-type ament_cmake --dependencies rclcpp std_msgs sensor_msgs  


