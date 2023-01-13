# elegooAndroidSimulinkSonarRobotNavigation
Use Simulink code generation for Android phone and Arduino Elegoo robot to do sonar based navigation

This project is for controling a robot using and Android Pixel 3a phone to do ultra-sonic based navigation of a house. The robot moves always forward and randomly turns left and right if an object is detected on front by the sonar.

Although this can be done solely within the robot, the fact that the Android phone controls the robot open up the door to do more interesting projects like using deep learning for computer vision, use the phone sensors, or implement a conversational agent with the robot.

The robot used in these models is "ELEGOO UNO R3 Project Smart Robot Car Kit V 3.0" (See link below). Please note that pin numbers might need to be adjusted in the model depending how the assembly of the robot was made.

https://www.elegoo.com/products/elegoo-smart-robot-car-kit-v-3-0-plus

This video discusses this project: https://www.youtube.com/watch?v=Tr4ih_EBk8c
This is the Spanish version of the video above: https://www.youtube.com/watch?v=CnedqasHmfI&t=623s

To do this project you will need an adapter cable to connect your phone with the USB cable of the robot as shown in the video. Maybe some velcro or other way of attaching your phone to the robot. You need to install both the Simulink Android and Arduino support packages from MathWorks that are free of cost. You also need MATLAB access with the Embedded Coder for Simulink code generation.

The two models needed for the project are in this repository:
Phone model: mElegooSonarControlAndroid.slx
Robot model: mElegooArduinoV1.slx

You have to generate code for them as described in the videos to upload the code in them.

These videos also show more details about the code generation from the model to the targets (Android/Arduino):
English: https://www.youtube.com/watch?v=O6Hy5tvZBbk
Spanish: https://www.youtube.com/watch?v=w9TmVaCLj-s
