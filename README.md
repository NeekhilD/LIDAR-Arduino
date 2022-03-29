#  Photogrammetry Using LIDAR + ARDUINO


<p align="left">
  
</p>

<img src="https://user-images.githubusercontent.com/26859754/160553016-117dd5ed-b7cf-4b82-a406-24accdca9507.png" width="500"/>
<img src="https://user-images.githubusercontent.com/26859754/160553172-300a27d5-dfde-4a4d-bf8a-66fbd52be52d.png" width="500" />




Arduino code
Thank to the Servo.h and LIDARLite.h Arduino libraries, the code to control these elements is made much easier. The basic work-flow of the code is the following:

 ``` Init. lidar, servos and serial; 
  For YawAngle = 0 to 180
  For PitchAngle = 0 to 180 
  Compute coordinates;
  Send value;
  ```
  
The micro-controller only knows the angles of the servos and the distance to the obstacle. A small amount of computation is required to convert the yaw angle, pitch angle and range information into much more usable X, Y and Z coordinates.











## With The Help Of  


<img align="left" width="50px" src="https://user-images.githubusercontent.com/26859754/160555283-cc38287b-f8b1-460a-beba-f0c3439c039f.png"/>
<img align="Center" width="20px" src="https://comma.ai/comma-white.png"/>
<img align="Center" width="80px" src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/87/Arduino_Logo.svg/2560px-Arduino_Logo.svg.png"/>
