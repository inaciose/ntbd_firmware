# ntbd_firmware
Arduino sketches for the robotic arm control with ROS.

Works with ntbd project

Versions: 
- Servo only
- Steppers and Servo

Requires ntdb_msgs ROS package available in ntbd_base at: https://github.com/inaciose/ntbd_base


Test robot arm movement with the following command sample:

rostopic pub --once /motors ntbd_msgs/Motors_Array "data: [20, 10, 110, 90]"

# Related repositories

- https://github.com/inaciose/ntbd_base
- https://github.com/inaciose/ntbd_web
- https://github.com/inaciose/ebamk1_description
- https://github.com/inaciose/ebamk2_description
- https://github.com/inaciose/ramk2p_description
