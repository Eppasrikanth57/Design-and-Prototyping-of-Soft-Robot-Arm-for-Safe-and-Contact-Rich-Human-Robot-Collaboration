# Design-and-Prototyping-of-Soft-Robot-Arm-for-Safe-and-Contact-Rich-Human-Robot-Collaboration
This repository contains the CAD designs, STL models, and embedded control code developed for my Master’s thesis at Hochschule Schmalkalden, Germany.
The project focuses on designing, building, and experimentally validating a vacuum-actuated soft robotic arm capable of safe, contact-rich human–robot collaboration.

The soft robotic arm is designed with modular flexible structures, granular-jamming-based variable stiffness, and multi-sensor feedback (force, proximity, and strain sensing). It offers a novel approach for achieving inherent safety in close human–robot interaction, aligning with the Industry 5.0 vision of human-centered manufacturing.

📁 Repository Structure

├── 2D Drawings/           # Technical manufacturing drawings of soft arm components

├── 3D CAD files/          # 3D part and assembly models designed in Solidworks 2022 and 2024

├── Coding/                # Arduino control code for actuation, sensing, and vacuum control

├── STL/                   # Exported STL files for 3D printing of structural components

├── LICENSE                # MIT License for academic and research use

└── README.md              # Project overview file

🛠️ Project Description

This thesis presents the complete design, prototyping, and validation of a motorized and vacuum-actuated soft robotic arm that dynamically changes stiffness using a Venturi-effect vacuum generator.
The system integrates force-sensing resistors (FSRs), time-of-flight (ToF) sensors, and foil strain gauges to perceive environmental interactions and respond safely to human contact.

Key Highlights:

Vacuum-Actuated Variable Stiffness:
Uses granular jamming via a Venturi-based vacuum generator to switch between soft and rigid modes.

Soft Structure & Additive Manufacturing:
Arm links and mounts fabricated using 3D printing and elastomeric materials for modularity and flexibility.

Multi-Sensor Integration:
Embedded FSRs, ToF sensors, and strain gauges enable adaptive response and safety behavior.

Microcontroller-Based Control:
An Arduino Mega 2560 manages pneumatic valves, sensors, and control logic for real-time adaptability.

Human-Robot Safety Compliance:
Experimental results confirm impact forces remain within ISO/TS 15066 biomechanical safety limits.

💻 Code Overview

The Coding/ folder includes Arduino programs written for system control and sensor integration.

Included functionalities:

Actuation control using low-power solenoid valves

Venturi vacuum generation for stiffness modulation

Real-time force and proximity sensing

Safety logic to reduce stiffness upon human approach

Hardware interfacing includes:

Arduino Mega 2560

Festo MYH-5/3G-M5-L-LED solenoid valves

ELEGOO 5V relay module

VL53LXX-V2 ToF sensor

Force-Sensitive Resistors and Strain Gauges

⚙️ Experimental Validation

The system was tested through multiple experiments:

Impact Tests: Collision safety assessment with varying vacuum pressures and bead fillings.

Tension Tests: Force-displacement behavior for soft and stiff states.

Comparative Tests: Impact forces benchmarked against a UR5e collaborative robot, confirming improved safety.

The prototype demonstrated smooth transition between compliant and stiff modes, validating its effectiveness for safe, contact-rich human interaction.

🧩 CAD and STL Files

3D CAD files/: Inventor models for soft arm prototypes, vacuum connectors, mounts, and baffles.

STL/: Printable versions of structural and interface components for 3D printing.

2D Drawings/: Engineering drawings with manufacturing dimensions and tolerances.

🔬 Applications

Human–Robot Collaboration (HRC)

Industrial manipulation and assembly

Healthcare and assistive robotics

Research and educational platforms

Service and domestic robotics

🧠 Research Focus

This repository supports research into:

Safe and adaptive soft robotic manipulators

Vacuum-based variable stiffness mechanisms

Multi-sensor fusion for human-aware robot control

Design methodologies for Industry 5.0 systems

🖌️ Licensing

This project is released under the MIT License.
All contents are free to use for academic, research, and personal learning purposes.
Commercial use requires prior written permission.

👨‍🎓 Author

Srikanth Reddy Eppa

M.Eng. Mechatronics and Robotics

Hochschule Schmalkalden, Germany

📧 Contact: For academic inquiries, feedback, or collaboration, feel free to reach out via [LinkedIn](https://www.linkedin.com/in/srikanth-reddy-eppa/) or contact through university channels.
