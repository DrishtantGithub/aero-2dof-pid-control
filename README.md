# EE615:PID Control of Pitch and Yaw in Aero 2-DoF System

## 📌 Overview
This project focuses on designing and implementing **PID/PD controllers** for pitch and yaw regulation in the Aero 2-DoF system. Both **MATLAB/Simulink simulations** and **real-time hardware implementation** were performed to validate the control strategy.

## ⚡ Objectives
- Model and derive transfer functions for the Aero 2-DoF system.
- Design PID/PD controllers using time-domain specifications (overshoot, peak time).
- Simulate and validate performance in MATLAB/Simulink before hardware deployment.

## 🛠️ Methodology
- **System Modeling:** Transfer functions for pitch and yaw derived from system dynamics.
- **Controller Design:** PID/PD gains tuned based on overshoot and peak-time constraints.
- **Simulation:** Closed-loop dynamics tested in MATLAB/Simulink.
- **Implementation:** Controllers deployed on Aero 2-DoF hardware for real-time validation.

## 📊 Results
- Achieved **< 5% peak overshoot** and **fast settling time** in simulations.  
- Hardware implementation showed **stable pitch–yaw regulation** under real-time conditions.  
- Highlighted the **scope for robustness improvements** via integral action in hardware. 
