# Quick Usage Instructions

```bash
export RMW_IMPLEMENTATION=rmw_cyclonedds_cpp
```

## Odom Navigation

- Navigate in global frame of `map`

```bash
ros2 launch mbs_nav2_template odom_navi.launch.py
```

## Mapping

```bash
ros2 run slam_toolbox async_slam_toolbox_node
```

## Map Navigations

```bash
ros2 launch mbs_nav2_template odom_navi.launch.py
```

# Dependencies

```bash
sudo apt-get install ros-$ROS_DISTRO-twist-mux\
                     ros-$ROS_DISTRO-navigation2\
                     ros-$ROS_DISTRO-nav2-bringup
```