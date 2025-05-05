# L3flood
A lightweight Layer 3 flood utility in C that quickly sends large volumes of echo requests to simulate high-traffic conditions. It helps network admins and security researchers assess the resilience of devices and infrastructure under stress and evaluate their ability to handle DoS attacks in real-world scenarios.

## 📖 Overview

**L3flood** is a simple yet effective Layer 3 flood tool written in C. It crafts and sends raw icmp packets in a tight loop, allowing users to test the robustness of local or remote network endpoints under high traffic volume.

> ⚠️ This tool is intended for **educational** and **testing** purposes only. Never run it against networks you do not own or have explicit permission to test.

---

## ⚙️ Features

- Raw socket-based packet crafting
- Custom spoofed source IP support
- Optional payload size customization
- Lightweight, minimal dependencies
- Prints real-time packet send counter

---
