---
layout: post
title: AVL Drivingcube for Heavy Duty Trucks
description: |
  The AVL Drivingcube is a vehicle-in-the-loop (ViL) validation system for ADAS and autonomous driving features, allowing real, ready to drive vehicles to be tested in a safe, virtual, and simulated environment. For the AVL Drivingcube vehicle dynamics testbed, I developed a mechanical actuator system capable of simulating real steering forces on heavy trucks without physically turning the wheels. The project required designing a high stiffness mechanism capable of handling loads up to 30 kN while remaining mountable within severe packaging constraints. Through iterative concept evaluation, structural FEM validation, and mechanical system design, I developed a scalable actuator architecture enabling controlled and repeatable steering simulations for advanced vehicle testing.

skills:
  - Mechanical system architecture
  - Concept development & evaluation
  - Force flow analysis
  - FEM structural & frequency analysis
  - Mechanism design
  - Vehicle integration design
  - Design for stiffness & compliance


main-image: "AVL-drivingcube.jpg"
---



---
# Engineering Context
The AVL Drivingcube is a vehicle dynamics test platform used to evaluate truck behaviour under controlled laboratory conditions. However, when trucks are placed on a dyno or chassis testbed, the wheels cannot physically steer, making it impossible to study steering effort or driver input effects.

The goal of this project was to create a ViL actuator system capable of simulating real steering forces while mechanically decoupling the wheels. This required replacing the traditional drag link with a custom mechanical system that reproduces steering effort without affecting wheel position.


## Engineering Challenge
The problem quickly evolved from a simple mechanism into a multi constraint problem:

- Simulate realistic steering loads up to 30 kN
- Operate within very limited space beneath the truck
- Maintain structural stiffness under high dynamic loads
- Avoid transferring harmful forces into the testbed
- Support multiple truck geometries
- Allow installation and maintenance accessibility

The system had to behave as if the truck was steering on the road, while physically remaining fixed on the test platform.


## Concept Strategy
Early development revealed that force flow management was the defining problem of the project. Two fundamentally different concepts were evaluated:

### Platform Concept

A rigid platform mounted partly to the ground, allowing controlled translations through bearings and springs.

Advantages: 

- High stiffness
- Simple structural logic

Limitations

- Heavy and difficult to install
- Limited compatibility across testbeds
- Poor packaging for chassis test environments

### Closed Force Loop Concept

Inspired by steering simulation systems used in passenger vehicles, I designed a closed force loop architecture where all loads remain inside the system and no major forces transfer to the ground.

This approach:

- Reduced weight dramatically
- Improved installation flexibility
- Allowed use across multiple testbeds
- Created a mechanically cleaner load path

Selecting this concept defined the rest of the project and shifted focus toward achieving stiffness through structural design rather than external supports. 


## Mechanism Development
With the system architecture defined, the next challenge was translating the drag-link motion into actuator input while keeping the actuator close to the mounting points to maximize rigidity. Multiple translation mechanisms were explored, where the final solution combined a Scott-Russell linkage with a lever system, enabling motion redirection while maintaining compact packaging and favorable weight distribution. This allowed the actuator to remain near the structural core, significantly improving system stiffness.


## Structural Engineering & Validation
As design complexity increased, structural dynamics became the critical risk factor. Initial structures proved insufficient, as eigenfrequency targets could not be achieved. I redesigned the framework using an X-profile structural architecture, increasing stiffness to weight ratio while preserving modular assembly.

FEM analysis guided each design iteration, focusing on stress distribution under peak steering forces, structural rigidity and frequency response. The final configuration achieved a minimum eigenfrequency of 105 Hz, exceeding the target requirement of 100 Hz and validating the concept for further development

## Performace Outcome
The final concept produced a mechanically robust steering simulation system capable of replicating steering forces without wheel movement, maintaining a closed internal force loop, supporting high load truck configurations, integrating within severe packaging constraints and providing a modular basis for future actuator integration. The design established a validated mechanical foundation for steering effort simulation on heavy vehicles within the Drivingcube ecosystem

## Engineering Impact
This project demonstrates high-level mechanical systems engineering, translating abstract principles into real hardware whilst balancing stiffness, compliance, and packaging simultaneously. Rather than designing a single mechanism, my work established a complete structural and kinematic framework that allows realistic steering simulation under controlled laboratory conditions. 










