---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>
<style>body {text-align: justify}</style>

I am a third-year PhD student at the [Robot Learning Lab](https://rl.aalto.fi/) at Aalto University, supervised by [Dr. Joni Pajarinen](https://people.aalto.fi/joni.pajarinen).  
My current research focuses on reinforcement learning and robotics, with a particular emphasis on **offline meta-RL**. In this setting, the goal is to train generalizable policies by leveraging datasets from multiple tasks. I am also interested in **representation learning**, such as developing efficient latent world models and studying disentanglement.

I earned my Master’s degree in Mechatronics Engineering from the University of Tehran, under the supervision of Dr. Askari Moghadam. My research explored supervised methods in reinforcement learning, focusing on improving the stability and performance of reward-conditioned methods. I investigated the use of sequential models (GRU, LSTM, Clockwork RNN, and Transformers) in the behavior function, along with intrinsic rewards to encourage more efficient exploration.

I obtained my Bachelor’s degree in Mechanical Engineering from the Iran University of Science and Technology. As a member of the Robotics Research Lab, supervised by Prof. Habibnejad Korayem, I gained hands-on experience with industrial manipulators (particularly the Hyundai HS series), various control methods (optimal, robust, and adaptive), robotics, and basic electronics.
# 📰 News
- **11-06-2025**: **[New Publication Alert]**: My M.Sc. research on **Upside-down RL** has been accepted to the Journal of Information and Intelligence! 🎉  
- **24-04-2025**: I'm attending [ICLR 2025](https://iclr.cc/Conferences/2025) conference at Singapore, looking forward meeting top-level ML researchers and presenting our work. 
- **25-02-2025**: [Zhiyuan Li](https://lizhyun.github.io/) will present my paper at AAAI 2025 at Philadelphia, USA.
- **01-02-2025**: My research visit at Amsterdam ended, thanks [Kevin Luck](https://kevin-luck.com/) for this amazing oppurtunity.
- **22-01-2025**: **[New Publication Alert]**: Our latest research on **Latent World Models** has been accepted to ICLR 2025! 🎉  
- **10-12-2024**: My visa application to attend AAAI 2025 at US was rejected! 
- **10-12-2024**: **[New Publication Alert]**: Our latest research on **offline meta-RL** has been accepted to AAAI 2025! 🎉  
- **01-09-2022**: I'm starting a visit research at [computational intelligence (CI)](https://cs.vu.nl/ci/) research group under supversiion of [Prof. Kevin Luck](https://kevin-luck.com/) At Vrije Universiteit Amsterdam.
- **18-07-2024**: **[Workshop Presentation]**: Our latest research on **Quantized Representation in Self Predictive RL** will be presented at [Arlet@ICML2024](https://arlet-workshop.github.io/icml2024/about).
- **15-07-2024**: I'm attending [L4DC 2024](https://l4dc.web.ox.ac.uk/home) conference at Oxford, UK. 
- **28-03-2024**: **[New Publication Alert]**: Our latest research on **Adaptation in RL** has been accepted to L4DC 2024! 🎉
- **13-08-2023**: I'm attending [IWIALS](https://www.ias.informatik.tu-darmstadt.de/Workshops/IWIALS2023) workshop at Kleinwalsertal, Austria. 
- **22-09-2022**: I'm a teaching assistant for reinforcement learning (RL) course. 
- **22-09-2022**: I'm starting my PhD at [robot learning lab](https://rl.aalto.fi/) at Aalto University, Finland.  


# 📝 Publications 

##  Conferences
<div class='small-paper-box'>
  <div class='small-paper-box-image'><div>
  <img src='images/ertrl.png' alt="sym" width="100%"></div></div>
  <div class='small-paper-box-text' markdown="1">

  [Entropy Regularized Task Representation Learning for Offline Meta-Reinforcement Learning](https://ojs.aaai.org/index.php/AAAI/article/view/34160) 
  - **Mohammadreza Nakhaei**, Aidan Scannell, Joni Pajarinen
  - `AAAI 2025`  [Code](https://github.com/mohammadrezanakhaei/er-trl)
</div>
</div>


<div class='small-paper-box'>
  <div class='small-paper-box-image'><div>
  <img src='images/dcwm.png' alt="sym" width="100%"></div></div>
  <div class='small-paper-box-text' markdown="1">

  [Discrete Codebook World Models for Continuous Control](https://openreview.net/forum?id=lfRYzd8ady) 
  - Aidan Scannell, **Mohammadreza Nakhaei**, Kalle Kujanpää, Yi Zhao, Kevin Sebastian Luck, Arno Solin, Joni Pajarinen
  - `ICLR 2025`  [Code](https://github.com/aidanscannell/dcmpc)
 
</div>
</div>

<div class='small-paper-box'>
  <div class='small-paper-box-image'><div>
  <img src='images/relce_overview.jpg' alt="sym" width="100%"></div></div>
  <div class='small-paper-box-text' markdown="1">

  [Residual learning and context encoding for adaptive offline-to-online reinforcement learning](https://proceedings.mlr.press/v242/nakhaeinezhadfard24a.html) 
  - **Mohammadreza Nakhaei**, Aidan Scannell, Joni Pajarinen
  - `L4DC 2024`  [Code](https://github.com/MohammadrezaNakhaei/ReLCE)
</div>
</div>

<div class='small-paper-box'>
  <div class='small-paper-box-image'><div>
  <img src='images/HS165.jpg' alt="sym" width="100%"></div></div>
  <div class='small-paper-box-text' markdown="1">

  [Dynamic modeling of industrial manipulator Hyundai HS165 in order to determine the dynamic load-carrying capacity for a specified trajectory](https://ieeexplore.ieee.org/abstract/document/9071847) 
  - **Mohammadreza Nakhaei**, A. Habibnejad Korayem
  - `ICROM 2019` 
 
</div>
</div>

## Journals

  <div class='small-paper-box-text' markdown="1">

  [Improving sample efficiency and exploration in upside-down reinforcement learning](https://www.sciencedirect.com/science/article/pii/S2949715925000174) 
  - **Mohammadreza Nakhaei**, Reza Askari Moghaddam
  - `Journal of Information and Intelligence 2025` 
</div>

# 👨‍💻 Projects

## Industrial projects

**Automatic path planning of spraying robot**

  - *2020 - 2021*
  -  SQ 15_06N manipulator for spraying different bodies in the factory
  -  Program capable of generating and simulating default paths in the robot such as linear, circular, zigzag and automatic path generation. 
  - Matlab GUI was first tried, which was slow and hard to maintain. [RoboDK](https://robodk.com/) was used instead.

## Other projects

<div class='paper-box'>
  <div class='paper-box-image'><div>
  <img src='images/2dCNC.jpg' alt="sym" width="80%"></div></div>
  <div class='paper-box-text' markdown="1">


  **2d Drawing CNC**
  -  In charge of electronics and programming, used a modified version of Marlin and GRBL to control the machine.
  - LightBurn software was for creating G-cod
</div>
</div>

# 🎖 Skills

-Programming: Proficient in Python and past experience with MATLAB anc C++

-Tools: Proficient in PyTorch, Numpy. Experience with ROS/ROS2, JAX, LaTeX, Git, Bash

-Software: Experiance with Microsoft Office, SolidWorks, Msc ADAMS

