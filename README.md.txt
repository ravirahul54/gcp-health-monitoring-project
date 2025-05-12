## GCP Health Monitoring Project

## Overview
This project demonstrates how to simulate real-time cloud infrastructure monitoring using Google Cloud Monitoring, Logging, and Alerting. It tracks system performance, logs, and simulates incident detection and response.

## Tools Used
- Google Compute Engine
- Cloud Monitoring
- Cloud Logging
- Alert Policies
- IAM

## Features
- Metric-based alerts (e.g., CPU usage > 80%)
- Log-based alerts (on ERROR severity)
- Uptime checks for availability
- Notification via email
- IAM-based access control

## Architecture
![Architecture Diagram](monitoring-architecture.png)

## Setup Instructions
1. Deploy a VM using Compute Engine
2. Enable Logging & Monitoring APIs
3. Configure logging agent (optional)
4. Set up alerting policies (CPU, logs)
5. Add email notification channels
6. Simulate load using SSH and `yes > /dev/null`

## Screenshots
See `/alert-policy-screenshots` for alert configurations and test results.

## Documentation
- [📄 Project Summary PDF](GCP_Health_Monitoring_Project_Summary.pdf)

## Author
Ravi Rahul Namballa
