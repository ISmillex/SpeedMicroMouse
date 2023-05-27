# SpeedMicroMouse

Welcome to the SpeedMicroMouse repository! SpeedMicroMouse is a Micromouse project aimed at developing a fast and efficient autonomous robot capable of navigating a maze in the shortest time possible. This repository contains all the necessary code and documentation to build, program, and optimize your own Micromouse robot.

Archyn and Oruç Çakır

![SpeedMicroMouse Demo](speedmouse_demo.gif)

## Table of Contents

1. [Introduction](#introduction)
2. [Roadmap](#roadmap)
3. [Design](#design)
4. [Features](#features)
5. [Contributing](#contributing)
6. [Resources](#resources)
7. [License](#license)

## Introduction

Micromouse is a fascinating field within robotics that challenges engineers and enthusiasts to create autonomous robots capable of exploring and solving maze puzzles. SpeedMouse is an open-source Micromouse project that aims to provide a platform for learning, experimentation, and innovation in the field of robotic navigation.

This repository serves as the central hub for all SpeedMouse-related resources. Here, you will find the source code, design files, documentation, and examples needed to build your own SpeedMouse robot.

## Roadmap

We have an exciting roadmap planned for the SpeedMouse project. Here are some of the key milestones we aim to achieve:

- **Version 1.0**:
	- Minimalist chassis design
  - Motor control and sensor integration
  - Basic maze-solving algorithm implementation

- **Version 2.0**:
	- Modular chassis design for easy customization
	- Enhanced sensor suite for better environment perception
  - Improved maze-solving algorithm with advanced path planning

- **Version 3.0**:
	- Advanced chassis with optimized weight distribution and agility
  - Integration of machine learning techniques for adaptive navigation
  - Advanced sensor fusion for precise mapping and localization


We are committed to regular updates and improvements, and we encourage the community to contribute to the project's growth.

## Design

The SpeedMouse robot has been designed with performance, simplicity, and modularity in mind. The key components of the design include:

- **Chassis**: The chassis is designed to be lightweight yet sturdy, allowing the robot to move quickly and maneuver through the maze effectively. It consists of laser-cut acrylic parts that are easy to assemble and modify.

- **Electronics**: The electronics stack comprises a microcontroller board, motor drivers, and various sensors. We have chosen the [SpeedBoard](https://github.com/SpeedMouse/SpeedBoard) as the primary controller board for its powerful features and compatibility with the SpeedMouse software.

- **Sensors**: SpeedMouse utilizes a combination of distance sensors, such as infrared or ultrasonic sensors, to detect walls and obstacles. Additionally, it incorporates an onboard gyroscope and accelerometer for orientation and motion sensing.

For detailed design specifications, assembly instructions, and 3D-printable files, please refer to the [Design](/design) directory.

## Features

- **Maze Solving**: SpeedMicroMouse implements efficient maze-solving algorithms that aim to find the shortest path from the maze's starting point to its center.

- **Real-time Mapping**: The robot uses its sensors to build a real-time map of the maze, enabling it to make informed decisions about its path.

- **Speed Optimization**: SpeedMicroMouse is designed to achieve maximum speed while maintaining precise control to navigate the maze swiftly.

- **Modularity**: The SpeedMouse architecture is modular, allowing users to experiment with different sensors, algorithms, and hardware configurations.

For a comprehensive list of features, please refer to the [Features](/features) directory.

## Contributing

We welcome contributions from the community to make SpeedMouse even better. If you would like to contribute, please follow these steps:

1. Fork the repository and clone it locally.
2. Create a new branch for your feature or bug fix.
3. Implement your changes and ensure that the code follows the project's coding guidelines.
4. Write tests to validate your code if applicable.
5. Commit your changes and push them to your forked repository.
6. Submit a pull request detailing your changes and explaining their benefits.

For more information, please refer to our [Contributing](/CONTRIBUTING.md) guidelines.

## Resources

Here are some additional resources that you may find useful:

- [MyProjectQ](https://sites.google.com/site/myprojectq/home?authuser=0)
- [BuleBule Documentation](https://bulebule.readthedocs.io/en/latest/index.html#)
- [Micromouse by Alex Hadik](https://www.alexhadik.com/work/micromouse/)
- [Micromouse USA](http://micromouseusa.com)
- [Micromouse by K. Srichand](https://kswichit.net/micromouse/micromouse.html)
- [Greenye Micromouse](http://www.greenye.net)
- [KerisLab JP (Translated)](https://www-kerislab-jp.translate.goog/?_x_tr_sl=auto&_x_tr_tl=en&_x_tr_hl=tr)

Please note that these references are external sources and are not directly affiliated with the SpeedMouse project. Make sure to refer to their respective websites for more information.


## License

The SpeedMouse project is licensed under the [MIT License](/LICENSE). You are free to use, modify, and distribute this software for both personal and commercial purposes. We encourage the use of SpeedMouse in educational settings and welcome contributions from all members of the community.

For more details, please refer to the [License](/LICENSE) file.

---

Thank you for your interest in the SpeedMouse project. We hope you find it exciting and enjoy building your own Micromouse robot. Happy exploring!
