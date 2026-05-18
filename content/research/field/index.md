---
title: Field Robotics
toc: true
reading_time: false
pager: false
show_date: false
authors: [marcocamurri, michelefocchi, andreadelprete, tommasofaraci, pietronoahcrestaz, elisaalboni, eliasfontanari, davidedemartini, luigipalopoli, danielefontanelli]
summary: |-
 Field robotics deals with the fundamentals and applications of mobile robots operating in unstructured and dynamic environments.
---

## Overview

 Field robotics deals with the fundamentals and applications of mobile robots operating in unstructured and dynamic environments, where conditions cannot be controlled. Applications include, but are not limited to: **precision agriforestry**, **construction**, **space exploration**, and **industrial inspection**. Our research focuses on the development of novel algorithms for perception, planning and control of mobile robots (tracked, wheeled, legged), parameter modeling and system identification (e.g., slippage in tracked robots on slopes), as well as novel unconventional robot designs (e.g., roped-legged). 



### Cooperative Aerial Manipulation

CO-FAST, standing for “Cooperative and Optimization-based Framework for Aerial Manipulation,” introduces a complete framework for the control and planning of cooperative aerial manipulation using swarms of drones connected to loads through motorized cables. Each drone (UAV) is equipped with electrically driven winches that allow adjustment of cable lengths to manipulate the load. This configuration forms a floating-base parallel kinematic structure enabling precise 6D manipulation while simplifying swarm formation control. The ability to adjust cable lengths introduces additional degrees of freedom, allowing load manipulation (such as orientation or height variations) to be decoupled from the swarm flight configuration. Furthermore, the capability to dynamically modify swarm geometry increases robustness against environmental disturbances such as wind and turbulence, improves aerodynamic efficiency inspired by bird flocking behavior, and enables modulation of the overall system stiffness. This feature provides unprecedented positioning accuracy when required, while also enabling acceleration and deceleration of the load without inducing unwanted oscillations. CO-FAST can enable innovative wildfire suppression strategies and has applications in transportation, handling, and automated assembly of loads in construction sites and remote areas.

![](https://github.com/idra-lab/idra-lab.github.io/blob/044f6864b802e3c2b5f70d7f74762174c5656103/content/research/field/cargo_system.png)

![](https://github.com/idra-lab/idra-lab.github.io/blob/044f6864b802e3c2b5f70d7f74762174c5656103/content/research/field/antenna_assembly.png)

![](https://github.com/idra-lab/idra-lab.github.io/blob/044f6864b802e3c2b5f70d7f74762174c5656103/content/research/field/fire_suppression_cycle.png)

### 

### Control and Planning of Tracked Vehicles

Tracked vehicles distribute their weight continuously over a large  surface area (the tracks). This distinctive feature makes them the  preferred choice for vehicles required to traverse soft and uneven  terrain. From a robotics perspective, however, this flexibility comes at a cost: the complexity of modelling the system and the resulting  difficulty in designing theoretically sound navigation solutions. In  this research we aim to bridge this gap by proposing a framework for the  navigation of tracked vehicles, built upon three key pillars. The first  pillar comprises two models: a simulation model and a control-oriented  model. The simulation model captures the intricate terramechanics  dynamics arising from soil-track interaction and is employed to develop  faithful digital twins of the system across a wide range of operating  conditions. The control-oriented model is pseudo-kinematic and  mathematically tractable, enabling the design of efficient and  theoretically robust control schemes. The second pillar is a  Lyapunov-based feedback trajectory controller that provides certifiable  tracking guarantees. The third pillar is a portfolio of motion planning  solutions, each offering different complexity-accuracy trade-offs. 

![trached vehicle simulation](https://github.com/idra-lab/idra-lab.github.io/blob/677359b8e5b70fd4ee8f8313f7cf920a03ede5d6/content/research/field/distributed_sim.png)



### Prototyping and Development of Climbing Robots

In addition to theoretical research, our group is also involved in the prototyping and development of advanced robotic systems designed for a variety of applications. One of these projects is the creation of a climbing robot, Alpine, developed with the goal of reducing human presence in difficult or hazardous environments.

![ALPINE](https://github.com/idra-lab/idra-lab.github.io/blob/044f6864b802e3c2b5f70d7f74762174c5656103/content/research/field/alpine.jpg)

By implementing advanced optimization systems, the robot is capable of avoiding obstacles and navigating complex environments in a semi-autonomous or fully autonomous manner.
This system enables analysis, maintenance, and inspection operations in high-risk environments such as rock walls,is specifically designed to carry heavy tools, remain stationary without consuming energy, thereby minimizing direct human exposure to extreme conditions.
The development of this prototype required the integration of multiple multidisciplinary skills, including:

- **Mechanical engineering**: design and construction of the climbing robot structure, involving knowledge of pneumatics, applied physics, and 3D modeling.
- **Electronics and mechatronics**: selection and integration of sensors and actuators necessary for the robot’s operation and stability.
- **Computer science and robotics**: development of control and navigation software, including computer vision algorithms for environment recognition, surface classification, and foreign object detection, as well as optimization algorithms for path planning.
- **Supervision and remote control systems**: development of a web application for real-time monitoring and remote operation of the robot, allowing operators to supervise tasks and intervene safely and efficiently.

![](https://github.com/idra-lab/idra-lab.github.io/blob/044f6864b802e3c2b5f70d7f74762174c5656103/content/research/field/cad_winch.jpeg)

![](https://github.com/idra-lab/idra-lab.github.io/blob/044f6864b802e3c2b5f70d7f74762174c5656103/content/research/field/use_case_new_square.png)

An explanatory video of the project can be found [here](https://www.youtube.com/watch?v=dRgj9493DnM).

The  webpage of the WIKI of the project can be found here: [https://github.com/alpine-robot](https://github.com/alpine-roboth).

#### The Climbing Robot Team

- [Michele Focchi](/author/michele-focchi/) - Professor
- Ruben Malacarne - Student
- Luca Hardonk - Student
