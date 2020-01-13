---
title: "Qibing Robot"
collection: projects_mcu
permalink: /projects/mcu/robogame
excerpt: "This project is for **Robogame**, a robot design contest held by USTC, and won the **first prize**. Our robot is called Qibing (旗兵 in Chinese, meaning a flag soldier). Using OpenCV on Raspberry Pi, we were able to identify the color of the boxes and decide the moving strategy. We used STM32 as the movement controller and implemented PID control algorithm on STM32 to guarantee stable and high-speed movement. Finally, we employed UART devices for efficient and reliable communication between the Raspberry Pi and STM32."
start_date: Sep. 2017
end_date: Apr. 2018
date: Oct. 2018
selected: true
---

This project is for **Robogame**, a robot design contest held by USTC, and won the **first prize**. Here is the [detailed rules](#rules) for this competitions.

Our robot is called Qibing (旗兵 in Chinese, meaning a flag soldier). Using OpenCV on Raspberry Pi, we were able to identify the color of the boxes and decide the moving strategy. We used STM32 as the movement controller and implemented PID control algorithm on STM32 to guarantee stable and high-speed movement. Finally, we employed UART devices for efficient and reliable communication between the Raspberry Pi and STM32.

Below is our robot. You can check our [technical report](/files/qb.pdf) (in Chinese) if you are interested in the specific implementation. If you are interested in his stage performance, check the video of the [exhibition game](https://youtu.be/flF1CCWiBO4) (Qibing is on the red side, i.e. on the right side of the stage).

![](/images/robogame_qibing.jpg)

Our team consists of five people. I was responsible for algorithm design, all STM32 programming and most Raspberry Pi programming. This is our team:

![](/images/robogame_comp.jpg)

And this is our award certificate:

![](/images/robogame_certi.png)

## <span id="rules" /> Detailed Rules

The motto of USTC is "红专并进理实交融". As 2018 is the 60th anniversary of USTC, the Robogame committee designed a special game based on this theme.

The game is divided into red and blue sides. Both robots start from the starting area at the same time and reach the designated position through the patrol line. There are eight flags with different colors along the road, marked as "红", "专", "并", "进", "理", "实", "交" and "融" respectively. Each player should select different flags according to the color; The blue player chooses the four flags marked "红", "专", "并", and "进", and the red one chooses the four flags designated by "理", "实", "交" and "融". After holding the flag, the robot should place the flags on cylinders of different heights in order. Due to the limited size of the robot, the robot can only place the flag on the tall cylinder by climbing up it. The player who completes the game faster wins.

![](/images/robogame_rules.png)

If you still cannot understand the rule, check the [exhibition game](https://youtu.be/flF1CCWiBO4).

