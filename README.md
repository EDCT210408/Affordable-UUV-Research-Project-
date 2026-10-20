# Affordable-UUV-Research-Project-

An undergraduate research project with an objective to design an Underwater Unmanned Vehicle (UUV) using affordable components. The UUV will utilize a robust PID controller to maintain nominal depth and course.

The project is split up into four parts with each playing into each other. The project is structured so that: CAD Model --> Mathematical Model --> Python Simulator --> Hardware Implementation 

With the CAD Model defining the geometry of the UUV for use in the python simulator along with actuator placement and mass properties. The mathematical model will define equations of motion and the hydrodynamic considerations with geometric properties defined by the CAD Model. With the equations of motion fully defined a python script can be used to simulate the UUV using our derived EOMs. The Python Simulator and subsequently the UUV prototype will be using the longitudinal model to simplify dynamics for project use case. Once the script is optimized under disturbance testing, hardware implementations can be considered with cost of parts being of considerable interest.    

