# 3D-A*-in-Vicon-


The repo use interact a* with mavproxy and mavros

# Step 1

Connect ground station to the jetson and vicon

# step 2

run the launch file including n6d_planner, n6d_trajectory_optimized, mission_manager, world2map bridge and tf2pose bridge.
``
ros2 launch nav6d_sim real_world_vicon_stack.launch.py
``

# Step 2

Run Mavproxy to arm and set mode of the drone


# Step 3

Run mavros to publish waypoint to mission_manager
