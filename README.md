# Shopping-Assistant-Robot-Prototype
Design and implementation of a dual-state autonomous mobile shopping assistant robot prototype.

## Overview
This project develops a low-cost, dual-state autonomous shopping assistant robot that can follow a shopper hands-free and guide them to specific items in a supermarket environment. The prototype targets crowded retail environments in Nigeria and is designed to be practical on student-level hardware.

## Core Capabilities
- Follow Mode: vision-based tracking and person re-identification to follow a specific shopper.
- Guide Mode: ROS 2 navigation with SLAM to lead the shopper to a selected location.
- Return Home: autonomous docking after checkout without staff intervention.

## Objectives
- Build a differential-drive robot with 2D LiDAR for indoor mapping.
- Implement ROS 2 navigation and obstacle avoidance.
- Integrate lightweight AI vision on a Raspberry Pi.
- Validate performance in a controlled indoor environment.

## Scope and Limitations
- Prototype scale with lightweight payload.
- Controlled indoor testing environment with adequate lighting.
- Focus on proof-of-concept software architecture and state switching.

## Technology Stack
- ROS 2 (Nav2, SLAM Toolbox, AMCL)
- Raspberry Pi 4
- 2D LiDAR (RPLidar A1)
- MobileNet-SSD with re-identification

## Repository Files
- proposal.md: grant-focused project proposal.
- README.md: project overview and context.

## Estimated Budget (NGN)
- Total prototype cost: 419,000 NGN
- Main cost drivers: Raspberry Pi 4, 2D LiDAR, motors, battery, chassis

## Timeline
Planned 12-week build cycle from procurement through testing and final demonstration.

## Team
- Project Lead: Keshinro Mus'ab Moyosore
- Supervisor: Dr. A. A. Ibrahim
- Institution: Ahmadu Bello University Zaria
