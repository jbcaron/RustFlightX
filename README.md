# Rust Autonomous Drone Project

This repository contains the source code and documentation for a Rust-based autonomous drone project that uses either the RP2040 or ESP32 microcontroller. The project is designed to be executed in multiple stages, and it covers various aspects of drone development, including sensor telemetry, sensor data filtering, real-time telemetry via radio communication, PCB prototyping for axis control and sensor data acquisition, axis regulation for stabilization and approach to the runway, and full autonomy using GPS waypoints.

[//]: # (Note: This README serves as a high-level overview of the project. More detailed instructions and code documentation can be found in the respective project folders within this repository.)

## Table of Contents

- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Project Stages](#project-stages)
- [Sensors](#sensors)
- [Hardware](#hardware)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Welcome to the Rust Autonomous Drone Project repository. This open-source project aims to develop an autonomous drone system for a 2-meter wingspan motor glider using Rust as the programming language. The drone is designed to be controlled by either the RP2040 or ESP32 microcontroller, providing an affordable and flexible solution for hobbyists and drone enthusiasts.

## Project Overview

The project is a comprehensive exploration of drone development, covering various aspects of autonomous flight. The main objectives of this project include:

- [ ] Sensor Telemetry: Integration of a variety of sensors, such as a 3-axis IMU (accelerometer, gyroscope, and compass), barometer, GPS, and a Time-of-Flight (TOF) Lidar laser for ground distance measurements.

- [ ] Sensor Data Filtering: Implementing filtering algorithms to enhance the accuracy and reliability of sensor data.

- [ ] Real-Time Telemetry: Establishing real-time communication between the drone and a remote ground station for monitoring and control.

- [ ] PCB Prototyping: Design and fabrication of custom Printed Circuit Boards (PCBs) for precise control of the drone's axes and sensor data acquisition.

- [ ] Axis Regulation: Developing control algorithms for axis stabilization and precision approach to the runway.

- [ ] Full Autonomy: Enabling the drone to navigate autonomously by following GPS waypoints, providing a high level of flexibility and utility.

## Project Stages

The project is structured into multiple stages to ensure a methodical development process:

1. Sensor Telemetry
In this stage, we will focus on integrating the various sensors into the drone. The sensors include:

A 3-axis Inertial Measurement Unit (IMU) for attitude and orientation sensing, which includes an accelerometer, gyroscope, and compass.
A barometer for measuring atmospheric pressure to estimate altitude.
A GPS module for global positioning information.
A Time-of-Flight (TOF) Lidar laser for precise ground distance measurement.

2. Sensor Data Filtering
To ensure reliable sensor data, we will implement filtering algorithms in this stage. Filtering will help reduce noise and errors in the sensor measurements, ultimately improving the drone's performance.

3. Real-Time Telemetry
This stage involves establishing real-time communication between the drone and a ground station using radio transmission. This communication allows for remote monitoring and control of the drone during flight.

4. PCB Prototyping
Custom PCBs will be designed and fabricated for controlling the drone's axes and acquiring sensor data. The PCBs provide a robust and tailored solution for our drone's specific needs.

5. Axis Regulation
In this stage, we will develop control algorithms to regulate the drone's axes, ensuring stability during flight and precise approaches to the runway.

6. Full Autonomy
The final stage of the project aims to achieve full autonomy for the drone. Using GPS waypoints, the drone will navigate autonomously, following a predefined path.

## Sensors

Our drone is equipped with various sensors that play a crucial role in its functionality:

- **3-axis IMU**: This sensor provides data from an accelerometer, gyroscope, and compass, enabling the drone to determine its attitude, orientation, and heading.

- **Barometer**: The barometer measures atmospheric pressure, allowing the drone to estimate its altitude and make necessary adjustments during flight.

- **GPS**: The GPS module provides precise global positioning data, essential for navigation and waypoint following.

- **Lidar (TOF)**: A Time-of-Flight Lidar laser is used to measure ground distances with high accuracy, assisting the drone in terrain following, obstacle avoidance and landing.

## Hardware

The choice of hardware, specifically the selection of either the RP2040 or ESP32 microcontroller, is essential to the success of this project. Additionally, custom PCBs will be designed to facilitate the control of the drone's axes and sensor data acquisition. For detailed hardware specifications and connections, please refer to the hardware documentation within this repository.

## Contributing

We welcome contributions from the community! If you have improvements, ideas, or suggestions, please feel free to open an issue or submit a pull request. Check our contribution guidelines for more information on how to get involved.

## License

This project is open-source and is licensed under the [MIT License](https://raw.githubusercontent.com/jbcaron/RustFlightX/main/LICENSE). You are encouraged to use and modify the code for your own projects, but please provide proper attribution to the original authors.

Happy flying! 🚁✈️🛰️
