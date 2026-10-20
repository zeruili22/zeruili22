<h1 align="center">Zerui Li</h1>

<p align="center">
  <strong>Embodied AI · Multimodal Agents · Robot Navigation</strong><br>
  From language instructions to reliable navigation in the physical world.
</p>

<p align="center">
  <a href="https://scholar.google.com/citations?user=hr5FDjMAAAAJ&amp;hl=en"><img src="https://img.shields.io/badge/Google_Scholar-4285F4?style=flat-square&amp;logo=googlescholar&amp;logoColor=white" alt="Google Scholar"></a>
  <a href="mailto:zerui.li@adelaide.edu.au"><img src="https://img.shields.io/badge/Email-334155?style=flat-square&amp;logo=gmail&amp;logoColor=white" alt="Email Zerui Li"></a>
</p>

<p align="center">
  <a href="#research">Research</a> ·
  <a href="#publications">Publications</a> ·
  <a href="#robots--tools">Robots &amp; Tools</a> ·
  <a href="#background--service">Background &amp; Service</a>
</p>

---

I'm a **PhD candidate** at the [Australian Institute for Machine Learning (AIML)](https://adelaide.edu.au/research/australian-institute-for-machine-learning/), **Adelaide University**, advised by **Prof. Qi Wu**.

My research focuses on **Vision-and-Language Navigation (VLN)**: enabling robots to follow natural-language instructions in unfamiliar environments. I develop multimodal agents that reason about space, recognise navigation failures, and recover through planning and interaction, with a particular focus on **transfer from simulation to real robots**.

## Research

- **Embodied intelligence:** connecting perception, reasoning, and action to build agents that understand and interact with the physical world.
- **Large-model training:** training and fine-tuning large language and vision-language models for embodied reasoning and decision-making.
- **Spatial reasoning:** explicit, queryable world representations that connect multimodal language models with metric geometry.
- **Zero-shot navigation:** language-guided planning, history-aware reasoning, and backtracking without task-specific navigator training.
- **Interactive recovery:** trajectory monitoring and grounded dialogue to help agents recognise and correct mistakes.
- **Real-world generalisation:** physics-based evaluation and deployment across quadrupeds, wheeled robots, and aerial platforms.

**Current focus:** training large multimodal models for VLN and developing a VLN benchmark in complex, dynamic, high-fidelity simulation environments.
## Publications

<sub>&#42; Equal contribution. My name is shown in bold.</sub>

### 2026

