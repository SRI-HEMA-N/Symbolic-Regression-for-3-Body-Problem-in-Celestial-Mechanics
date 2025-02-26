# 🌌 Symbolic Regression for 3 Body Problem in Celestial Mechanics

## 📌 Overview
This project simulates the 3-body problem in celestial mechanics and uses symbolic regression to discover mathematical expressions that describe the motion of the bodies. It combines physics, numerical simulation, and machine learning to explore the chaotic behavior of celestial systems.

## 🌟 What is the 3-Body Problem?
The 3-body problem is a classic problem in physics that describes the motion of three celestial bodies (like planets or stars) under the influence of gravity. Unlike the 2-body problem, which has a simple solution, the 3-body problem is chaotic and does not have a general analytical solution. This project uses numerical methods to simulate the motion of three bodies and applies symbolic regression to approximate their trajectories.

## 🚀 What Does This Code Do?
Simulates the 3-Body Problem:

The code solves the equations of motion for three bodies using numerical integration (scipy.integrate.solve_ivp).
It calculates the positions and velocities of the bodies over time.

Visualizes the Motion:
The code creates a 3D animation of the bodies moving in space.
The animation is saved as a video file (3_body_simulation.mp4).

Applies Symbolic Regression:
The code uses symbolic regression (via gplearn) to find mathematical expressions that approximate the motion of each body.
It evaluates the accuracy of these expressions and compares them to the actual trajectories.

Outputs Results:
The best symbolic expressions for each body's motion are printed.
Plots are generated to compare the predicted and actual trajectories.

## 🛠️ Tools and Libraries Used
Numerical Simulation: scipy.integrate.solve_ivp
Symbolic Regression: gplearn.genetic.SymbolicRegressor
Visualization: matplotlib (3D plots and animation)
Data Handling: numpy, sklearn


## ⚙️ How It Works (Real-Time Functionality)
1. **Physics Model**: Uses Newton's second law and gravitational equations to compute the acceleration of each body.
2. **Numerical Integration**: Solves the differential equations using numerical methods (e.g., Euler or Runge-Kutta).
3. **Visualization**: Plots the paths of the celestial bodies in real time, showing their chaotic motion.




https://github.com/user-attachments/assets/36cfebc2-cd77-43cc-8907-c9d4228e4b23


Enjoy exploring the universe! 🌠
