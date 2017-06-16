# Motor Driver BTS7960B and a PCA9685 servo controler
This is a set of Python programs to control two DC motors with two BTS7960 motor drivers and single PCA9685 servo controler board. The PCA9685 generates only the PWM signal which is needed to control the speed of the DC motor connected to the motor driver.

![Raspberry Pi robot - BigRob](https://custom-build-robots.com/wp-content/uploads/2017/01/Custom-Build-Robots-Big-Rob16-300x225.jpg)

Due to the fact that the Raspberry Pi has problems to generate four independent PWM signals I searched for a cheap solution.
I ended up in the combination of the PCA9685 servo controler and two BTS7960 motor drivers boards.

I tested the program in my BigRob robot and it works perfect together with the RobotControl.py program. Mor about the BigRob and How to build ist is available on my Blog: https://custom-build-robots.com/raspberry-pi-robot-cars/big-rob-motor-driver-bts7960b/8155?lang=en
