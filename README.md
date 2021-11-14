# ece470_finalproject

Hi!

We are using this website so we collaborate on the code, but we have most of the files done locally. The simulator we are using is CoppeliaSim, and we are using Python (in Spyder) to program the UR3 robot. 

Project Update 1:

For this update, most of what did is in the file main.py. Basically, the script is divided into 3 parts.

The first one is establishing the connection between CoppeliaSim and Python (line 8-14)
The second is initializing/defining all the robots joints and the sensor we attached to it (line 16-23)
The third one is a while loop (line 26-49)containg the actions the robot does. We programmed to move to a default position, check its proximity sensor, then move somehwere close to the "grill", and check its proximity sensor again. 
There is some code that is commented out that we were not able to finish yet, but we are working on it.

proj update 1 link - https://youtu.be/jHi_SpvEkRM

Project Update 2+3:

For this update, most of what did is in the file update2.py. Basically, the tasks we completed are divided into 3 parts.

The first one is defining the forward kinematics equations by utilizing inverse kinematics, decision making, and planning. 
The second is perfecting the robot grasp to function and pick up objects. This is a very important step that we spent the most time figuring out.
The third one is integrating computer vision to actually detect the the components the robot is picking up. While the code is not working right now, with some more research on the available libraries, we should have the final viable product soon.
All of this code is a work in progress, but we are on track to finish the assignment plus the supplementary writings by the deadline.

proj update 2+3 link - 
