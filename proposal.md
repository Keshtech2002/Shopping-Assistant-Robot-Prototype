# Dual-State Autonomous Shopping Assistant Robot

## Project Summary
This grant proposal seeks support to build a low-cost, dual-state autonomous shopping assistant robot that can (1) follow a shopper hands-free and (2) guide them to specific items using indoor mapping. The prototype targets crowded supermarket environments in Nigeria, where customer experience and operational efficiency are constrained by manual cart handling, navigation difficulties, and limited service automation. The system uses ROS 2, 2D LiDAR SLAM, and lightweight computer vision on a Raspberry Pi to deliver a practical, scalable solution at student-prototype cost levels.

## Problem Statement and Need
- Shoppers, especially the elderly or physically impaired, struggle with heavy carts and confusing store layouts.
- Retailers lose sales when customers abandon purchases due to poor navigation and fatigue.
- Local supermarkets need affordable, contactless automation that does not require premium hardware.

## Project Objectives
- Design an autonomous shopping system for both follow and guide states.
- Build a wheeled robot prototype equipped with 2D LiDAR.
- Implement ROS 2 navigation to map the environment and guide users to items.
- Integrate a lightweight AI vision system for consistent human tracking in crowds.
- Evaluate system performance in a controlled indoor environment.

## Proposed Solution
A dual-state mobile robot with two core modes:
- Follow Mode: tracks a specific shopper with vision-based detection and re-identification while carrying small loads.
- Guide Mode: leads the shopper to selected store locations using SLAM and ROS 2 Nav2.

After checkout, the robot autonomously returns to its docking station without staff intervention.

## Innovation and Relevance
- Dual-state operation combines follow and guide capabilities in a single system, which is rare in existing retail robots.
- Designed for budget-constrained environments using accessible hardware (Raspberry Pi, 2D LiDAR, USB camera).
- Built on open-source ROS 2 to enable rapid iteration, local maintenance, and knowledge transfer.

## Technical Approach
- Vision: MobileNet-SSD with person re-identification for persistent target tracking in crowds.
- Navigation: ROS 2 Nav2 stack with SLAM Toolbox and AMCL for indoor mapping and localization.
- Safety: Dynamic obstacle avoidance with DWA.
- Kinematics: Differential-drive chassis for tight aisle maneuvering.

## System Workflow
1. Idle at docking station.
2. Pairing: lock onto shopper.
3. Follow Mode: hands-free load carrying and obstacle avoidance.
4. Guide Mode: user selects destination; robot leads.
5. Return Home: autonomous docking post-checkout.

## Implementation Plan (12 Weeks)
- Literature review and proposal defense
- Component procurement and contingency planning
- Chassis assembly and wiring
- ROS 2 setup and LiDAR SLAM configuration
- Vision tracking integration
- State machine and return-to-home logic
- System testing and tuning
- Final documentation and demonstration

## Expected Outcomes and Impact
- Functional dual-state robot prototype.
- Reliable tracking of a specific shopper in crowded conditions.
- Demonstrated indoor navigation with real-time obstacle avoidance.
- Fully autonomous return-to-home behavior.
- A replicable, low-cost platform for local research, teaching, and future commercial pilots.

## Beneficiaries
- Shoppers who need hands-free assistance, including elderly and physically impaired users.
- Local retailers seeking low-cost automation to improve customer experience.
- University researchers and students working in robotics and embedded AI.

## Monitoring and Evaluation
- Target lock stability: maintain user tracking accuracy above 90 percent in controlled crowd scenarios.
- Navigation performance: successful guide-to-destination and return-to-home completion rates.
- Safety and usability: obstacle avoidance success and operator feedback from controlled trials.

## Budget (Estimated, NGN)
Total prototype cost: 419,000 NGN

Primary cost drivers:
- Raspberry Pi 4 Model B (4GB)
- 2D LiDAR (RPLidar A1)
- Motors, drivers, battery, chassis, and sensors

Cost-reduction alternatives include depth cameras (Xbox Kinect, Orbbec Astra), lower-cost motors, and a simplified chassis.

## Risk Management
- Occlusion in crowded aisles: re-identification model and predictive tracking.
- Lighting variability: LiDAR-based mapping reduces vision dependency.
- Hardware cost spikes: validated low-cost sensor and motor alternatives.

## Grant Request
This project requests grant support to fund hardware procurement, system integration, and controlled pilot testing. The grant will directly enable the development, evaluation, and documentation of a working prototype suitable for replication and future scale-up.

## Team and Supervision
- Project Lead: Keshinro Mus'ab Moyosore (Mechatronics Engineering)
- Supervisor: Dr. A. A. Ibrahim
- Institution: Ahmadu Bello University Zaria

## References
A detailed bibliography is available on request and includes key sources on ROS 2 navigation, SLAM, and vision-based tracking in retail environments.
