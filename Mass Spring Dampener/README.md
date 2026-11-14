\# 1-DOF Mass-Spring-Dampener Dynamic Simulation





\## Project Overview

This project models and simulates the dynamic response of a single-degree-of-freedom linear mass-spring-dampener system using MATLAB. Systems of this type are fundamental in mechatronics and mechanical engineering, serving as the foundational mathematical model for vehicle suspensions, robotic arm joints, and vibration isolation platforms.



\## Mathematical Equations Used

The physical system is governed by a second linear order differential equation:



m\*x'' + c\*x' + k\*x = F

\#State Equation : dx1/dt = x2



dx2/dt = (F - c\*x2 - k\*x1) / m

\#Implemented in MATLAB using anonymous function and ODE.

