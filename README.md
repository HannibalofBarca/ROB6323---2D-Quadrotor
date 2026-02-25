  # ROB6323---2D-Quadrotor
IPython notebook demo for the rob6323 reinforcement learning and optimal control course. Implementations SQP and MPC controller 

https://github.com/user-attachments/assets/33cfa0ae-1746-4df8-a58e-203d7cdf7f79

# Quadrotor Model Predictive Control

This project implements a control system for a 2D quadrotor to perform a loop using Sequential Quadratic Programming (SQP) and Model Predictive Control (MPC).

* **Sequential Quadratic Programming (SQP):** A custom SQP solver is implemented to solve the nonlinear trajectory optimization problem, determining the ideal set of states and controls to complete the loop.
* **Model Predictive Control (MPC):** A nonlinear MPC controller uses the optimized trajectory as a reference, recalculating control actions to maintain stability and handle external disturbances.

## Requirements
* `numpy`
* `matplotlib`
* `qpsolvers`
* `scipy`
