<img width="905" height="383" alt="image" src="https://github.com/user-attachments/assets/f6084c36-0f5d-4c22-9824-85c74c50ccef" />
# UR10e Mixed Reality

A Mixed Reality prototype built with Unity, running on Meta Quest 3. The Universal Robots UR10e industrial arm is imported from its official URDF data and placed into the user's real physical environment via passthrough, forming a foundation for maintenance training scenarios.

## About

This project covers the first stage of building a Mixed Reality environment where maintenance procedures for an industrial robot arm can be simulated virtually. The UR10e's official URDF and mesh data were used to import the robot's full joint hierarchy (base, shoulder, elbow, wrist 1-2-3) directly into Unity, scaled to real-world dimensions and placed inside the user's own room.

## Tech Stack

- Unity 6 (Universal Render Pipeline)
- Meta XR SDK / OpenXR
- Meta Quest 3 (Mixed Reality Template)
- Unity Robotics Hub - URDF Importer
- Universal Robots ROS2 Description (official UR10e URDF and mesh data)
- XR Interaction Toolkit

## Features

- Passthrough-based Mixed Reality view
- UR10e robot imported with its real joint hierarchy
- Realistic materials and coloring (silver body, blue joint bands)
- Basic hand-tracking interaction
- Real-world scale robot placement

## Setup

1. Clone the repository
2. Open the project in Unity 6 (or later)
3. Make sure the Android Build Support module is installed
4. Connect a Meta Quest 3 in Developer Mode via USB
5. Select the Android platform under `File > Build Profiles` and use `Build And Run` to deploy to the device

## Roadmap

- [x] Set up Unity and Meta Quest 3 development environment
- [x] Import the UR10e robot from its URDF
- [x] Realistic materials and coloring
- [ ] Interactive joint manipulation by hand
- [ ] Design the maintenance scenario (step-by-step procedure)
- [ ] Automatic placement on a real table/surface (Scene API)
- [ ] Evaluation and feedback system

## License

This project is intended for educational and prototyping purposes. Universal Robots URDF data is subject to its own license.
