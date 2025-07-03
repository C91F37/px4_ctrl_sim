<<<<<<< HEAD
# esdf_mapper_demo

> Efficient ESDF Mapping from Voxelized Sensor Input

This repository implements a lightweight, CPU-friendly Euclidean Signed Distance Field (ESDF) construction pipeline inspired by [Voxblox](https://github.com/ethz-asl/voxblox), tailored for academic benchmarking and algorithm prototyping in autonomous navigation contexts.

It simulates real-time occupancy grid generation and ESDF propagation on 2.5D slices, supporting modular integration into higher-level planning frameworks such as A*, RRT*, or kinodynamic sampling-based methods.

## ✨ Features

- Minimalistic 3D voxel map representation with efficient memory layout
- Modular architecture for ESDF update cycles and obstacle injection
- Visualization via `numpy` + `PIL` to render signed distance field slices
- Designed for fast prototyping, supports batch experiments for distance transform accuracy

## 📌 Applications

- Autonomous ground/aerial robotics (as mapping front-end)
- Validation of ESDF-based planning algorithms under voxel constraints
- Teaching, research, or interview demonstration of spatial map construction

## 🛠️ Installation

```bash
pip install -r requirements.txt
=======
<pre lang="markdown"><code># px4_ctrl_sim – Trajectory Tracking Control via Simplified PX4-Inspired UAV Kinematics ## Overview This repository simulates trajectory tracking for a quadrotor-like vehicle using B-spline generated paths. Inspired by simplified PX4 dynamics and control architecture, it features a fake drone model with tunable physics and a pluggable controller API, facilitating experimentation with feedback control strategies. ## Features - ✈️ Lightweight `drone.py` dynamics simulator (6-DOF simplified kinematics) - 📈 B-spline trajectory generation and temporal parametrization - 🎮 Plug-and-play controller module: includes mock PID, supports MPC stub - 📊 Real-time 2D visualization of tracking performance with `matplotlib` ## Suggested Use Cases - MPC, PID, or LQR trajectory tracking controller prototyping - UAV control policy debugging without requiring PX4 or ROS stack - Educational demos on model-based control and trajectory following </code></pre>
>>>>>>> feb7596 (init: project structure for px4_ctrl_sim)
