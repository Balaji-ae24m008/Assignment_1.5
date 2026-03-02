# AS5420 – Introduction to Computational Fluid Dynamics  
## Assignment 1.5

---

## 📌 Assignment Description

This assignment focuses on:

1. Constructing Butcher Tableaus for various Runge–Kutta (RK) methods.
2. Implementing a fourth-order Runge–Kutta (RK4) method to solve the Lorenz system.
3. Visualizing the phase-space trajectory of the Lorenz attractor.

---

# 📝 Question 1  
## Butcher Tableau Construction

Construct the Butcher Tableau for the following Runge–Kutta methods:

- RK1 (Forward Euler)
- RK2
- RK3
- RK4
- RK5
- RK6


# 📝 Question 2  
## Numerical Integration of the Lorenz System

The Lorenz system is defined by the following nonlinear ordinary differential equations:

dx/dt = σ (y − x)

dy/dt = x (ρ − z) − y

dz/dt = x y − β z

---

## 📌 Parameters

σ = 10  
ρ = 28  
β = 8/3  

---

## 📌 Initial Conditions

x(0) = 1.0  
y(0) = 1.0  
z(0) = 1.0  

---

## 🔹 Task (a): RK4 Implementation

- Implement the 4th Order Runge–Kutta (RK4) method.
- Programming language: Python or C++
- Time interval: t ∈ [0, 50]
- Time step: Δt = 0.01


## 🔹 Task (b): Phase-Space Plot


## 📂 Submission Requirements

- Source code (Python or C++)
- Clearly labeled plots
- Proper documentation
- Clean implementation

---

## 📊 Expected Results

- Time evolution of x(t), y(t), z(t)
- 3D chaotic Lorenz attractor visualization
- Verified RK4 implementation

---

