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
  **Full research under embargo until 14/01/2028, key details may be missing**

# Problem statement
As microchips continue to shrink and production speeds increase, conventional vacuum pick-and-place systems face scaling limitations due to nozzle size constraints and clogging risks. In this project, I developed and validated a laser driven microchip propulsion mechanism that replaces vacuum gripping with a capillary adhesion using a water droplet, and a laser induced explosive evaporation of the droplet to propel the chip. 




The goal was to identify a safe and repeatable concept in which a laser rapidly generates water vapour inside of the water droplet, generating pressure enough to propel a 0.1 mm² die. The strict constraint is to do this without damaging the die or the boundry system.


## Methodology
The project combined multiphysics simulation and experimental validation.

A heat transfer model in COMSOL was developed to simulate pulsed Gaussian laser heating interating on the water ranging in parameters. The model mapped temperature evolution and identified the balance between sufficient heating and material damage.

Experimentally, I characterized laser fluence limits. By varying spot size and exposure conditions, I established a safe operating window in which explosive evaporation occurs without system or chip damage. High speed imaging (4000 fps) was used to analyze droplet dynamics and die motion, while post process microscopy was used to validate the surface integrity.


## Key findings
For the parameters, a robust operational window was identified. Within this window, repeatable die propulsion was achieved in under 10 ms with negligible lateral displacement and no observable bulk die damage. The study proved that controlled explosive evaporation can function as a reliable micro actuation mechanism without transitioning into destructive laser material interaction. 

## Engineering contribution
This work bridges thermodynamics, laser–material interaction, and microscale fluid dynamics to establish a physically validated propulsion mechanism. It translates theoretical superheating limits into a practical, experimentally confirmed parameter set suitable for system integration. The results provide a foundation for vacuum free microchip handling systems and scalable propulsion system for high throughput semiconductor manufacturing.











