# AU423

## Install dependencies
```bash
sudo apt install -y ros-galactic-joint-state-publisher-gui ros-galactic-effort-controllers ros-galactic-controller-manager ros-galactic-gazebo-ros2-control ros2-galactic-ros2-control ros-galactic-joint-state-broadcaster ros-galactic-joint-trajectory-controller ros-galactic-position-controllers ros-galactic-diff-drive-controller ros-galactic-velocity-controllers
# sudo apt install -y ros-galactic-joint-state-controller 
```

## Clone this repository in your workspace
```bash
cd ~/catkin_ws/src && git clone https://github.com/JohvanyROB/AU423
cd ~/catkin_ws && catkin_make && source ~/catkin_ws/devel/setup.bash
```