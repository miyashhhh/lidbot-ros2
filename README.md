## LIDBOT (Autonomous Robot using LiDAR Sensor and SLAM Algorithm for Navigation)

To run simulation at current stage use command.

Terminal 1
```bash

ros2 launch lidbot_ros2 launch_sim.launch.py world:=.src/lidbot_ros2/worlds/construction_cones.world


```

To control robots movement run command.

```bash

ros2 run teleop_twist_keyboard teleop_twist_keyboard 
```
