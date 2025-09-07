# Mechanical Vibrations – Wind Turbine Structure Analysis

This project studies the vibrational behavior of a simplified wind turbine model.  
The system is modeled with concentrated masses, flexible beams, and rotating blades, and is analyzed using MATLAB for natural frequencies, mode shapes, and forced responses.  
Additional simulations in MSC ADAMS and MATLAB Simulink are used for validation.

---

## Project Overview
The wind turbine is simplified into:
- Four concentrated masses connected by two flexible beams (clamped–clamped boundary condition).
- Two additional flexible beams with point masses at their tips, representing the turbine blades, attached to the fourth mass.
- The blades are allowed to rotate and bend, capturing their vibrational behavior.

The objective is to build a mechanical and mathematical model, compute vibration characteristics, and simulate system responses under external forces.

---

## Necessary Tasks
1. **Mechanical Modeling**
   - Sketch the equivalent system using masses, springs, and dampers.
   - Define assumptions and parameters for a simplified 2D model.

2. **Natural Frequencies and Mode Shapes**
   - Formulate the mass and stiffness matrices.
   - Solve the eigenvalue problem to obtain natural frequencies and mode shapes.
   - Plot mode shapes using MATLAB.

3. **Forced Response**
   - Implement the system equations in MATLAB using `ode45`.
   - Simulate the forced response of the system under harmonic excitation.
   - Plot the displacement response for all degrees of freedom.

4. **Mode Excitation**
   - Determine a set of initial displacements that excites only the third vibration mode.

---

## Extra Tasks
- **MSC ADAMS Simulation**  
  Simulate the system to validate MATLAB results and compare responses.

- **MATLAB Simulink Simulation**  
  Build a block diagram model and obtain the forced response through simulation.

- **Extended Analysis**  
  - Plot forced response of all degrees of freedom individually.
  - Re-compute and compare natural frequencies across different platforms.
