
# Prometheus sim
Prometheus Robot (V1.0) Simulation (ROS 1)

![Ubuntu 20.04](https://img.shields.io/badge/OS-Ubuntu_20.04-informational?style=flat&logo=ubuntu)
![ROS Noetic](https://img.shields.io/badge/Tools-ROS_Noetic-informational?style=flat&logo=ROS)
![Gazebo-classic](https://img.shields.io/badge/Tools-Gazebo%20Classic%2011-informational?style=flat&logo=Gazebo)

![Carlos_Prometheus_Gif](https://github.com/user-attachments/assets/0e245cd5-2e44-4824-ab3b-f7aea6fa5331)


## Prometheus is a real robot
We developed Prometheus as the avatar robot side of a telepresence system, and it is the first full-scale humanoid robot created in Mexico. It ranked 7th out of 99 contestants in the ANA Avatar XPRIZE competition.

![teleop_prome_2](https://github.com/user-attachments/assets/6592794a-97a6-4356-b198-1922c607ec11)


## Dependencies
* System Requirements:
    * `Ubuntu 20.04` 
    * `ROS Noetic` 
    * `Gazebo Classic 11` (default with ROS Noetic)
  

## Installation of this package
To install the prometheus_sim package, follow these steps: 

```bash
  # Clone the repository into your workspace (e.g. catkin_ws) and build it
  cd ~/catkin_ws/src/
  git clone https://github.com/CarlosHdezM/prometheus_sim.git
  cd ..
  catkin build # You can also use catkin_make if preferred
  source devel/setup.bash
```