**[Talk2Escape: Conversational Grounding for Vision-and-Language Navigation](https://arxiv.org/abs/2609.28296)**  
<sub><strong>Zerui Li</strong>, Sihao Lin, Yanyan Shao, Jiwen Zhang, Xiangyu Shi, Shijie Li, Qi Wu</sub>  
**IROS 2026** · [Paper](https://arxiv.org/abs/2609.28296) · [Project](https://zeruili22.github.io/talk2escape/)

Trajectory monitoring and grounded dialogue help navigation agents detect failures and request corrective feedback, with deployment on a Unitree Go2.

**[One Agent to Guide Them All: Empowering MLLMs for Vision-and-Language Navigation via Explicit World Representation](https://arxiv.org/abs/2602.15400)**  
<sub><strong>Zerui Li</strong>&#42;, Hongpei Zheng&#42;, Fangguo Zhao, Aidan Chan, Jian Zhou, Sihao Lin, Shijie Li, Qi Wu</sub>  
**CoRL 2026** · [Paper](https://arxiv.org/abs/2602.15400) · [Project](https://zeruili22.github.io/GTA/)

**GTA** separates spatial state estimation from semantic planning through an interactive metric world representation, supporting zero-shot transfer to wheeled and aerial robots.

### 2025

**[SmartWay: Enhanced Waypoint Prediction and Backtracking for Zero-Shot Vision-and-Language Navigation](https://arxiv.org/abs/2503.10069)**  
<sub>Xiangyu Shi&#42;, <strong>Zerui Li</strong>&#42;, Wenqi Lyu, Jiatong Xia, Feras Dayoub, Yanyuan Qiao, Qi Wu</sub>  
**IROS 2025** · [Paper](https://arxiv.org/abs/2503.10069)

Improved waypoint prediction, history-aware reasoning, and backtracking for robust zero-shot navigation in continuous environments.

**[Ground-level Viewpoint Vision-and-Language Navigation in Continuous Environments](https://arxiv.org/abs/2502.19024)**  
<sub><strong>Zerui Li</strong>, Gengze Zhou, Haodong Hong, Yanyan Shao, Wenqi Lyu, Yanyuan Qiao, Qi Wu</sub>  
**ICRA 2025** · [Paper](https://arxiv.org/abs/2502.19024)

Bridging the viewpoint gap between human-centric instructions and low-height quadruped observations, with deployment on a Xiaomi CyberDog.

**[Open-Nav: Exploring Zero-Shot Vision-and-Language Navigation in Continuous Environment with Open-Source LLMs](https://arxiv.org/abs/2409.18794)**  
<sub>Yanyuan Qiao, Wenqi Lyu, Hui Wang, Zixu Wang, <strong>Zerui Li</strong>, Yuan Zhang, Mingkui Tan, Qi Wu</sub>  
**ICRA 2025** · [Paper](https://arxiv.org/abs/2409.18794) · [Code](https://github.com/YanyuanQiao/Open-Nav)

Open-source language models for zero-shot navigation, combining spatial-temporal reasoning with object and spatial context.

### Preprints & Under Review

**[VLNVerse: A Benchmark for Vision-Language Navigation with Versatile, Embodied, Realistic Simulation and Evaluation](https://arxiv.org/abs/2512.19021)**  
<sub>Sihao Lin&#42;, <strong>Zerui Li</strong>&#42;, Xunyi Zhao&#42;, Gengze Zhou, Liuyi Wang, Rong Wei, Rui Tang, Juncheng Li, Hanqing Wang, Jiangmiao Pang, Anton van den Hengel, Jiajun Liu, Qi Wu</sub>  
**2025 · Under review at IEEE TPAMI** · [Paper](https://arxiv.org/abs/2512.19021)

A physics-based benchmark unifying navigation tasks, embodied simulation, and evaluation to study the gap between simulated and real-world navigation.

**[Fast-SmartWay: Panoramic-Free End-to-End Zero-Shot Vision-and-Language Navigation](https://arxiv.org/abs/2511.00933)**  
<sub>Xiangyu Shi, <strong>Zerui Li</strong>, Yanyuan Qiao, Qi Wu</sub>  
**2025 · Preprint** · [Paper](https://arxiv.org/abs/2511.00933)

End-to-end navigation from three frontal RGB-D images, removing panoramic observations and waypoint prediction from the navigation pipeline.

## Robots & Tools

I work across the deployment pipeline, from hardware integration and ROS development to navigation under sensor noise, odometry drift, and unfamiliar floor plans.

| Platform | Hardware |
| :-- | :-- |
| Quadruped | Unitree Go2 · Xiaomi CyberDog |
| Humanoid | Booster K1 |
| Wheeled | TurtleBot 4 |
| Aerial | Custom-built quadrotor |

**Languages & learning:** `Python` `C/C++` `PyTorch` `TensorFlow`  
**Robotics & simulation:** `ROS` `ROS 2` `NVIDIA Isaac Sim` `Omniverse` `Isaac Gym` `Gymnasium`  
**Systems & training:** `Linux / Unix` `Git` `Multi-GPU / distributed training`

## Background & Service

- **PhD research at AIML** — began in 2024.
- **B.Eng. (Honours), Electrical & Electronic Engineering** — The University of Adelaide, 2023.
- **3rd place**, CCF Robot Embodied Intelligence Challenge, 2023.
- **Teaching:** casual academic, co-lecturing and serving as lead teaching assistant for AI courses.
- **Outreach:** AIML Ambassador.

<details>
<summary>Earlier university service</summary>

- Academic Board, The University of Adelaide (2017–2019).
- Social Justice Officer, Adelaide University Union / SRC (2017–2018).

</details>

---

<p align="center">
  Interested in VLN, spatial reasoning, or sim-to-real robotics?<br>
  <a href="mailto:zerui.li@adelaide.edu.au">Let's connect.</a>
</p>
