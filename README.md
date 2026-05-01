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
(Add your attack map + logs here)

## What I Learned
- Cloud security deployment
- Threat analysis
- Real-world attacker behavior
