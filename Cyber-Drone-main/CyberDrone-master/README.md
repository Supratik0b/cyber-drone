# Cyber Attacks Using UAVs

## 📌 Overview
This project explores the **cybersecurity vulnerabilities of Unmanned Aerial Vehicles (UAVs)** and demonstrates how drones can both be targets and tools of cyber attacks. The study focuses on **Wi-Fi, GPS, and control system vulnerabilities**, providing a comprehensive review of threats, experimental demonstrations of attacks, and proposed countermeasures.

## 🎯 Objectives
- Analyze the **security challenges of UAV systems**.  
- Demonstrate different **cyber attacks on drones**, such as:
  - Pass-the-Hash Attack  
  - Evil Twin Attack  
  - PMKID Attack  
  - Denial-of-Service (DoS)  
  - Beacon Attack  
  - Video Interception  
  - GPS Spoofing  
- Propose **preventive measures and countermeasures** to secure UAV systems.  
- Raise awareness about **cyber airworthiness and cyber reliability** in UAV deployments.  

## 🛠️ Methodology
- Designed a quadcopter model to understand UAV **architecture and communication mechanisms**.  
- Conducted experimental setups using **ESP32/NodeMCU boards, Raspberry Pi, and Wi-Fi tools**.  
- Simulated real-world attacks on UAV communication channels.  
- Evaluated **countermeasures such as WPA3, intrusion detection, password management, and encryption**.  

## 📡 Types of UAV Communications Studied
- **Drone-to-Drone (D2D)**  
- **Drone-to-Ground Station (D2GS)**  
- **Drone-to-Network (D2N)**  
- **Drone-to-Satellite (D2S)**  

## 🚨 Attacks Demonstrated
- **Physical Attacks** – surveillance abuse, UAV crashes, payload threats.  
- **Logical Attacks** – Wi-Fi spoofing, man-in-the-middle, rogue access points, malware injection.  

## 🔐 Proposed Countermeasures
- Use of **WPA3 encryption & secure protocols**.  
- **Password management & privilege separation**.  
- **Wireless intrusion detection systems (WIDS)** for DoS detection.  
- **Beacon frame integrity checks**.  
- **Encrypted video streaming** to prevent interception.  

## ⚠️ Security Concerns
- Lack of built-in UAV safety features.  
- Absence of strong operational standards.  
- Vulnerability to **GPS jamming and spoofing**.  

## 📖 Conclusion
UAVs are rapidly becoming part of modern **smart cities, defense, and industrial operations**, but their lack of robust security protocols makes them vulnerable. This project highlights **real attack demonstrations and effective countermeasures** to secure UAV ecosystems against cyber threats.  


