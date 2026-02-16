---
title: "Automated Robotic Quality Control System"
date: 2026-02-01
description: "Robotics, computer vision, and REST API for automated inspection"
tags: ["robotics", "python", "opencv", "fastapi", "automation"]
weight: 5
---

**Timeline:** February 2026 - April 2026 (expected completion) · **Category:** 🎓 Education

As part of my final technical project, I am developing (February - April 2026) an automated robotic quality control system that combines robotics, computer vision, and backend API design.

This project serves as the capstone of my technical education program.

The system performs objective and reproducible quality inspection of configurable 3D-printed cubes.

It integrates robotics, image processing, and REST-based system architecture into a unified workflow.

## System Goals

The project automates the complete inspection pipeline:

- A robotic arm automatically handles finished parts
- A camera-based vision system detects configuration details
- Image data is analyzed using OpenCV
- Detected values are compared with expected JSON configurations
- Parts are automatically sorted based on inspection results
- All results are logged in a database
- A REST API exposes inspection data to external systems

## Architecture & Modules

The system is divided into modular components:

**Configuration Module**
- JSON-based configuration system
- API-driven parameter transfer
- Independent testability

**Robotics Module**
- Automated gripping and positioning
- Reproducible camera alignment
- Sorting based on inspection results

**Computer Vision Module**
- OpenCV-based image analysis
- HSV color detection
- Feature recognition
- Structured data extraction

**Comparison Engine**
- Automated validation of expected vs actual values
- Deterministic inspection results

**Logging System**
- SQLite database storage
- Timestamped inspection history
- Traceable quality records

**REST API Layer**
- FastAPI backend
- JSON endpoints for external integration
- System interoperability

## Engineering Focus

Key engineering challenges addressed:

- Reliable robot positioning
- Reproducible image capture
- Computer vision accuracy (>95%)
- Modular software architecture
- API-based system integration
- Hardware-software interaction
- System safety and fault handling

## Results & Impact

The project demonstrates:

- Integration of robotics and backend software
- Practical computer vision implementation
- Modular system architecture
- Automated quality assurance workflows
- Industrial automation concepts
- Scalable API-based design

## Skills Demonstrated

- Robotics programming
- Computer vision engineering
- Backend API development
- System architecture design
- Hardware-software integration
- Automation engineering
- Structured project planning

## Tech Stack

**Software:** Python 3.11 · FastAPI · OpenCV · SQLite · JSON · Git

**Hardware:** Niryo Ned2 Robotic Arm · USB Camera · Controlled Lighting · Custom Fixtures
