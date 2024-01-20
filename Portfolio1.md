# Nirav Madhani's Portfolio in Robotics and Machine Learning

Welcome to my portfolio where I highlight my expertise in Robotics and Machine Learning, showcasing projects that demonstrate my skills in celestial navigation, autonomous movement, and inter-agent communication.

## Projects

### Linkedin Non-Professional Post Remove (in-progress)

**DEMO**

**Key Features**
- Developed a LinkedIn post scraping addon, communicating with local server to increase database storage capacity by more than 50x.
- Architected LLM based application for data labeling, improving labeling efficiency over 100x with 96% performance of human labelers. 
- Training SLM using transfer learning to classify text as Professional / Non-Professional and deployed as ONNX increasing performance over 50x and reducing cost to 0.
- Wireframed an addon to delete LinkedIn post based on SLM classification.


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

### Multi-Task Learning using HydraNet

[Source](https://gist.github.com/Nirav-Madhani/641f083f05b39dd83d4dd3664275ba3f)

**Key Feature**
- Used Pretrained Resnet Network, connected to end layers with use of dense layer for reshaping
- Performed Image Segmentation and Depth Predition

#### Sample Output

![image](https://github.com/Nirav-Madhani/Nirav-Madhani/assets/77914957/dcef92e1-b258-4efa-be7f-268a1eca7419)
![image](https://github.com/Nirav-Madhani/Nirav-Madhani/assets/77914957/9dd82ec4-9a2f-4dd6-ba16-c0e5b5678b6c)
![image](https://github.com/Nirav-Madhani/Nirav-Madhani/assets/77914957/ec6955b6-0778-4801-82d3-b649289c1424)



## Contact Me
For collaborations or questions, reach out to me through the following channels:

- **LinkedIn:** [nrmadhani](https://www.linkedin.com/in/nrmadhani/)
- **GitHub:** [Nirav Madhani](https://github.com/Nirav-Madhani)

Thank you for visiting my portfolio!
