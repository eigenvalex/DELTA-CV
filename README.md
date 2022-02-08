# -High-Speed-Pick-and-Place-4-DOFs-Parallel-Kinematic-Delta-Robot---Graduation-Project
Worked in a team of 7, designing and manufacturing a delta robot capable of increasing the production rate contributing to solving the worldwide increasing demand problem. The robot can pick and place products swiftly at amazingly high speeds also rotates the product while moving it. The control algorithm starts with the camera capturing a frame to locate where the products are, then a script warps the image and applies filters on the captured frame. The script outputs X &amp; Y coordinates of the products which is the input for the next stage, the inverse kinematics, the coordinates are converted from cartesian to angles at the motor shaft. Furthermore, A sophisticated trajectory planning algorithm is utilized to plan a path and trajectory for the end effector to move along. The output is an array of angles (points). All the previous steps were being executed on a Jetson TX2 (high-level). The output array is transferred to a Tiva TM4C (Low-level) through the I2C communication protocol. Finally, the microcontroller controls the motors according to the received data and executes them in the required time.

You can find the working project Video & more stuff at
https://engasuedu-my.sharepoint.com/personal/16p8196_eng_asu_edu_eg/_layouts/15/onedrive.aspx?id=%2Fpersonal%2F16p8196%5Feng%5Fasu%5Fedu%5Feg%2FDocuments%2FHigh%20Speed%20Pick%20and%20Place%204%2DDOF%E2%80%99s%20Parallel%20Kinematic%20Robot%20%2D%202021
