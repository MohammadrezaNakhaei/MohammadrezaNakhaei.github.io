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

I'm a first year PhD student at [Robot Learning Lab](https://rl.aalto.fi/) at Aalto University under supervision of [Dr. Joni Pajarinen](https://people.aalto.fi/joni.pajarinen). Currently, my research is focused on reinforcement learning and robotics. To be more specific, I'm investigating planning in offline goal-conditioned RL. Also I am involved in an industrial project where we are using spot robot to autonomously colllect data on construction site. 

I got my master degree in mechatronics engineering at University of Tehran. I was supervised by Dr. Askari Moghadam and my research was about supervised methods in reinforcement learning. I investigated methods to imrpove the stablity and performance of reward-conditioned methods by considering sequential models (GRU, LSTM, Clockwork RNN, and Transformers) in the behavior function and intrinsic reward to encourage more efficient exploration. 

I got my bachelor degree in mechanical engineering at Iran University of Science and Technology. I was a member of robotic research lab supervised by Prof. Habibnejad Korayem where I had the chance to learn about industrial manipulators (particularly Hyundai HS group), different control methods (optimal, robust and adaptive), robotics, and basic electronics. 

# 📝 Publications 
<!---
##  Preprints


<div class='small-paper-box'>
  <div class='small-paper-box-image'><div>
  <img src='images/wenyan_yang_offline_gcrl.png' alt="sym" width="100%"></div></div>
  <div class='small-paper-box-text' markdown="1">

  [Swapped goal-conditioned offline Reinforcement Learning](https://arxiv.org/pdf/2302.08865), 
  - **Wenyan Yang**, Huiling Wang, Dingding Cai, Joni Pajarinen, Joni-Kristen Kämäräinen
  - `Preprint` arXiv, 2023
 
</div>
</div>
-->

##  Conferences

<div class='small-paper-box'>
  <div class='small-paper-box-image'><div>
  <img src='images/HS165.jpg' alt="sym" width="100%"></div></div>
  <div class='small-paper-box-text' markdown="1">

  [Dynamic modeling of industrial manipulator Hyundai HS165 in order to determine the dynamic load-carrying capacity for a specified trajectory](https://ieeexplore.ieee.org/abstract/document/9071847) 
  - **Mohammadreza Nakhaei**, A. Habibnejad Korayem
  - `ICROM 2019` 
 
</div>
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
  <img src='images/2dCNC.png' alt="sym" width="100%"></div></div>
  <div class='paper-box-text' markdown="1">


  **2d Drawing CNC**
  -  In charge of electronics and programming, used a modified version of Marlin and GRBL to control the machine.
  - LightBurn software was for creating G-cod
</div>
</div>

# 💬 Talks and Presentations
- **Decision transformer: Reinforcement learning via sequence modeling** | [Video](https://youtu.be/vVoVYV-5hl0)
- **Improved learning of robot manipulation tasks via tactile intrinsic motivation** | [Video](https://youtu.be/Nn8XBfLV7uA)

# 🎖Skills

-Programming: Proficient in Python and past experience MATLAB anc c++

-Tools: Proficient in PyTorch, Numpy. Experience with ROS, JAX, LaTeX, Git, Bash

-Software: Experiance with SolidWorks, Msc ADAMS
<br/><br/>







