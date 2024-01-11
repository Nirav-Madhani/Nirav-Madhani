# Nirav Madhani's Portfolio in Robotics and Machine Learning

Welcome to my portfolio where I highlight my expertise in Robotics and Machine Learning, showcasing projects that demonstrate my skills in celestial navigation, autonomous movement, and inter-agent communication.

## Projects

### CeNSE-DL: Celestial Navigation in Outer Space Enhanced by Deep Learning
This repository contains the code, paper, and dataset generator tool used for the term project for *Case Studies in ML* at **UT Austin**.

**Key Features:**
- Custom dataset generator based on a modified implementation of [Starry Sky](https://github.com/Firnox/StarrySky) by [Firnox](https://github.com/Firnox).
- Parallel dataset generation with adjustable worker count for efficiency.
- Trained on Colab with a potential for adapting to different environments.

**Reproduction Steps:**
1. Generate the dataset using `buildDataset.py`.
    ```python
    python buildDataset.py {Total Number of Images} {Number of Workers}
    ```
2. Customize the training environment and notebook as per your setup.
3. Train the model by running the provided notebook step by step.

### Traffic Swarm: Inter-Communication within Agents Using Reinforcement Learning
In this project, cars navigate a traffic lane without colliding by intercommunicating using reinforcement learning.

![Traffic Swarm Demo](https://user-images.githubusercontent.com/77914957/158375965-51e6d75a-fb06-488b-93f3-51f2e991cc53.gif)

**Demo GIF:** Take1

_Note: Source Code and Final trained model will be made available soon._

## Robotics Project: Object Searching and Grasping Robot
This robot, equipped with a 5DOF arm, gripper, and Mecanum wheels, demonstrates object searching and grasping capabilities. Utilizing distributed computing concepts, the robot has 'two brains' that handle different tasks and communicate to achieve its goals.

**Key Features:**
- Bifurcated computing system where the Raspberry Pi handles low-level tasks while a PC or Colab resource manages state determination and intensive computations.
- Implementation of a state machine for decision-making.
- Monocular depth estimation using simple linear approximation.

**YouTube Demonstration:**
[![Robot Project Video](https://img.youtube.com/vi/rHJ69zlpGIQ/0.jpg)](https://www.youtube.com/watch?v=rHJ69zlpGIQ "Robot Project Video - Click to Watch!")

## Contact Me
For collaborations or questions, reach out to me through the following channels:

- **LinkedIn:** [Your LinkedIn Profile](https://www.linkedin.com/in/nrmadhani/)
- **GitHub:** [Nirav Madhani](https://github.com/Nirav-Madhani)

Thank you for visiting my portfolio!
