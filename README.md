# px4_ctrl_sim

> B-Spline Trajectory Tracking with Simulated UAV Dynamics and Modular Controller Framework

This repository simulates trajectory tracking for quadrotor-like aerial vehicles using B-spline path interpolation and a simplified dynamic model inspired by PX4 flight stack architecture. It provides a mock drone simulator, a modular control framework (supporting PID and placeholder MPC), and real-time visualization.

It is ideal for prototyping controller logic, debugging trajectory-following algorithms, or serving as an educational/research scaffold for aerial motion planning.

## 🔧 System Components

- 🛩️ **`drone.py`**: 6-DOF kinematic simulator for a UAV model
- 🎯 **`trajectory.py`**: B-spline interpolation and trajectory generator
- 🎮 **`controller.py`**: Modular control interface with mock PID and MPC stubs
- 📊 **`visualization/plot_trajectory.py`**: 2D/3D trajectory rendering using matplotlib
- 🔁 Designed for future integration with planning and mapping stacks

## ✨ Features

- Plug-and-play controller interface (PID / initial MPC attempts)
- Configurable drone dynamics and state update loop
- Realistic simulation of tracking deviation and control response
- Visualization of ground truth vs predicted trajectory

## 🔬 Applications

- Research on trajectory tracking and model-based control for UAVs
- Educational demos of control loop structure for drones
- Benchmarking control response under trajectory perturbations

## 📦 Folder Structure
```bash
px4_ctrl_sim/
├── sim/
│ ├── drone.py
│ ├── trajectory.py
│ └── controller.py
├── scripts/
│ └── run_sim.py
├── visualization/
│ └── plot_trajectory.py
├── tests/
│ └── test_sim.py
├── requirements.txt
└── README.md
```

## 🛠️ Installation

```bash
pip install -r requirements.txt
