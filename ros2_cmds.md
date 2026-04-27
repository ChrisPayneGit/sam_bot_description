**These are common commands to run this package**:

# To Setup *sam_bot*
*Setup every new terminal:
source /opt/ros/$ROS_DISTRO/setup.bash

* To run the *sam_bot* RViz and Gazebo Simulation:
ros2 launch sam_bot_description display_sdf.launch.py

* Launch the *slam_toolbox* for simulation use:
ros2 launch slam_toolbox online_async_launch.py use_sim_time:=true

* Launch Nav2 using *nav2_bringup*:
ros2 launch nav2_bringup navigation_launch.py use_sim_time:=true

# To control *sam_bot*
* Send commands to *sam_bot* using *teleop_twist_keyboard*:
ros2 run teleop_twist_keyboard teleop_twist_keyboard --ros-args -p stamped:=true --remap cmd_vel:=/demo/cmd_vel

* To publish a *Pose* in CLI
ros2 topic pub /goal_pose geometry_msgs/PoseStamped "{header: {stamp: {sec: 0}, frame_id: 'map'}, pose: {position: {x: 0.2, y: 0.0, z: 0.0}, orientation: {w: 1.0}}}"

# Example: *turtle_bot3 (waffle)*
* ros2 launch nav2_bringup tb3_simulation_launch.py slam:=True
* Where to find the code:
-  cat /opt/ros/jazzy/share/nav2_bringup/launch/tb3_simulation_launch.py