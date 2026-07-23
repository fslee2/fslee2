# Yujie Pang / fslee2

Robotics, tactile manipulation, teleoperation, and embodied AI experiments.

I am currently building practical robot manipulation systems around MuJoCo, ROS2, camera-based teleoperation, tactile contact control, and dexterous robot hands.

## Lab Robotics Portfolio

### Real Robot Setup

![Real robot tactile manipulation setup](assets/lab/real_robot_setup.jpg)

### Real-to-Sim Manipulation

![Real-to-simulation abstraction for contact manipulation](assets/lab/real_to_sim_abstraction.jpg)

| Simulation spawn setup | Contact observation |
|---|---|
| ![Robot simulation spawn setup](assets/lab/robot_simulation_spawn.jpg) | ![Tactile contact closeup](assets/lab/tactile_contact_closeup.jpg) |

### Tactile Control Results

| Touch coverage | Force-safety comparison |
|---|---|
| ![Touch coverage distribution](assets/lab/touch_coverage_distribution.jpg) | ![Force safety comparison](assets/lab/force_safety_comparison.jpg) |

## Current Focus

- Real robot manipulation with tactile/contact feedback.
- Real-to-simulation abstraction for contact-rich manipulation tasks.
- MuJoCo task environments for robot teleoperation and policy testing.
- Human input interfaces using cameras, keyboard control, and VR experiments.
- Lightweight alternatives to heavy monocular 3D hand reconstruction.
- Imitation learning and robot-control pipelines.

## Featured Projects

| Project | What it contains | Stack |
|---|---|---|
| [cr3-craft-teleop-showcase](https://github.com/fslee2/cr3-craft-teleop-showcase) | CR3 + CRAFT DexJoCo integration, teleop scripts, and handoff notes | Python, MuJoCo, DexJoCo |
| [cr3-robot-description-assets](https://github.com/fslee2/cr3-robot-description-assets) | MuJoCo XML / MJCF and URDF assets for CR3 + CRAFT simulation | MuJoCo, URDF, ROS2 |
| [Dobot-CraftHand](https://github.com/fslee2/Dobot-CraftHand) | CRAFT hand and robot-control experiments | Python |
| [Lerobot_robomimic](https://github.com/fslee2/Lerobot_robomimic) | Robot learning and imitation-learning experiments | Python |
| [JetArm-Dummy](https://github.com/fslee2/JetArm-Dummy) | Master-slave teleoperation between JetArm and Dummy | C |

## Main Robotics Stack

```text
Simulation      MuJoCo, DexJoCo
Robot assets    MJCF/XML, URDF, STL, MoveIt config
Teleoperation   MediaPipe, cameras, keyboard control, VR experiments
Robot learning  imitation learning, robomimic, LeRobot-style pipelines
Languages       Python, C/C++, shell scripting
Tools           GitHub, ROS2, uv, conda, WSL, Windows
```

## Recent Work

The main recent work is centered on practical robot manipulation:

- built and documented real-to-simulation abstractions for contact manipulation;
- organized tactile manipulation visuals, contact observations, and force-safety results;
- extracted and organized CR3 robot-description assets;
- prepared reusable MuJoCo XML / MJCF entry points;
- tested camera and keyboard teleoperation entry scripts;
- documented handoff notes for Windows/WSL setup.

Start here:

- [CR3 + CRAFT Teleop Showcase](https://github.com/fslee2/cr3-craft-teleop-showcase)
- [CR3 MuJoCo / URDF Assets](https://github.com/fslee2/cr3-robot-description-assets)
