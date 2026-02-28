---
title: Project Requirements
---

## Requirements Development

The system requirements for the exploration rover were developed from identified user needs, subsystem ownership, and concept evaluation. Each requirement is written to be measurable and verifiable within the semester timeline. The Minimum Acceptable Performance represents the threshold required for successful demonstration. The Target Performance represents the desired operational goal under nominal conditions. Stretch requirements provide additional capability beyond core functionality but are not required for baseline system success.

---

## System Requirements Table

| Requirement | Minimum Acceptable Performance | Target Performance | Stretch (Y/N) | Responsible Member(s) | Verification Method |
|-------------|--------------------------------|--------------------|---------------|------------------------|---------------------|
| Front Camera | Provides live video feed to laptop display | 720p resolution with less than 200 ms latency | N | Hattie | Live video validation during demo |
| Reverse Camera | Displays rear camera feed when manually activated | Automatically displays rear feed when reverse command is issued | Y | Hattie | Functional reverse movement test |
| Wireless Communication | Stable wireless control at 5 meters | Stable wireless control at 15 meters | N | Rylee | Measured range test with continuous input |
| Controller Input | Rover responds to input within 500 ms | Rover responds to input within 150 ms | N | Rylee | Command latency measurement |
| Drivetrain Mobility | Moves forward, reverse, and turns on flat surface | Traverses uneven terrain without stalling | N | Tim, Bryce | Obstacle course mobility test |
| Tank Treads | Operate without slippage during normal movement | Maintain tension after 10 minutes of continuous operation | N | Tim, Bryce | Mechanical inspection after timed run |
| Battery System | Operates continuously for 10 minutes | Operates continuously for 20 minutes | N | Rylee | Timed continuous runtime test |
| Temperature Sensor | Detects ambient temperature within ±3°C | Detects ambient temperature within ±1.5°C | N | Riley | Controlled heat source comparison |
| Humidity Sensor | Detects humidity within ±10% RH | Detects humidity within ±5% RH | N | Riley | Environmental comparison test |
| Hall Effect Sensor | Detects motor rotation events | Measures wheel rotation within 5% error margin | N | Tim, Bryce | RPM validation test |
| Distance Sensor | Detects obstacle within 20 cm | Detects obstacle within 5 cm and triggers alert | Y | Hattie | Obstacle detection validation |
| LED Indicators | At least one operational status LED | Separate power and error status LEDs | N | All | Visual functional inspection |
| Emergency Stop | Stops drivetrain when activated | Stops drivetrain within 200 ms | Y | Rylee | Stop response timing test |
| Rover Body | Securely mounts all components | Protects internal components during minor collision | N | Tim, Bryce | Physical inspection and controlled bump test |
| Charging Capability | Allows manual battery charging | Provides guided docking alignment | Y | Hattie | Charging validation test |
| Audio Alert | Produces audible alert signal | Distinct alert for error conditions | Y | Rylee | Audio output verification |
| Non Sharp Edges | No exposed sharp edges | All exposed edges rounded and deburred | N | Tim, Bryce | Physical inspection |

---

## Requirements Traceability Matrix

| Requirement | Subsystem | Block Diagram Component | Verification Method |
|-------------|------------|--------------------------|--------------------|
| Wireless Communication | Controller Module | ESP32 Communication Node | Range and stability test |
| Controller Input | Controller Module | Game Controller Interface | Latency measurement |
| Drivetrain Mobility | Drive System | Motor Driver + Treads | Obstacle course test |
| Hall Effect Feedback | Drive System | Hall Sensor Interface | RPM validation |
| Front and Rear Cameras | Camera Module | Camera Nodes + Laptop Display | Live feed validation |
| Temperature & Humidity | Sensor Module | Environmental Sensor Board | Controlled comparison |
| Battery System | Power System | Battery + Voltage Regulation | Timed runtime test |
| Emergency Stop | Controller + Drive | Kill Switch Circuit | Stop latency test |
| LED Indicators | All Modules | Status Indicator Circuit | Visual inspection |
| Distance Sensor | Camera Module | Proximity Sensor Interface | Obstacle detection test |

---

## Demonstration Acceptance Criteria

The rover will be considered functional for external review if it meets the following criteria:

- Establishes stable wireless communication with the controller and laptop.
- Provides a continuous live front camera feed.
- Responds to controller input with observable drivetrain motion.
- Successfully traverses a defined obstacle path.
- Displays temperature and humidity readings on the laptop interface.
- Detects nearby obstacles and activates a visual or audio alert.
- Operates on battery power for a minimum of 10 continuous minutes.
- Immediately halts drivetrain motion when the emergency stop is activated.

Power verification will be conducted through timed continuous operation testing. Communication reliability will be validated through range testing with uninterrupted command transmission. Control responsiveness will be verified by measuring delay between controller input and drivetrain activation. Sensor functionality will be validated through controlled environmental comparisons.
