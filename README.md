MockBOTQ-Robot 

Ubuntu 26.04  /ROS 2 /Lyrical Robot functioning on a Qualcom VentunoTM Q dual-brain architecture development board.. 

The ROS 2 package architecture is based on Linorobot 2 (https://github.com/linorobot/linorobot2/tree/lyrical) and
MockBOTC1 (https://github.com/ARLunan/MockBOTc1-Robot).

The Ventuno Q combines a QualcommTM Dragonwing QCS8275 IQB processor IMPU) and STM32H5F5 microcontroller (MCU) 
which communicates seamlessly via RPC (Remote Procedure Call) bridge. The Robot Chassis is a 4WD Diff-Drive (skid-steer)
with Hall-Effect-Encoders, LD19 Lidar, OAK-D Lee, IMU ICM-20948, Logitech F710 manual teleop joystick.

It is intended to function in collaboration with the MockBOTQ-Desktop which provides SLAM and Mapping and Navigation2 autonomous navigation.

 
