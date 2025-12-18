# AGV Robotics Workshop

A comprehensive 2-day workshop covering theoretical concepts and hands-on implementation of autonomous ground vehicle robotics, including SLAM, path planning, control systems, and computer vision.

## Workshop Overview

### Duration
- **Day 1 (Saturday)**: Introduction, Theory, and Simulation Setup
- **Day 2 (Sunday)**: Hands-on Implementation and Integration

### Topics Covered
1. **SLAM** - Simultaneous Localization and Mapping (Hector SLAM)
2. **Path Planning** - RRT (Rapidly-exploring Random Trees)
3. **Control Systems** - Pure Pursuit Controller
4. **Computer Vision** - Camera Calibration, Lane Detection, YOLO Object Detection
5. **System Integration** - Navigation stack combining all components

## Repository Structure

```
AGV-Robotics-Workshop/
├── 00-Setup/                     # Installation and environment setup
│   ├── docker/                   # Docker environment configurations
│   ├── ros_installation/         # ROS/ROS2 installation guides
│   └── simulator_setup/          # F1tenth Gym and MVSim setup
│
├── 01-Theory/                    # Theoretical materials and slides
│   ├── slam/                     # SLAM concepts and slides
│   ├── path_planning/            # Path planning algorithms (RRT, etc.)
│   ├── controls/                 # Control theory (Pure Pursuit, Stanley)
│   ├── computer_vision/          # Classical CV techniques
│   └── deep_learning/            # Deep learning for perception
│
├── 02-Hands-on/                  # Implementation code and exercises
│   ├── slam_hector/              # Hector SLAM implementation
│   ├── path_planning_rrt/        # RRT path planning code
│   ├── controls_pure_pursuit/    # Pure Pursuit controller implementation
│   ├── cv_classical/             # Camera calibration, lane detection
│   └── cv_deep_learning/         # YOLO object detection
│
├── 03-Simulation/                # Simulation environments
│   ├── f1tenth_gym/              # F1tenth Gym setup and examples
│   ├── mvsim/                    # MVSim for ground robots
│   └── maps/                     # Map files for simulation
│
├── 04-Integration/               # Full system integration
│   ├── navigation_stack/         # Complete navigation framework
│   └── sensor_integration/       # Vision, Lidar, US, GPS, IMU integration
│
├── 05-Resources/                 # Additional materials
│   ├── datasets/                 # Training and testing datasets
│   └── reference_materials/      # Papers, documentation, links
│
└── 06-Evaluation/                # Testing and evaluation criteria
```

## Prerequisites

Participants should have:
- Basic understanding of Python programming
- Familiarity with Linux/Ubuntu
- Laptop with at least 8GB RAM and 50GB free disk space


## Getting Started

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd AGV-Robotics-Workshop
   ```

2. **Setup environment**
   - Follow instructions in `00-Setup/` for ROS/Docker installation
   - Install required simulators (F1tenth Gym, MVSim)

3. **Day 1: Theory and Setup**
   - Review theory materials in `01-Theory/`
   - Set up simulation environment in `03-Simulation/`

4. **Day 2: Hands-on Implementation**
   - Work through exercises in `02-Hands-on/`
   - Integrate components in `04-Integration/`

## Hardware/Sensors Used

The final integrated system will utilize:
1. Vision (Camera)
2. Lidar
3. Ultrasonic Sensors (US)
4. GPS Waypoints
5. IMU (Inertial Measurement Unit)

## Contact

For questions or issues, please contact the workshop instructors.
