# Tracking PID Controller for Differential-Drive Vehicles



This is a simple PID controller written in Python3 for controlling differential-drive vehicles, such as [Heron Unmanned Surface Vehicle (USV)](https://www.clearpathrobotics.com/assets/guides/melodic/heron/index.html), [Jackal Unmanned Ground Vehicle (UGV)](http://www.clearpathrobotics.com/assets/guides/noetic/jackal/), and [Husky UGV](https://www.clearpathrobotics.com/assets/guides/kinetic/husky/index.html), to a desired position/waypoint. A tutorial can be found [here]((https://weizhechen.com/tracking_pid/)).

This repo is mostly based on https://github.com/Weizhe-Chen/tracking_pid 


Heron USV | Jackal UGV | Husky UGV
:-------------------------:|:-------------------------:|:-------------------------:
<img src="https://www.clearpathrobotics.com/assets/guides/melodic/heron/_images/heron_banner.jpg" width="300" height="100"/> |  <img src="http://www.clearpathrobotics.com/assets/guides/noetic/jackal/_images/jackal_banner.png" width="300" height="100"/> | <img src="https://www.clearpathrobotics.com/assets/guides/kinetic/husky/_images/TJM_5949_00001.jpg" width="300" height="100"/>


Make sure your `~/.bashrc` has the following settings and remember to `source ~/.bashrc` after modifying it:

```bash
export ROS_MASTER_URI=http://localhost:11311
export ROS_HOSTNAME=localhost
```


```
git clone https://github.com/this-repo
cd ..
catkin build
. devel/setup.bash  # `.` is equivalent to `source`
rosrun tracking_pid tracking_pid_node.py
```

