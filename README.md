### Why?
This project creates the necessary header and source files to send data over a ROS2 node
Currently, it only has files for xbox controllers, but will later have more

### Build
- Set $ROS2 to the location of ROS2's files. Usually /opt/ros/{DISTRIBUTATION}/setup.zsh  
  
Note, all setup files are shell scripts. Change the extension to match what shell you're using. Default: zsh
```
source $ROS2/setup.zsh
colcon build --packages-select ros2_input_msgs
```
