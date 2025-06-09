# Tsinghua University: Embodied AI

This repository contains all the learning materials and project implementation for the Embodied AI course at Tsinghua University, instructed by Professor [Huaping Liu](https://www.cs.tsinghua.edu.cn/info/1121/5096.htm).

## Course Overview

Embodied Intelligence stands at the frontier of AI, merging software and hardware to create intelligent agents that can perceive, reason, and interact with the physical world. The widespread adoption of deep learning and robotics has paved the way for creating sophisticated systems that can understand and execute complex tasks in real-world environments. However, building these systems requires a deep understanding of the "full stack" of embodied AI—from high-level AI algorithms to low-level hardware control and communication protocols.

The goal of this course is to provide students with a comprehensive, hands-on understanding of building an embodied AI system from the ground up. We explore the entire pipeline, from the mechanical design and construction of a robotic platform to the integration of advanced AI models for perception and decision-making. Throughout the course, students will design and build a complete robotic system, including a custom-designed six-axis robot arm, and develop the software to control it. Students will then implement a state-of-the-art AI pipeline, integrating large language models for natural language understanding, vision models for object detection, and advanced algorithms for grasp prediction and motion planning.

## Course Materials

- Course Website: N/A
- Lecture Record: N/A
- Lecture Slides: Under [slides](./slides/) folder.
- Assignments Implementation: Under [assignments](./assignments/) folder.

## Final Project

The final project for this course was to design, build, and program a complete six-axis collaborative robot arm platform for Embodied Intelligence research. The project's goal was to create a low-cost, effective system capable of understanding natural language commands and performing intelligent object manipulation tasks.

Our final project successfully integrated multiple cutting-edge AI models to achieve this. The system uses a Large Language Model (Kimi) to parse user commands, a Vision-Language Model (OWL-ViT) for zero-shot object detection, a grasp prediction network (GraspNet) to determine the best way to pick up an object, and MoveIt within the ROS framework for robust motion planning. The entire system was validated in the MuJoCo simulation environment, achieving a high success rate on pick-and-place tasks.

- The final report, detailing the AI pipeline and results, can be found here: [AI Algorithm Experimental Report](./assignments/report/report.md)
- The open-source repository for the robot arm hardware and software is available at: <https://github.com/ShanningZhuang/lib_robot_arm>
