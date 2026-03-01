# 🛩️ Multi-Drone Leader–Follower Swarm System  
### Simulation + Raspberry Pi Network Validation (ROS-Based)

🎥 **Demonstration Video**  
https://youtu.be/iEC_uNLix1s  

---

## 📌 Project Overview

This repository documents the demonstration and validation of a 4-drone leader–follower swarm architecture implemented using the Robot Operating System (ROS).

The system was tested in both:

- Simulation environment  
- Embedded Raspberry Pi deployment over WiFi network  

Due to NDA restrictions under Team Arrow, source code and configuration files cannot be publicly shared. This repository serves as a technical showcase of system behavior, architectural design, and validation process.

---

## 🎯 Objective

The primary objectives of this project were:

- Implement coordinated multi-drone swarm behavior  
- Establish a communication-based leader–follower architecture  
- Validate distributed ROS communication across hardware nodes  
- Observe and evaluate network latency effects on formation stability  

This project serves as a baseline communication-driven swarm system.

---

## 🧠 System Concept

The swarm follows a **leader–follower model**:

- **Drone 1 → Leader (manually controlled)**
- **Drones 2, 3, 4 → Followers**

Each follower:

- Subscribes to custom made pose data via ROS topics  
- Computes control outputs using feedback logic  
- Maintains relative formation offset  


