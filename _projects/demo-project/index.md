---
layout: post
title: Laser Based Chip Propulsion
description: |
  **Full research under embargo until 14/01/2028, key details may be missing**

  Microchip handling systems face scaling limitations as chips shrink and production speeds increase. Conventional vacuum pick and place systems are constrained by nozzle size and clogging risks, making them infeasible for further scaling. During my research, I developed a new handling method using capillary-based water droplets and laser-driven propulsion to transfer microchips, designing and experimentally validating a method that converts laser energy into controlled chip propulsion. I performed coupled simulations and lab experiments to optimize system parameters, demonstrating a scalable approach that increases chip handling speed by over 60%, and that can be applied to a wide scale of chip sizes. This research forms the foundation for controlled implementation of a water–laser-based semiconductor handling system into practice.

skills:
  - Micro systems design
  - Multiphysics simulation
  - System parameter optimization
  - Experimental validation & lab testing
  - Concept to prototype R&D execution
  - Opto mechanical design
  - Laser system design

main-image: "/Cover page 4.jpg"
---



---


# Problem statement
As microchips continue to shrink and production speeds increase, conventional vacuum pick-and-place systems face scaling limitations due to nozzle size constraints and clogging risks. In this project, I developed and validated a laser driven microchip propulsion mechanism that replaces vacuum gripping with a capillary adhesion using a water droplet, and a laser induced explosive evaporation of the droplet to propel the chip. 


{% include image-gallery.html images="Laser pick and place.png" height="200" %} 


The goal was to identify a safe and repeatable concept in which a laser rapidly generates water vapour inside of the water droplet, generating pressure enough to propel a 0.1 mm² die. The strict constraint is to do this without damaging the die or the boundry system.


## Methodology
The project combined multiphysics simulation and experimental validation.

A heat transfer model in COMSOL was developed to simulate pulsed Gaussian laser heating interating on the water ranging in parameters. The model mapped temperature evolution and identified the balance between sufficient heating and material damage.

Experimentally, I characterized laser fluence limits. By varying spot size and exposure conditions, I established a safe operating window in which explosive evaporation occurs without system or chip damage. High speed imaging (4000 fps) was used to analyze droplet dynamics and die motion, while post process microscopy was used to validate the surface integrity.


## Key findings
For the parameters, a robust operational window was identified. Within this window, repeatable die propulsion was achieved in under 10 ms with negligible lateral displacement and no observable bulk die damage. The study proved that controlled explosive evaporation can function as a reliable micro actuation mechanism without transitioning into destructive laser material interaction. 

## Engineering contribution
This work bridges thermodynamics, laser–material interaction, and microscale fluid dynamics to establish a physically validated propulsion mechanism. It translates theoretical superheating limits into a practical, experimentally confirmed parameter set suitable for system integration. The results provide a foundation for vacuum free microchip handling systems and scalable propulsion system for high throughput semiconductor manufacturing.









