* Set ROS_DOMAIN_ID=0

```bash
cd qualisys_ws
colcon build --symlink-instll
. ./install/setup.bash
ros2 launch uwb_test test.launch
```
