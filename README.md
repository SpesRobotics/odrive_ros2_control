# odrive_ros2_control
ENGLISH / [中文](<README_CN.md>)
## Introduction
ODrive driver for ros2_control
## Compatibility
|  | ROS 2 Foxy Fitzroy | ROS 2 Humble Hawksbill |
|---|---|---|
| ODrive Firmware v0.5.3 | [foxy-fw-v0.5.3](../../tree/foxy-fw-v0.5.3) | [humble-fw-v0.5.3](../../tree/humble-fw-v0.5.3) |
| ODrive Firmware v0.5.1 | [foxy-fw-v0.5.1](../../tree/foxy-fw-v0.5.1) | [humble-fw-v0.5.1](../../tree/humble-fw-v0.5.1) |
## Documentation
- [Wiki](https://github.com/Factor-Robotics/odrive_ros2_control/wiki/Documentation)
## Done
- [x] Support native protocol on USB
- [x] Support position, speed, torque commands
- [x] Support position, speed, torque feedbacks
- [x] Support using multiple ODrives
- [x] Support smooth switching of control modes
- [x] Unit conversion adheres to [REP-103](<https://www.ros.org/reps/rep-0103.html>)
- [x] Support using any or both of axes on each ODrive
- [x] Allow multiple axes running in different control modes
- [x] Provide sensor data (error, voltage, temperature)
- [x] Auto watchdog feeding
## Todo
- [ ] Support serial port and CAN
- [ ] Support feedforward control inputs
- [ ] Automatic configuration of ODrives based on URDF and YAML files