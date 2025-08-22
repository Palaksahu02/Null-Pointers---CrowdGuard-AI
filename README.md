# Null-Pointers---CrowdGuard-AI
Team name - Null Pointers, Project title -  CrowdGuard AI
Team Members - Rohit Singh, Palak Sahu, Tekendra Sonvarsha
## Problem Statement -- Large gatherings often face risks such as stampedes, medical emergencies, accidents, or even security threats. Traditional emergency response is usually delayed due to slow communication, lack of real-time monitoring, and human error.

## Project Description -- CrowdGuard AI

Title: CrowdGuard AI – Revolutionising Emergency Response to Save Lives

Overview:
CrowdGuard AI is an intelligent surveillance and emergency response system designed to detect overcrowded situations, abnormal activities, or potential emergencies in real-time. Using AI-powered computer vision, the system analyzes live CCTV or drone feeds, estimates crowd density, and identifies unusual movement patterns that may indicate risks such as stampedes, riots, or medical emergencies. By generating instant alerts with location details, CrowdGuard AI enables authorities to take timely preventive actions and safeguard lives.

Key Features :
Real-Time Crowd Detection: Uses AI models to detect and count people in video streams.

Dynamic Density Estimation: Calculates people per square meter to determine overcrowding levels.

Emergency Recognition: Identifies abnormal crowd behaviors (sudden rush, panic, collapse).

Automated Alerts: Sends instant notifications with crowd density and location details to emergency responders.

Scalable Input Sources: Works with CCTV cameras, drone footage, or mobile cameras.

Web-Based Dashboard: Provides a live monitoring dashboard built with Flask + React for easy visualization.

Data Logging: Stores crowd data trends for analysis and better event planning in the future.

Workflow:
Input Source: Video stream from CCTV cameras or drone footage is fed into the system.

Preprocessing: Frames are extracted, cleaned, and optimized for analysis.

AI Processing:
Object detection models (YOLO/SSD/OpenCV-based) identify and count people.

Density estimation models analyze area coverage.

Decision Layer:

Compares real-time density with predefined safety thresholds.

Detects abnormal crowd behaviors using pattern recognition.

Alert System:

If crowd density crosses safe limits or an emergency pattern is detected, an automatic alert is triggered.

Response Coordination:

Authorities receive an alert with location, density level, and risk type, enabling rapid intervention.

Modules

Video Input Module – Handles CCTV/drone camera streams.

Preprocessing Module – Frame extraction, noise reduction, and scaling.

Detection Module – Identifies individuals using trained deep learning models.

Density Estimation Module – Calculates crowd density in real time.

Emergency Detection Module – Recognizes unusual crowd patterns (rush, chaos).

Alert & Dashboard Module – Sends alerts and displays real-time data on a Flask/React dashboard.

Database & Logging Module – Stores crowd statistics for analysis and reporting.

Unique Approach

Unlike traditional surveillance that requires manual monitoring, CrowdGuard AI automates crowd analysis and emergency detection.

Uses computer vision + AI for accuracy and speed, reducing human error.

Capable of real-time response, which is critical during life-threatening emergencies.

## Teach Stack Used --
Front End: React.js, HTML, CSS, Material UI for UI components and site layout.

Machine Learning Models: Convolutional Neural Networks (CNN) with YOLOv8 for human detection.

Clustering Algorithm: DBSCAN for grouping individuals based on proximity.

Tracking: ByteTrack for multi-object tracking to measure crowd movement speed.

Back End: Flask for API management and Flask-SocketIO for real-time communication.

Video Processing: OpenCV for frame analysis and transformation to a bird’s eye view.

Other Tools: PyTorch for model implementation, Flask-CORS for enabling cross-origin requests, base64 encoding for image data transfer.

## Installation and usage --
1. Clone the Repository
2. Set Up Environment
3. Install Dependencies
4. Configure Environment

## Future Enhancements -- 

While CrowdGuard AI already provides real-time crowd monitoring and emergency response features, there are several areas where the system can be further improved in future versions:

Enhanced Accuracy with Advanced Models

Integrate more robust deep learning models (e.g., YOLOv8, EfficientDet) for better accuracy in detecting individuals in diverse lighting and weather conditions.

Multi-Camera Integration

Support for combining video feeds from multiple cameras and drones to cover larger areas and eliminate blind spots.

Predictive Analytics

Use historical data and AI models to predict crowd surges, risky areas, and potential emergencies before they occur.

Edge AI Deployment

Optimize models to run on edge devices (CCTV hardware, drones, Raspberry Pi) to reduce latency and dependence on cloud servers.

Integration with IoT & Smart Infrastructure

Connect with IoT sensors (temperature, CO₂, vibration) and public safety systems (alarms, smart lighting, exit signs) for automated response.

Mobile & Web Dashboard

A user-friendly dashboard for authorities with live crowd heatmaps, alert notifications, and decision-making tools accessible via mobile and web.

Emergency Response Automation

Automatic triggering of crowd-control measures like alarms, digital signage, or alerts to nearby authorities when thresholds are breached.

Scalability & Cloud Support

Deploy on cloud platforms (AWS, GCP, Azure) for handling large-scale, city-wide surveillance with seamless scalability.

Privacy & Compliance Features

Implement privacy-preserving techniques such as face blurring, GDPR compliance, and secure encrypted data handling.

Multilingual Voice Alerts

Add automatic voice-based alerts in multiple local languages for crowd guidance during emergencies.

