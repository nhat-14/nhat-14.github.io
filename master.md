---
title: (2020-2022) Master Thesis 
layout: default
parent: Works
---

## Odor Source Localization in Obstacle Regions Using Switching Planning Algorithms with a Switching Framework

<div style="text-align: justify">Odor source localization (OSL) robots are crucial for rescuing teams dealing with hazardous chemical plumes. Constructing the dispersion model of the odor plume for probabilistic odor source search algorithms is difficult due to the complex environment. In this study, I simplified the environment into sub-environments with different resolutions and proposed a framework that alternates between Infotaxis and Dijkstra algorithms to navigate the agent. This improved the success rate and reduced the average moving steps. Our implementation on an autonomous mobile robot verified its effectiveness. </div>

**Problem statements**:
* Finding gas source in obstacle region.
* Conventional algorithm such as Infotaxis is uneffective in obstacle region.
* Overcome deadlock in areas where gas concentraion is high.


### Images and Results:
<center>
  <img src="images/cpt.jpg" alt="Robot" width="600"/>
  <p>Environment are divided into sub-area and robot switch planning algorithms base on gas detection history and environment geometry</p>
</center>

<div style="text-align: center;">
  <video width="600" height="337" controls>
    <source src="images/master.mp4" type="video/mp4">
    Implementation of the switch planning algorithms framework in odor source localization
  </video>
</div>

### Additional Information:
**Location**: Kurabayashi Laboratory, Tokyo Institute of Technology, Japan.  
**Date**: From 2020 October to 2022 September.  
**Context**: This is my Master's graduation thesis at Tokyo Institute of Technology.  
**Publications**: [Luong et al. (2023)](https://www.mdpi.com/1424-8220/23/3/1140), [Luong et al. (2024)](https://doi.org/10.1080/18824889.2024.2374569).