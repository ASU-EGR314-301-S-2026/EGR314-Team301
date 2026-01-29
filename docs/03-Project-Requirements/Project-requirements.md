---
title: Project Requirements
---

## Table

| Requirement Description | Measure of Threshold | Target Measure | Stretch Requirement (Y/N) | Team Member(s) | Context |
|-------------------------|--------------------|------------------|----------------|-----------------|------------------------|
| Front Seeing Camera | What can it see | Have a good range | N | Hattie | In order for the rover to be able to give visual feedback to the operator, so that the operator can reliably control it, it needs a camera to see where it is going. |
| Surface mounted microcontroller | 1 PIC or ESP | 8-bit ESP | N | Everyone | In order to fulfill the class requirements and for the rover to be able to function, both for outputs like movement and for sensor inputs. |
| ESP32 | Wifi | Connect the robot to controller | N | Everyone | In order to fulfill the class requirements we need to be able to connect to each other's modules wirelessly. |
| LED | Does it light up | They turn on when needed | Y | Everyone | In order for the user to be able to know when the electronics are truly working we will be adding LED's to just about every part of the robot whether it's a status LED or error LED. |
| Wireless Communication | Have connection | Have long distance connection | N | Rylee | In order for this rover to be a true exploration device, it needs to have the ability to be controlled wirelessly. |
| Motors | Moves entire body | Does not overheat quick due to load | N | Tim, Bryce | In order to allow the rover to move around, and allow it to function as a rover, it needs motors to produce the rotational motion for its treads. |
| Body to hold all components | Keeps components in place | Sturdy enough to protect components | N | Tim, Bryce | In order for the rover to have a solid foundation and a place to keep and protect all of the electronics and other things that it may require within it, it will have a solid but lightweight body to minimize the amount of electricity used while also keeping our electronics secure. |
| Battery | How long it lasts | Lasts more than 10 min | N | Rylee | In order for the rover to really explore the environment that would be required without having to drag a cord behind it a battery will be fitted to the device, we want the battery to last a while in order to get to where it needs to go, see what it needs to see, and come back before running out of charge. |
| Temperature sensor | Detects overheating | When it reaches a certain reading to determine overheating | N | Riley | In order to properly read the environment around the rover, it needs to be capable of measuring the ambient temperature around the rover. |
| Hall effect sensor | Measure increments on motor | Detects magnetic fields and converts them into electrical signals | N | Tim, Bryce | In order to know how far the tank treads have moved we have added hall effect sensors that will be able to tell the user how fast or slow the rover is moving. |
| Humidity sensor | Reads humidity | Accuracy of humidity | N | Riley | In order to properly read the environment around the rover, it needs to be capable of measuring the humidity. |
| Controller | Can control the robot | Has a very good input to output speed | N | Rylee | In order for the land rover to be able to do what the human wants with no coding experience, it will be controlled with a controller. |
| Tank tread | What terrain can it handle | Driveable on all terrain | N | Tim, Bryce | In order to allow the rover to move comfortably in uncontrolled environments, using treads gives the rover more grip and ground contact to keep it upright and mobile more reliably than wheels. |
| Gears for tank tread | Secures treads | No slippage to keep treads tight | N | Tim, Bryce | In order for the rover to be able to have a reliable amount of movement the tank treads will be tightened down enough so they don’t slip and get stuck in the environments they are exploring. |
| Speaker | Makes an inkling of a sound | User can clearly hear it | Y | Rylee | For user feedback the controller will be fitted with a speaker that will give audio alerts if an error or other certain phenomena occur. |
| Distance sensor | Measure distance | Sense an object is too close and plays a sound | Y | Hattie | In order for the rover to not run into things and potentially break we are adding a distance sensor. |
| Servo | Move in 360 | Moves camera to any angle needed | Y | Hattie | For maximum visibility we will be putting our camera on a servo so we can look at the environment around us more effectively. |
| Reverse Camera | Shows back view | Shows only when reversing | Y | Hattie | To help the user navigate more effectively we are adding a camera at the back so reversing is possible. |
| Motion Sensor | Can sense motion | Alerts user of motion and what direction it was in | Y |  | In order for the rover to be able to check for motion in an area, to determine if something around it is in motion without the user having to manually see it, it will have the rover alert the user of the movement. |
| Charging Station | Can get to the charging station | Can start charging it without user input | Y | Hattie | To help our users we also provide a charging station that the robot can mount and start charging itself on. |
| Non-Sharp Corners | Isn't sharp | Won't cut anyone who touches it | N | Tim, Bryce | To ensure safety for the people using our device we will file and deburr all the edges so nothing and no one gets cut or hurt while using our rover. |



## What is each team member doing?
| Module                           | Member        |
|----------------------------------|---------------|
| Controller                       | Rylee         |
| Drivetrain / Body / Hall Effect  | Tim, Bryce    |
| Camera System                    | Hattie        |
| Temperature / Humidity Module    | Riley         |


## Context
