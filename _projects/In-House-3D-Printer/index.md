---
layout: post
title: In house Large Scale 3D Printer
description: |
  When our research team at the Royal Netherlands Military Police lost the ability to print large scale parts due to an unreliable industrial printer, I led a full system redesign using only the existing frame as a starting point. By developing a new electronics architecture, motion system, and control software stack, I transformed a non functional machine into a reliable large manufacturing platform. The redesign increased usable print volume by over 500%, enabled secure network operation, and created a scalable platform capable of further expansion.

skills:
  - System architecture & integration
  - Mechatronic system design
  - Embedded electronics & wiring design
  - Firmware & motion control
  - Large-scale additive manufacturing
  - Hardware–software co-optimization
  - Reliability engineering

main-image: "/Printer 3.jpeg"
---




---


# Engineering Context
Large scale additive manufacturing was critical for our research activities, yet the existing industrial 3D printer had gradually become unusable. Poor print quality, unreliable operation, and difficult usability meant the system was ultimately abandoned. This created a major limitation: our maximum printable volume dropped from roughly 0.5 m³ to 0.05 m³, significantly restricting what we could build and test.

Rather than replacing the machine, we opted to rebuild it, since no good alternatives were available on the market for our applications. The objective was not simply repair, it was to transform the unused platform into a reliable, high performance system that could be operated safely through an encrypted server network while providing industrial print stability and speed.


## Engineering Challenge
Only the mechanical frame was worth keeping. Everything responsible for performance (e.g. motion hardware, electronics, control architecture, and software) needed to be redesigned.

This meant solving several problems simultaneously:
- Designing a new electrical and control architecture inside existing mechanical constraints
- Integrating custom and off the shelf hardware into a cohesive system
- Developing stable motion control for a large moving mass
- Achieving high speed printing without sacrificing dimensional accuracy
- Creating a system simple enough for daily research use

The real challenge was that hardware and software decisions were deeply coupled. Changing one parameter often required redesigning another part of the system.


## System Reconstruction
The project started with a complete teardown of the original machine. All legacy electronics and motion components were removed to create a clean design baseline. From there, I developed a new system architecture defining power distribution, motion control, sensing, and communication. Custom hardware components were designed to integrate motors, extruders, cooling systems, and control electronics into the existing frame while improving maintainability and accessibility.

On the software side, I built the control stack using Klipper firmware running on a Raspberry Pi, enabling distributed processing and flexible tuning of motion behavior. This allowed precise synchronization between components while supporting secure network-based operation for remote job deployment. At this stage, the printer could move, but high performance required a deeper iterative process.


## Hardware–Software Optimization
Once operational, the project shifted into an intensive optimization phase where mechanical design and firmware tuning evolved together. Large scale motion introduces the amplyfied effect of challenges from desktop printing: structural resonance, inertia driven vibration, flow instability, and accumulated positional errors. Solving these required simultaneous adjustments to hardware geometry and control algorithms.

Key areas of optimization included:
- Resonance analysis and input shaping
- Motion acceleration tuning
- Flow rate calibration at high speed
- Bed probing and large-area leveling strategies
- Mechanical redesign of critical components for stability

The process involved continuous iteration: redesigning hardware parts in CAD, validating prints, adjusting firmware parameters, and repeating until performance targets were met.

## Performace Outcome
The final system transformed an abandoned machine into a reliable research tool with substantial performance gains:

- 0.1 mm dimensional tolerance
- 30 cm²/s material flow capability
- 12,000 mm/s² maximum acceleration
- 0.3 mm maximum bed deviation across 600 × 600 mm
- ~0.25 m³ usable build volume

This represents more than a 500% increase in printable volume, with identified upgrade paths to reach approximately 1000% through minor future modifications.

## Engineering Impact
This project demonstrates system engineering; not only designing parts or software, but rebuilding and integrating an entire manufacturing platform from first principles. By combining mechanical redesign, electronics architecture, firmware development, and performance optimization, I converted a non functional machine into a maintainable production system. The result restored large scale additive manufacturing capability for the team.





