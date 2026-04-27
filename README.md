# sam_bot_description
This is a repos following the ROS2 NAV2 Tutorial, "Setting Up the URDF" (https://docs.nav2.org/setup_guides/urdf/setup_urdf.html#setting-up-the-urdf). This tutorial shows the steps to setup a basic robot simulation in RViz.

## Tutorials Completed So Far:
* [**Setting Up The URDF**](https://docs.nav2.org/setup_guides/urdf/setup_urdf.html): Creating a simple visual and physical model for a differential-drive robot called sam_bot
* [**Setting Up The SDF**](https://docs.nav2.org/setup_guides/sdf/setup_sdf.html): Creating a simple .sdf to describe the sam_bot in a simulated environment e.g. Gazebo (*Simulation Description Format*)
* [**Setting Up Odometry**](https://docs.nav2.org/setup_guides/odom/setup_odom_gz.html): Adding the required elements to produce the transforms and messages expected by the Nav2 odometry system
* [**Smoothing Odometry using Robot Localization**](https://docs.nav2.org/setup_guides/odom/setup_robot_localization.html): Implemented the *robot_localization* node to produce filtered and smoothed odometry sensor data from multiple sources, i.e. wheel encoders and IMUs
* [**Setting Up Sensors - Gazebo**](https://docs.nav2.org/setup_guides/sensors/setup_sensors_gz.html): Added a basic sensor setup to sam_bot's Gazebo *.sdf* and *.urdf*, including a LIDAR and a RBGD Depth Camera
* [**Mapping and Localization**](https://docs.nav2.org/setup_guides/sensors/mapping_localization.html): Set up the *slam_toolbox* and *nav2_amcl* for sam_bot, showing the costmap and occupancy grid from the LIDAR sensor.
* [**Setting Up the Robot’s Footprint**](https://docs.nav2.org/setup_guides/footprint/setup_footprint.html): Set up the sam_bot's local and global footprint as a polygon and circle, respectivley. This was based on the default from *nav2_params.yaml*.
* [**Setting Up Navigation Plugins**](https://docs.nav2.org/setup_guides/algorithm/select_algorithm.html): Set up sam_bot to use different planner and controller algorithms to complete navigation tasks.

## Next Up To Complete:
* **ALL TUTORIALS HAVE BEEN COMPLETED IN THIS SERIES**