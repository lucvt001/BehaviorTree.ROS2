## Installation

### Dependencies

```bash
cd ~/ros2_ws/src
git clone https://github.com/lucvt001/BehaviorTree.ROS2.git
git clone https://github.com/BehaviorTree/BehaviorTree.CPP.git
sudo apt install -y ros-${ROS_DISTRO}-generate-parameter-library
```

### Build

Open a new terminal so that everything is reloaded:

```bash
cd ~/ros2_ws
colcon build --symlink-install --packages-select behaviortree_cpp behaviortree_ros2 btcpp_ros2_interfaces
```

You can build btcpp_ros2_samples as well, but it is not necessary.
