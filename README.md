# Hi, I'm Dewaraj Raparthi 👋

Robotics & Mechatronics engineer focused on embedded control systems, autonomous mechanisms, and simulation-driven design.

**Background**
- MSc, Robotics, Automation & Mechatronics — Stevens Institute of Technology (2026)
- BTech, Electronics & Communication Engineering
- Currently  open to robotics / mechatronics / embedded systems / automation roles

**What I build**
- 🐛 Bio-inspired locomotion — peristaltic/earthworm-style soft robotics modeled in MATLAB, studying segment contraction and gait control
- 🎛️ Control system simulation — Simulink models for robotic arena/motion scenarios
- 🤖 Autonomous systems and embedded control, from sensor integration to control logic

**Currently exploring**
- Control algorithms for mobile robotics
- Sensor fusion and real-time embedded systems

**Reach me**
- 📫 dewarajraparthi@gmail.com
- 🔗 [LinkedIn](https://www.linkedin.com/in/dewaraj-raparthi-0176a6257)
# Robotics Simulink Project — [Replace with actual project name]

## Overview
 A Simulink-based simulation of [system arena navigation mobile robot dynamics], modeling [ motion control sensor response path planning].

## Problem
[What real-world robotics problem does this address?]

## Approach
- Built in MATLAB/Simulink
- Model files: `.slx` Simulink models + `Plots.zip` 


## Method
[IT has decision making and path planning detects obstacles drops the objects on required locations]


## Tools
MATLAB, Simulink

## Why this matters
[ target  — control systems, automation, mobile robotics]

# Earthworm-Inspired Soft Robot — Peristaltic Locomotion Model

## Overview
A MATLAB-based model of earthworm-inspired peristaltic locomotion, simulating segment-by-segment contraction and expansion to generate crawling motion — the same actuation principle earthworms use to move through soil.

## Problem
Traditional wheeled/legged robots struggle in confined, irregular, or soft environments (pipes, rubble, tight gaps). Soft, peristaltic locomotion offers a way to navigate these spaces without rigid joints.

## Approach
- **`earthworm5.m`** — Core locomotion model; simulates the earthworm's body as a series of segments undergoing sequential contraction/expansion.
- **`peristaltic.m`** — Implements the peristaltic wave pattern driving forward motion.
- **`peristaltic_control_10v.m`** — Control logic for actuation, modeled at a 10V drive signal (likely representing a physical actuator/motor voltage constraint).
- **`locomotionPlot.m`** — Visualization of simulated motion/gait output over time.

## Method
 The model represents the robot body as discrete segments, applying a phase-delayed contraction pattern across segments to mimic peristaltic wave propagation, then plots resulting displacement/velocity.

## Results
 e.g. "Achieved stable forward crawling motion across N segments with a contraction phase delay of X, validated in simulation."

## Tools
MATLAB, mechanical/control system modeling

## Why this matters
Demonstrates bio-inspired mechanism design and control logic — transferable to soft robotics, confined-space inspection robots, and medical/endoscopic robotics applications.
