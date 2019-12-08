---
title: "Qibing Robot"
collection: projects_mcu
permalink: /projects/mcu/robogame
excerpt: "This is the project for Robogame and won the first prize."
start_date: Sep. 2017
end_date: Apr. 2018
date: Oct. 2018
selected: false
---

This project is for **Robogame**, a robot design contest held by USTC, and won the **first prize**.

Our robot should grab four flags placed on wooden boxes of four specific colors, put two of the flags on the lower poll, and put the other two on the higher polls.

Our robot is called Qibing (旗兵 in Chinese, meaning a flag soldier). Using OpenCV on Raspberry Pi, we were able to identify the color of the boxes and decide the moving strategy. We used STM32 as the movement controller and implemented PID control algorithm on STM32 to guarantee stable and high-speed movement. Finally, we employed UART devices for efficient and reliable communication between the Raspberry Pi and STM32.

Below is our robot. If you are interested in the performance of our robot, check the video of the [exhibition game](https://youtu.be/flF1CCWiBO4) (Qibing is on the red side, i.e. on the right side of the stage).

![](/images/robogame_qibing.jpg)