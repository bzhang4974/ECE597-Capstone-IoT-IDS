# ECE597-Capstone-IoT-IDS
# Project Overview

This project implements a multi-stage IoT network intrusion detection system using the CIC IoT-DIAD 2024 dataset.

The system includes two main stages:

1. Packet-level unsupervised anomaly detection for initial alert generation.
2. Flow-level supervised learning for false positive reduction and final classification.

The project focuses on five attack categories:

- DDoS-HTTP Flood
- DoS-HTTP Flood
- DNS Spoofing
- Cross-Site Scripting (XSS)
- Brute Force

The repository is organized into separate modules so that each team member can work on a specific part of the pipeline while keeping the final implementation reproducible.