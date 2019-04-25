# Arduibo-with-Matlab
This project is __MATLAB Support Package__ for Arduino Hardware

## Timeline:
2019.4.25
1. download the Simulink Support Package for Arduino Hardware
2. successfully run __first demo__ and nearly have no problems while follow the [offical document](https://www.mathworks.com/help/supportpkg/arduino/ref/getting-started-with-arduino-hardware.html).
3. ecounter a problem, which is adding a plot and check the feedback from servo motor.
4. When I want to run simulink function, it report [this error](https://www.mathworks.com/matlabcentral/answers/356266-failed-to-generate-all-binary-outputs).
5. When I want to run Matlab instead, it report that I didn't have MATLAB Support Package for Arduino Hardware.
6. I try to download the package, however it report errors when I download.
7. I find in the internet and they say this is because the version of Matlab too low.
8. I try to download Matlab 2018, and at the same time, I download the package in my surface computer, too.
9. When I download Matlab 2018, there are millions of [problems](https://blog.csdn.net/niuxiaolei/article/details/80596183)!
10. Meanwhile, my surface also doesn't work! The same code from my desktop can't work in the same environment in my surface, and they report this [error](https://www.mathworks.com/matlabcentral/answers/402811-simulink-io-enabled-error-on-arduino-uno).
11. I give up and go back have a rest.

2019.4.26
1. As to download Matlab 2018, I eventually try to ejct and import many time and solve the [problem](https://blog.csdn.net/niuxiaolei/article/details/80596183).
2. After one hour, my two computers have the same verion of Arduino Support Package.
3. However when I run a very simple simulink model in my desktop, it ecounter thousands of errors and with extremely low speed!
4. The same in my surface. I have two Arduino boards. Once I change one of them to connect the other computre. There are errors...
5. I eventually give up and waste two hours to fix this problem.
6. At the moment I giving up and clean my desk. An idea occurs in my mind, maybe I can try __Matlab Package__. And I download Matlab Package on my desktop. And eventually find that Matlab Package is much more stable and will seldom encounter the problems occur in Simulink package.
7. There are also some problems in the process. You can try to transfer the __port of Arduino__
8. However, I find there too many funciton that I don't know to handle matlab arduino. Hence I need some time to master it.

## Summary
Actually, it is a good start. I have completed two tasks, and learn how to debug the Arduino Package.

## Tasks:
Final: [Control Motor](https://www.mathworks.com/videos/hardware-support-package-from-matlabsimulink-to-real-application-115952.html)
1. ~~Install successfully the packages~~
2. ~~Simulink: LED light demo~~
3. ~~Simulink: servo motor control~~
4. Simulink: servo motor control live
5. ~~Matlab: servo motor control live~~

    ![arduino](/img/servo_motor.jpeg)

6. Matlab: DC motor control
    1. is it another board?

    ![arduino](/img/arduino.jpeg)

    2. speed control board
    3. find the stable source
    
    ![arduino](/img/power.jpeg)

    ![arduino](/img/connection.jpeg)
7. Simulink: DC motor control live

other useful videos:

1. [Using Arduino with MATLAB and Simulink](https://www.mathworks.com/videos/using-arduino-with-matlab-and-simulink-100477.html)

2. [Using MATLAB and Arduino for Motor Control](https://www.mathworks.com/videos/using-matlab-and-arduino-for-motor-control-100737.html)
