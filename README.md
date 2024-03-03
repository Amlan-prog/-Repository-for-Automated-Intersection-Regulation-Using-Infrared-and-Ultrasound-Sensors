# -Repository-for-Automated-Intersection-Regulation-Using-Infrared-and-Ultrasound-Sensors

Welcome to our Intelligent Traffic Control System code repository, a comprehensive resource for developing an innovative traffic management solution. At its core, the system leverages data from both infrared and ultrasound sensors strategically positioned at intersections. These sensors continuously gather real-time information about vehicular presence and movement.

The code within this repository orchestrates an intricate system that processes the sensor data, enabling the automated decision-making required for regulating traffic lights at an intersection. By carefully analyzing the input from the infrared and ultrasound sensors, the system dynamically adjusts the timing of traffic lights for multiple lanes.

The intelligent decision-making algorithm takes into account the flow of vehicles from different directions, optimizing the overall traffic flow. This adaptive approach not only enhances intersection efficiency but also contributes to improved road safety and reduced congestion.

Developers can integrate and customize this codebase into their projects, taking advantage of its modular structure and compatibility with various sensor configurations. This repository serves as a foundation for creating smart traffic control solutions that are responsive to real-time conditions, contributing to more sustainable and efficient urban transportation systems.

**Requirements:**
 hardware setup using a DEMOQE128 Rev. C board with the MC9S08QE128 microcontroller. Here's a brief overview of the components mentioned:

Microcontroller:

Model: MC9S08QE128
Details: A microcontroller is a small computer on a single integrated circuit. The MC9S08QE128 is specifically mentioned as the model used in this setup.
Integrated Development Environment (IDE):

IDE: CodeWarrior
Details: CodeWarrior is an integrated development environment used for editing, compiling, and running firmware code for microcontrollers. In this case, it's utilized for programming the MC9S08QE128.
Sensors:

Infrared Sensors:

Model: GP2Y0A21YK (2 sensors)
Details: GP2Y0A21YK is an infrared proximity sensor, likely used for detecting the presence or absence of objects within a certain range.
Ultrasound Sensors:

Model: SRF04 (2 sensors)
Details: The SRF04 is an ultrasonic range finder commonly used for measuring distances by emitting ultrasonic pulses and measuring the time it takes for the echoes to return.
Phototransistor/Infrared Emitting Diode Pairs:

Quantity: 2 pairs
Details: Phototransistor and Infrared Emitting Diode pairs are often used for object detection or to measure light intensity. They work by detecting the infrared light reflected off nearby surfaces.
Traffic Lights:

LEDs: 6 LEDs
Details: Two sets of traffic lights at the intersection, each consisting of three LEDs (commonly red, yellow, and green). LEDs are used to visually indicate the status of traffic lights.
7-Segment Displays:

Quantity: 2 displays
Details: 7-segment displays are commonly used to represent numerical information. Each display typically has seven LEDs arranged in a specific pattern, allowing the representation of decimal numerals.
