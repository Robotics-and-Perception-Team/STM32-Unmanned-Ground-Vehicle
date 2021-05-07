# STM32-Unmanned-Ground-Vehicle
STM32F4 Discovery based Autonomous Unmanned Ground Vehicle Codes
As Medipol Robotics and Perception group, we made STM32F4 based unmanned ground vehicle for autonomous missions. These codes are written in STM32CUBE IDE program.


Uploading WhatsApp Video 2021-01-04 at 18.24.29 (1).mp4…


This program is using two serial ports, one of them for communicating with a computer via UART communication bus. Other is communicating with TF-mini Lidar. If you haven't got Tf-mini Lidar you can disable lidars code from program by comment it.

In Src file main.c is your user code, while using this code you can change and improve main.c. This code uses HAL Libraries.

For communicating with computer like Raspberry Pi or Nvidia Jetson series developer boards, You have to use serial library in python or c++. Check Ascii codes and send movement data by each bytes.
