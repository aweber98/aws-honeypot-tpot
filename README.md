# AWS Honeypot Deployment (T-Pot)

## Overview
This project demonstrates the deployment of a cloud-based honeypot using AWS EC2 and T-Pot to capture and analyze real-world cyber attacks.

## Technologies Used
- AWS EC2
- Ubuntu Linux
- T-Pot (Docker-based honeypot platform)
- Cowrie, Dionaea, Heralding

## Features
- Captures brute-force attacks and port scans
- Logs attacker commands and behavior
- Visualizes global attack sources
- Simulates vulnerable services

## Architecture
- Internet-facing EC2 instance
- Open ports (SSH, HTTP, FTP, etc.)
- Logging and monitoring via T-Pot

## Key Findings
- Attackers follow patterns: scan → access → execute
- High volume of automated attacks
- Most targeted protocols: HTTP, SSH

## Setup Steps
1. Launch AWS EC2 instance
2. Install Docker + T-Pot
3. Configure security groups (open ports)
4. Deploy honeypot containers
5. Monitor logs

## Screenshots
<img width="720" height="345" alt="Picture7" src="https://github.com/user-attachments/assets/7a7fdaae-05dd-4d34-afe3-761655eac9a6" />
<img width="576" height="300" alt="Picture8" src="https://github.com/user-attachments/assets/7004da4a-81ba-4f38-a6aa-0b60baa8595b" />
<img width="576" height="300" alt="Picture9" src="https://github.com/user-attachments/assets/05262e59-1384-4f49-8f8e-f8b5e87061b3" />
<img width="720" height="375" alt="Picture1" src="https://github.com/user-attachments/assets/30ae2015-8a2d-40f3-94b9-d717672fae28" />
<img width="720" height="375" alt="Picture2" src="https://github.com/user-attachments/assets/e56f3b56-4d9f-44f7-a127-6125cc674997" />
<img width="720" height="375" alt="Picture3" src="https://github.com/user-attachments/assets/733fb532-7aff-4773-9a1c-7341010538d7" />
<img width="576" height="324" alt="Picture5" src="https://github.com/user-attachments/assets/53968590-af5d-4301-bbe3-2a956f5adb86" />
<img width="576" height="345" alt="Picture6" src="https://github.com/user-attachments/assets/12589966-9207-4244-8b1e-7ccfddf847a8" />


## What I Learned
- Cloud security deployment
- Threat analysis
- Real-world attacker behavior
