# Safety and Security of Autonomous Vehicles: Risk-Aware Control, Adversarial Threats, and Automotive Standards


**Proposed half-day tutorial · IEEE Intelligent Vehicles Symposium (IV 2027)**  
**Duration:** 3.5 hours (210 minutes) · **Status:** Proposed; subject to conference acceptance and scheduling  
**Organizers and presenters:** Prof. Qadeer Ahmed and Dr. Sidra Bhatti, The Ohio State University

## Overview

Autonomous vehicles rely on tightly coupled sensing, state estimation, communication, and feedback control. Measurement uncertainty, faults, and deliberate cyber manipulation can all affect safety-critical vehicle behavior. This tutorial brings **safety and cybersecurity together through a dynamical-systems perspective**, progressing from mathematical foundations to real-world vehicle and hardware-in-the-loop research, with a practical orientation to automotive assurance standards.

Participants will explore the different ways uncertain and adversarial information enters an autonomy stack, the assumptions behind safety-critical control and intrusion detection methods, and the challenges of engineering resilient and trustworthy vehicles.

## Who should attend?

Graduate students, academic researchers, and automotive practitioners working in autonomous systems, vehicle controls, robotics, intelligent transportation, AI, or cybersecurity. Familiarity with basic linear algebra, probability, and feedback control is helpful; specialized knowledge of safety barrier functions or automotive standards is not required.

## What participants will learn

- Distinguish sensing uncertainty, functional faults, and malicious manipulation in autonomous vehicle feedback systems.
- Understand safe sets, invariance, control barrier functions, and risk-aware safety-critical control.
- Recognize automotive cyber-physical threat models and limitations of residual-based intrusion detection.
- Connect technical research methods to automotive functional safety, SOTIF, AI safety, and cybersecurity engineering standards.
- Evaluate experimental evidence, modeling assumptions, and open challenges at the safety–security boundary.

## Research-based case studies

### 1. Safety under sensing uncertainty

**Risk-aware safe control with multi-modal sensing for dynamic obstacle avoidance**  
P. Y. Chang, Q. Xu, V. Renganathan, and Q. Ahmed, *Control Engineering Practice* (2026).  
Camera, LiDAR, and V2X sensing are integrated using Wasserstein-barycenter fusion, followed by an MPC nominal controller and CVaR–control barrier function safety filtering. The case study includes autonomous-vehicle experiments and simulation evaluation.  
[Read the paper](https://doi.org/10.1016/j.conengprac.2026.107114)

### 2. Security under adversarial manipulation

**Model-Free Generative Stealthy Attacks on Safety-Critical Vehicle Cyber-Physical Systems**  
Q. Mairaj ud din, S. G. Bhatti, and Q. Ahmed (2026).  
This case study examines generative measurement manipulation, tradeoffs between attacker impact and stealth, intrusion-detection limitations, and vehicle cyber-physical system evaluation, including hardware-in-the-loop results.  
[Read the research paper](https://arxiv.org/abs/2610.31864)

**Supplementary example:** N. U. Javed, Y. Singh, and Q. Ahmed, “Vehicle Localization in GPS-Denied Scenarios Using Arc-Length-Based Map Matching,” *IEEE Transactions on Intelligent Transportation Systems* (2026). This addresses localization under degraded GPS availability—not a demonstrated defense against GPS spoofing. [Read the paper](https://doi.org/10.1109/TITS.2025.3648744).

## Tentative program

| Elapsed time | Topic |
| --- | --- |
| 00:00–00:15 | Introduction: autonomous vehicle architecture; safety and security challenges |
| 00:15–00:45 | Safety foundations: dynamics, safe sets, invariance, control barrier functions, and risk |
| 00:45–01:20 | Case study 1: multimodal sensing and risk-aware obstacle avoidance |
| 01:20–01:30 | Break |
| 01:30–01:55 | Cyber-physical security foundations: threats, residuals, intrusion detection |
| 01:55–02:30 | Case study 2: model-free stealthy attacks in vehicle CPS |
| 02:30–02:55 | Automotive safety and cybersecurity standards |
| 02:55–03:15 | Interactive comparison: uncertain sensing versus intentional attacks |
| 03:15–03:30 | Open challenges, early-career Q&A, and closing discussion |

*Final date, session times, venue, and registration instructions will be determined by IEEE IV 2027 if accepted.*

## Standards discussed

- **ISO 26262:** Road-vehicle functional safety.
- **ISO 21448 (SOTIF):** Safety of the Intended Functionality.
- **ISO/PAS 8800:** Safety and artificial intelligence for road vehicles.
- **ISO/SAE 21434:** Road-vehicle cybersecurity engineering.

The tutorial presents these standards as engineering context and does not claim certification or standards compliance for the research examples.

## Organizers and instructors

**Prof. Qadeer Ahmed** · Department of Mechanical and Aerospace Engineering, The Ohio State University  
Primary contact · [ahmed.358@osu.edu](mailto:ahmed.358@osu.edu) · [Faculty profile](https://people.engineering.osu.edu/people/ahmed.358)

**Dr. Sidra Bhatti** · The Ohio State University / Center for Automotive Research  
Co-organizer and instructor · [bhatti.39@osu.edu](mailto:bhatti.39@osu.edu) · [Professional website](https://u.osu.edu/sidrabhatti/)

### Previous tutorial experience

- **MECC 2026:** *Learning for Complex Dynamics and Controls* — presented by Prof. Ahmed and Dr. Bhatti. [Official tutorial listing](https://mecc2026.a2c2.org/tutorial-sessions/).
- **ITEC 2026:** *Physics-Guided Learning for Powertrain Controls* — co-presented by Dr. Bhatti, Hend Abououf, and Prof. Ahmed.

## Resources and updates

The organizers plan to add selected teaching slides, explanatory diagrams, and links to publicly available research resources after the tutorial. The event is planned to be in person; live remote participation is not planned.

For inquiries: **[ahmed.358@osu.edu](mailto:ahmed.358@osu.edu)**.

---

**Website:** The public tutorial webpage is served from [`index.html`](index.html) through GitHub Pages. This README provides the public-facing summary for the GitHub repository. 
