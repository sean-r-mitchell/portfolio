---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.S. in Electrical Engineering, University of Alabama in Huntsville, 2021-2026 (Expected)
  * Minor: Mathematics
  * Focus: Dynamical Systems, Chaos Theory, and Machine Learning
  * Thesis: Influence of Entropy and Periodicity in Neural Network Training
      * Advisor: Dr. Aubrey Beal
      * ``Deep neural networks typically utilize psuedo-random number generation to populate the default states of neurons. Shown is an alternative approach that utilizes the non-linear dynamics that are present in one-dimensional mappings that exhibit chaos. These dynamics can be used to initialize the neurons and show equivalent or greater performance than traditional algorithms.``
* B.S. in Electrical Engineering, University of Alabama in Huntsville, 2015-2020
  * Minor: Computer Science
  * Focus: Mechatronics & Control Theory

Work experience
======
* 12/2024 -- Present: Lead Software Engineer, Cummings Aerospace, Huntsville, Alabama
  * Lead engineer supporting development of a family of high-speed, low-cost loitering S-UAS platforms. Responsible for software architecture, C2 integrations, and design of fire control and seeker subsystems
    * Architected and implemented flight software stack including guidance,
navigation, and control algorithms (nonlinear guidance, Kalman filtering,
multi-motor PID stabilization
    * Developed fire-control and ground-control systems (laptop and Android),
extending existing weapon interface standards to support new operational
behaviors
    * Integrated RF telemetry and sensor systems including custom packet protocols,
S-band radar interface, and a 6-DOF RF link margin simulation environment
    * Designed and integrated custom PCBs supporting telemetry,
power management, and peripheral interfacing
    * Established weapons integration laboratory including HWIL, SWIL, and vehicle
checkout infrastructure for rapid software and hardware testing

* 06/2023 -- 12/2024: Senior Software Engineer, Cummings Aerospace, Huntsville, Alabama
  * Supported modernization of mission-critical Ground Based Midcourse Defense
(GMD) command and control software infrastructure. Contributed to architectural transition from legacy Ada systems to a modular C++ microkernel architecture supporting containerized deployment and modern development workflows. Led a cross-functional engineering team delivering modernization capabilities for a large-scale defense system
    * Contributed to architecture redesign transitioning legacy Ada-based
software to modular C++ microkernel and microservice-based systems
    * Developed automated code-generation tooling to accelerate conversion
of legacy Ada code into modern C++ implementations
    * Maintained build systems, CI/CD pipelines, and containerized deployment
environments supporting Kubernetes-based infrastructure
    * Led a multidisciplinary team of 15 software and systems engineers,
increasing team delivery throughput by 43%
    * Coordinated system integration and technical progress with program
leadership and government stakeholders

* 01/2022 -- 05/2023: Electrical Design Engineer, Kratos Defense and Security Solutions, Huntsville, Alabama
  * Electrical and software systems engineer for PEGASUS, a tethered S-UAS platform. Served as software subteam lead and architect for distributed control, command-and-control infrastructure, and hardware/software integration across the tether station and vehicle systems
    * Architected distributed embedded computing system using multiple
Raspberry Pi nodes to support remote command, telemetry, and control
of a high-altitude tethered aerostat platform
    * Designed real-time control algorithms for synchronized dual-motor tether
payout capable of maintaining controlled slack while compensating for
vehicle velocity and altitude dynamics
    * Developed asynchronous distributed control architecture supporting
system communications, coordination, and command across vehicle and
ground subsystems
    * Implemented middleware pipeline integrating MAVLink and ATAK systems
via ZMQ to enable interoperability between UAS telemetry and tactical
command interfaces
    * Built automated sensor-data processing and analysis tools that reduced
post-mission data analysis from hours to minutes
    * Developed hardware-in-the-loop and software-in-the-loop test
infrastructure including endpoint device emulators and prototype
Android ground-control interfaces

Consulting Experience
======

Internship Experience
======

  
Skills
======
* Programming & Scripting
  * Python, C, C++, Java, MATLAB, Octave, Rust, Julia, Bash, LaTeX, R, Node.js, Ruby, Assembly, Ada, PHP, Javascript, Go, HTML, CSS, Javascript, Haskell, Lisp, Kotlin, Verilog, VHDL, Fortran   
* Software Architecture
  * Microservices, Microkernel, Event-Driven, Modular System Design, Embedded Software Architecture, Real-Time Software Design, MOSA/WOSA principles
* Machine Learning & AI
  * CNN, RNN, Transformer, GAN, PCA, LDA, Clustering, Reservoir Computing, Real-Time Sensor Data Processing, Embedded ML Applications, Automatic Target Recognition 
* Control \& Robotics
  * Robot Kinematics \& Dynamics, PID, Nonlinear Control, Kalman Filtering, Sensor Integration, ROS, Rapid Prototyping, Autonomous Vehicles
* ECAD 
  * Altium, KiCAD, LTSpice, Ngspice, Multisim, Vivado, Vitis, Quartus
* DevOps
  * Git, CMake, Ninja, Jenkins, Gradle, GitLab CI, Docker, Kubernetes, Doxygen
    
Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
