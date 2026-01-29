# Contributing to URDFHUB

Thank you for your interest in contributing to URDFHUB! This guide explains how to submit robot models.

## Contribution Guidelines

### Submitting a Robot Model

1. **Fork** this repository
2. **Create a new directory** under `/robots/` with your robot name (lowercase, hyphenated)
3. **Include required files:**
   - `model.urdf` or `model.urdf.xacro` - The robot description
   - `README.md` - Documentation (see template below)
   - `meshes/` - Visual and collision meshes (STL or DAE)
   - `config/` - Any configuration files (joint limits, controllers)
   - `launch/` - ROS 2 launch files (optional but recommended)

4. **Submit a Pull Request** with:
   - Clear description of the robot
   - Simulator compatibility tested (Gazebo, Isaac Sim, etc.)
   - Any known limitations

### Robot README Template

# Robot Name

## Overview
Brief description of the robot.

## Specifications
- **DOF:** 
- **Payload:** 
- **Reach:** 

## Compatibility
- [ ] Gazebo Classic
- [ ] Gazebo (Ignition)
- [ ] Isaac Sim
- [ ] PyBullet
- [ ] MuJoCo
