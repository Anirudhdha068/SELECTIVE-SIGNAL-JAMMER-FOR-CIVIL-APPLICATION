# Selective Signal Jammer for Civilian Applications

🏆 Codeversity National Level Hackathon – 2026  
👥 Team Diamonds  

---

## Overview
This project presents a **microcontroller-based wireless signal control system** designed for civilian and institutional environments. The system allows controlled disruption of wireless communication through a **web-based interface hosted on the ESP device itself**.

The goal of the project is to demonstrate **responsible and selective signal control**, avoiding indiscriminate disruption while maintaining flexibility for controlled environments.

---

## System Highlights
- ESP-based embedded system
- Web interface accessed via ESP local IP
- Real-time Wi-Fi scan & control
- Two operational modes
- Portable and low-cost prototype (~₹5,000)

---

## Modes of Operation

### 1️⃣ Normal Mode (Implemented & Uploaded)
- Operates on **Wi-Fi and BLE**
- Performs controlled deauthentication
- Used for demonstration and testing
- **Source code available in this repository**

### 2️⃣ Selective Mode (Advanced / Partial Implementation)
- Focuses on **Wi-Fi-based selective control**
- Targets only unidentified or unauthorized devices
- Operated via web interface
- Core logic under active development and optimization

> The selective mode represents the innovative direction of this project and is demonstrated through system architecture, UI flow, and testing results.

---

## Web Interface
- Hosted directly on ESP device
- Accessed via local IP address
- Features:
  - Scan nearby Wi-Fi networks
  - Switch between modes
  - Start/stop signal control
  - View device activity

---

## Hardware Components
- ESP series microcontroller
- Wireless transceiver modules
- Antenna system
- Power management circuit
- Portable enclosure

---

## Source Code Policy
This repository includes **working firmware for the Normal Mode** to demonstrate practical implementation.

Advanced selective logic is intentionally limited to architecture and UI demonstration due to:
- Security considerations
- Ongoing optimization
- Responsible disclosure practices

---

## Media & Demonstration
Project images, UI screenshots, and working videos are provided in the `/media` and `/demo` sections.

---

## Conclusion
This project demonstrates a practical embedded system capable of controlled wireless signal handling, combining affordability, portability, and a strong foundation for future intelligent enhancements.
