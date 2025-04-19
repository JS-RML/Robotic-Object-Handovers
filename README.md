# Robotic-Object-Handovers
-------------
## Table of Contents
- [1. Overview](#1-overview)
  * [Self-Righting](#self-righting)
  * [Palm-To-Surface Handover](#palm-to-surface-handover)
- [2. Prerequisites](#2-prerequisites)
  * [Hardware](#hardware)
  * [Sotfware](#sotfware)
- [3. Getting Started](#3-getting-started)
  * [./ur5_start.sh](##ur5startsh)
------------
# 1. Overview
This repository contains a simulation approach to model the occurrence of __Self-Righting__ behavior of planar-based rigid objects supported on two contact points under the influence of gravity, and also provides the software implementation of robotic __Palm-to-Surface Handover__.

## Self-Righting
GIF
## Palm-To-Surface Handover
![Image](https://github.com/user-attachments/assets/5b8d6f74-0ea4-4d87-9dff-f5e7c758bc65)
# 2. Prerequisites
## Hardware
- [Universal Robots UR5e](https://www.universal-robots.com/products/ur5e/): Industrial robot arm
- [Robotis RH-P12-RN gripper](https://www.robotis.com/model/page.php?co_id=prd_hand): Two-fingered gripper, where one of the fingers is customized as a "palm", as shown in the image below.
- Palm: 3D printed

![Image](https://github.com/user-attachments/assets/228ac45a-89e8-47fa-b46a-6f8126e5e6da)

## Sotfware
Our simulation software is implemented with __Matlab 2024b__, and 
# 3. Getting Started
## ./ur5_start.sh
    ./ur5_start.sh
