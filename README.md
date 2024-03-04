# IN426

## Clone this repository in your workspace
```bash
mkdir -p ~/ros2_ws/src && cd ~/ros2_ws/src && git clone https://github.com/JohvanyROB/IN426
```

## Install ROS2 galactic if not done yet
If you are using ROS Development Studio, skip this part and go to the last section! (Compile the project)
```bash
cd ~/ros2_ws/src/IN426 && ./install_galactic.sh && source ~/.bashrc
```

## Compile the project
```bash
cd ~/ros2_ws/src/IN426 && ./install_dependencies.sh && source ~/ros2_ws/install/setup.bash
```