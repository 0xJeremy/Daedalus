# Daedalus Motor Controller

#### Who we are, and what we're doing

We are two mechanical engineering students at Tufts University. As part of a project with our university robotics club, we are working on making strong, fast, accurate, and reliable robot actuators. We were inspired by robots like Spot and Atlas by Boston Dynamics, the Unitree A1, and the MIT Mini-Cheetah. This work is broken into two parts: a custom actuator with a 6:1 planetary gearbox called called the OrbitActuator, and a custom-designed motor controller board: Daedalus.

#### Project Description

As mentioned above, our project is broken into two parts, but they come together seamlessly to make a state-of-the-art robotic actuator. This actuator is as small and powerful as we can make it. The Daedalus motor controller is perfectly designed to complement the mechanical design, and fits directly behind the motor. Using an integrated magnetic encoder, the Daedalus board can provide extremely precise position control to the motor. It runs at 24V and is capable of supplying up to 30 amps to the motor when required. It uses the CAN bus communication protocol, and accepts power via one of two XT30 plugs on the bottom of the board. It is designed to be fully daisy chained, with in terms of power and data to reduce the number of wires that go to your main robot controller. With it's on-board STM32 microcontroller and 168 MHz clock speed, the Daedalus Motor Controller can also perform blazing fast calculations to help offload computation from the main robot computer. It comes equipped with an SWD breakout, and Micro USB port for programming and debugging.

This project is fully open source, with full build instructions and a detailed bill-of-materials coming soon.

#### Future Plans

In the future we plan to develop the firmware to run this board and optimize it for use with our custom actuator. As with the hardware, this will be fully open-source and open for hacking and modifying to fit other projects. We intend to develop a version 2 of this board that we hope will be smaller, and capable of supplying even more current at peak.

#### Words to PCBWay

We are hoping PCBWay will be able to help us by sponsoring our Daedalus Motor Controller board. We have put countless hours in the careful design, and re-design of this board to make full use of PCBWay's manufacturing capabilities. We intend to use the assembly service to fully assemble all the surface mount components, add our Micro-USB port, and mount our magnetic encoder to the back of the board. We want to thank PCBWay for having such an easy and inviting sponsorship program for universities and students.
