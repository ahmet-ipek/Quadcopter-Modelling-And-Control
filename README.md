# Quadcopter-Modelling-And-Control

1. **Introduction**

A quadcopter is a multirotor aerial vehicle with four rotors, allowing it to hover, maneuver in 3D space, and maintain stability through precise control of thrust and torques. To simulate and control a quadcopter, understanding its dynamics is crucial. The equations governing the motion of the quadcopter are derived from fundamental principles, including Newton-Euler equations for rigid body dynamics.

The purpose of this section is to explain how the translational and rotational dynamics of the quadcopter are derived, with an emphasis on:

- Forces and moments acting on the quadcopter.
- Translational dynamics that govern the movement in 3D space.
- Rotational dynamics that control orientation (roll, pitch, and yaw).

These equations form the basis of the quadcopter’s simulation and control system, implemented in MATLAB and Simulink. They allow us to model the quadcopter's response to motor inputs, environmental forces, and trajectory-following commands.

2. Coordinate Frames

To describe the motion of the quadcopter, two coordinate frames are used:

2.1. Inertial Frame

The inertial frame is a fixed reference frame used to define the global position and orientation of the quadcopter. It is often represented as an Earth-centered frame:

Axes:
- X: Points North.
- Y: Points East.
- Z: Points Downward.

2.2. Body Frame

The body frame is a moving frame attached to the quadcopter's center of gravity (CoG). It rotates with the quadcopter:

Axes:
- x: Points forward.
- y: Points to the right.
- z: Points downward.


<p align="center">
  <img src="https://github.com/user-attachments/assets/65d30124-5033-4627-8e8d-f965a35f9d86" width="300" />
</p>

3. Forces Acting on the Quadcopter

   The motion of a quadcopter is governed by forces acting on it, primarily thrust, gravity, and aerodynamic drag. Understanding these forces is crucial for deriving the translational dynamics. Below, we explain each force in detail:
   
5. Moments Acting on the Quadcopter
6. Translational Dynamics
7. Rotational Dynamics
8. Implementation in Simulink

