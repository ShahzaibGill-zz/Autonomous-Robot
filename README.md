# LEGO Grab and Retrieve Robot
Autonomous Grab and Retrieve Robot made using LEGO Mindstorms and Robot C

![ScreenShot](https://github.com/ShahzaibGill/Autonomous-Robot/blob/master/Lego%20Robot%20Pictures/full%20robot%202.jpg?raw=true)

## What does the Robot do?

The autonomous robot searches for "garbage" by rotating 360 degrees. After detection of an object using the ultrasonic sensors, the robot stops the rotation and approaches the object. After approaching the object, the robot stops, clamps the object, and rotates again in order to search for the target disposal site. The robot then approaches the disposal location and drops off the object.

## Sensors and Design

1. Ultrasonic Sensor placed near the ground is used for detecting object
2. Ultasonic Sensor placed higher up is used to locate the target disposal location - indicated by a flag
3. Two intensity Sensors to ensure the robot stays within a set environment and does not fall into the disposal location hole

Since Lego Mindstorm is limited to 3 motors, and 2 motors are used for movement (linear and rotational), only one motor was used to both clamp and lift the object off the ground. This was done through innovative mechanical design, where the motor would spin until the object is clamped (and the clamping gear is locked). The locked clamping gears would then cause the preceding gears to become rigid, and the arm lifts up.

## Block design and 3D Printed components
![ScreenShot](https://github.com/ShahzaibGill/Autonomous-Robot/blob/master/Lego%20Robot%20Pictures/various%20clamp%20designs.jpg?raw=true)

## Additional Pictures
![ScreenShot](https://github.com/ShahzaibGill/Autonomous-Robot/blob/master/Lego%20Robot%20Pictures/Clamping%20mechanism%202.jpg?raw=true)
![ScreenShot](https://github.com/ShahzaibGill/Autonomous-Robot/blob/master/Lego%20Robot%20Pictures/Clamping%20mechanism.jpg?raw=true)
![ScreenShot](https://github.com/ShahzaibGill/Autonomous-Robot/blob/master/Lego%20Robot%20Pictures/robot%20after%20clamp%20.jpg?raw=true)