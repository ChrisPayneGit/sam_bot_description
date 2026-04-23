# sam_bot_description
This is a repos following the ROS2 NAV2 Tutorial, "Setting Up the URDF" (https://docs.nav2.org/setup_guides/urdf/setup_urdf.html#setting-up-the-urdf). This tutorial shows the steps to setup a basic robot simulation in RViz.

## Tutorials Completed So Far:
* [**Setting Up The URDF**](https://docs.nav2.org/setup_guides/urdf/setup_urdf.html): Creating a simple visual and physical model for a differential-drive robot called sam_bot
* [**Setting Up The SDF**](https://docs.nav2.org/setup_guides/sdf/setup_sdf.html): Creating a simple .sdf to describe the sam_bot in a simulated environment e.g. Gazebo (*Simulation Description Format*)
* [**Setting Up Odometry**](https://docs.nav2.org/setup_guides/odom/setup_odom_gz.html): Adding the required elements to produce the transforms and messages expected by the Nav2 odometry system
* [**Smoothing Odometry using Robot Localization**](https://docs.nav2.org/setup_guides/odom/setup_robot_localization.html): Implemented the *robot_localization* node to produce filtered and smoothed odometry sensor data from multiple sources, i.e. wheel encoders and IMUs

## Next Up To Complete:
* [**Setting Up Sensors - Gazebo Classic**](https://docs.nav2.org/setup_guides/sensors/setup_sensors_gz_classic.html): Will add a basic sensor setup to sam_bot