# UAS-AVIONICS-TASK
## UAS RECRUITMENT TASK
NAME : SARTHAK AGGARWAL </br>
BRANCH : ECE </br>
DEPARTMENT : AVIONICS </br>
ROLL NUMBER : 2K22/A18/25 </br>
TASK : TO MAKE AN ANTENNA TRACKING SYSTEM (ATS) </br>

DESCRIPTION :

QUES :
Design an antenna tracking system using MATLAB code that can accurately track the motion of a UAV given its equation of motion. The antenna tracking system should be capable of computing the appropriate direction and orientation of the antenna based on the UAV's position and velocity, and it should be able to adjust the antenna in real-time to maintain a strong signal connection.

SUMMARY OF CODE:
I have set the initial coordinates of the UAV as (x0, y0, z0) from the user input.
Similarly, I have set the initial orientation of the antenna ie phi, and theta from the user input.
Now as my code starts, it shows the equation of motion of the UAV wrt time.

x = 3t </br>
y = 4t </br>
z = 5tan(t) </br>

Differentiating the equations above we get equations for the velocities in the respective axes.

Vx = 3 </br>
Vy = 4 </br>
Vz = 5(sec(t))^2 </br>

Now to find the final orientation of the antenna, we compute the final theta and phi (theta_f and phi_f) by using the basics of polar coordinate geometry, and then adjusting the antenna's direction accordingly.

Now the loop starts from t = 0 to t = user input, having step size = user input. The coordinates of the x, y and z axes changes accordingly; thus the direction and the orientation of the antenna changes which is the ultimate aim of this task. 
