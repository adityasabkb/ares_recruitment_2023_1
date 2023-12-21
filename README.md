# Installation

```
mkdir -p ares_bot_ws/src
cd ares_bot_ws/src
git clone <link>
cd ..
colcon build --symlink-install
```


# Launch
```
source install/setup.bash
ros2 launch ares_bot launch_sim.launch.py
```
There are some missing packages which you will have to install by yourself.<br>
Reading the errors would help