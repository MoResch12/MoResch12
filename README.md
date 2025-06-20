# Hi, I'm Moritz Resch

Welcome to my Github page!
I'm a Msc. in "Automation and Robotics" from TU Wien and based in Vienna, Austria. This GitHub page showcases some of my work across various domains, including autonomous systems, robotics and some ML. Most of the projects are originally in private repos, but I still hope to give you some insights on the projects I did in the past.

---

## 💼 Projects

### 📊 Master Thesis - Leveraging Large Language Models for Parametrization and Code Generation of Impedance Controllers in Robotic Manipulation
**Description:** Written at [GV LAB](https://www.gvlab.jp/contact-e.html) - Universtiy of Tokyo and [ACIN](https://www.acin.tuwien.ac.at/en/) - TU Wien under supervision of Prof. Christian Ott and Prof. Gentiane Venture. In summary, the thesis aims to build a framework to leverage the world knowledge of LLMs to parameterize compliant controllers for dual arm manipulation tasks and autonomously generate trajectories. For this, I developed a framework which specifies the prompt structure and the output variables (see Fig. below). The framework was then implemented and tested on two dual arm manipulators (Franka dual arm setup and Pepper robot). Both were able to perform single and dual arm manipulation tasks across different objects, while also being compliant towards outside pertubations.  
A potential paper based on the thesis is still under review.  
**Tech Stack:** Matlab, Simulink, Python

[🔗 View Project](https://github.com/MorResch/ComBi_Copilot)

![thesis_overview](https://github.com/MoResch12/MA_img/blob/main/MA_Git_summary.png)

---

### 📱 [AREC - Austrian Real Estate Challenge TU Wien & Stanford University](https://www.tuwien.at/mwbw/im/ie/ifm/arec-austrian-real-estate-challenge) 
Also known as [ME310](https://sites.google.com/stanford.edu/global-engineering-design-inno)
**Description:** A 1 year project to learn how to approach a problem set by our industry partners, develope prototypes and finally come up with a working solution. This was done in a team consisting of students from the TU Wien and Stanford and included 2 stays at Stanford.  
Our industry partners were Austrian real estate companies that wanted to collect ESG data (EU requirement) in their commercial buildings, while maintaining tenant comfort. Especially the measurement of the "Social" aspect is a challenge.  
Our final solution was a sensor box that provided a number of environemnt data (see Fig. below) and an anonymized occupancy heatmap. With this, the operator has direct insights on workspace quality and interaction data with certain areas. Especially with the occupancy heatmap, measures to improve the "Social" metric can be verified (e.g. do tenenats acutally use the new sofas). This data can later also be used to further automate and optimize the HVAC system.  
**Tech Stack:** Python, C++, HTML, CAD

![Arec_summary](https://github.com/MoResch12/AREC/blob/main/AREC_summary.png)

[🔗 View Project](https://github.com/ME310-AREC-2023?view_as=public) 

---


### 🌐 [Autonomous Racing](https://www.tuwien.at/inf/scuderia-segfault/)
**Description:** This project is part of the international [RoboRacer program](https://roboracer.ai/), where the TU Wien was able to secure victories and podium spots in the last years. In a team of 5 we implemented the software for an autonomous (toy-) race car, which was equipped with all the typical hardware, including Lidar, Nvidia Jetson Xavier, IMU, cameras, etc. The task was to autonomously race against other participating teams.  Troughout the course, we implemented different alogorithms (Follow the wall, Follow the gap, etc.) and ultimately settled on a mix of "Pure Pursuit" and "Disparity Extender" algorithms. While no obstacle was detected, the car used the faster "Pure Pursuit", following an optimized race line. As soon as obstacles were detected, the system switched to "Disparity Extender" to drive around. Unfortunately, the Code details are not publicly available.  
**Tech Stack:** Python, C++, Ros2, Docker

![AutRacing_collage](https://github.com/MoResch12/AutonomousRacing/blob/main/AutRacing_img.png)

---

### 📊 Reinforcement Learning - Teach a quadruped how to walk
**Description:** In this project we (group of 4) implemented and trained a Robust Policy Optimization (RPO) based RL framework to achieve locomotion on a 4-legged Unitree Go1 robot. For the final implementation, various reward functions (e.g. orientation, energy, feet contact, airtime, etc.) were combined with General Advantage Estimation (GAE), a cartesian PD controller and more to achieve locomotion across various walking speeds.  
A short report provided in the repository gives insights on the implementation details.  
**Tech Stack:** Python (gymnasium, mujoco, torch ...)

[🔗 View Project](https://github.com/MoResch12/DL_Unitree/tree/main)

![RL Project walking img](https://github.com/MoResch12/DL_Unitree/blob/main/walk_on_rand_obstacles.png)

---
## 📫 Get in Touch

- [LinkedIn](https://www.linkedin.com/in/moritz-resch-708436131/)  
- [Email](mailto:moritz@resch-vienna.at)  

---


<!--
**MoResch12/MoResch12** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
