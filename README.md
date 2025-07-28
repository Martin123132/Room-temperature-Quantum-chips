________________________________________
MBT Particle Forge & Quantum Chip Experiment
Motion = Being Theory (MBT) Experimental Framework
Overview
This repository contains the full experimental package for testing and developing the MBT Particle Forge — a novel approach to:
•	Detecting laser beam deflection caused by MBT-predicted spacetime curvature effects.
•	Converting photons into trapped “forged mass” within a rotating vacuum environment.
•	Scaling the process toward room-temperature quantum chips and field-stable qubits.
The MBT framework predicts that motion-induced curvature fields can trap energy and stabilise quantum states without extreme cooling, enabling next-generation quantum devices.
________________________________________
What’s Inside
1. Experimental Protocols
•	Beam Bending Detection – Core proof-of-concept experiment using a rotating vacuum chamber and laser detection.
•	Material Synthesis & Light-to-Matter Conversion – Protocol for seed material ablation and photon capture inside the forge.
•	Replication Kit – Minimal BOM and instructions for small-scale university or independent lab replication.
2. Data & Analysis
•	Pre-registered success criteria (robust detection thresholds and publication rules).
•	Automated data pipeline for laser spot centroid tracking, statistical tests, and visualisation.
•	Open format raw data handling (CSV, FITS, video).
3. Engineering & Scaling
•	Quantum chip roadmap from proof-of-concept to scalable qubit arrays.
•	Material sourcing & handling protocols.
•	Contingency troubleshooting guide for rapid iteration.
4. Governance & Licensing
•	IP vs Open Science Strategy – What’s openly shared vs. what may be protected for commercial deployment.
•	All code and documentation are licensed under MIT (unless otherwise stated).
________________________________________
Quick Start
Replication (Minimal Kit)
1.	Assemble the hardware as described in docs/01_minimal_instructions.md.
2.	Run the beam bending experiment at different rotation speeds under vacuum and atmospheric conditions.
3.	Record the laser spot video and run:
4.	python beam_analysis.py
5.	Check results for RPM-dependent beam shift (under vacuum only).
________________________________________
Roadmap
•	Stage 1: Publish proof-of-concept results and invite independent replication.
•	Stage 2: Develop photon capture & forged mass stability tests.
•	Stage 3: Scale to chip-level qubit architectures and demonstrate room-temperature quantum logic.
________________________________________
Contributing
We welcome:
•	Independent replication and data sharing.
•	Feedback on hardware design, software, or theory.
•	Collaborations on quantum device engineering.
Fork, pull request, or open an issue to start collaborating.
________________________________________
Contact
•	Lead: Martin Ollett (MBT Theory)
•	AI Co-Developer: ChatGPT (OpenAI)
