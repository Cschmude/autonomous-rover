# Autonomous Rover

A Python-based autonomous ground rover built on a Raspberry Pi 4, 
designed to navigate unstructured environments using sensor fusion 
between an IMU and ultrasonic sensors. Built as a pre-college 
engineering project to develop hands-on experience in embedded 
systems, autonomous navigation, and engineering documentation —
directly relevant to my planned work on MSOE's Lunarbotics team.

---

## Project Goals

- Design and build a functioning autonomous rover from scratch
- Implement sensor fusion between an MPU-6050 IMU and HC-SR04 
  ultrasonic sensors
- Log and analyze all sensor data and navigation decisions in Python
- Document the full engineering process including failures, 
  iterations, and analysis
- Produce a complete CAD model of the final assembly in Onshape

---

## Phases

| Phase | Description                         | Status      |
|-------|-------------------------------------|-------------|
| 1     | Construction and Movement           | Not Started |
| 2     | Sensor Integration and Data Logging | Not Started |
| 3     | Autonomous Navigation               | Not Started |
| 4     | Analysis and Documentation          | Not Started |

---

## Phase Details

### Phase 1 — Construction and Movement
Assemble the rover chassis, configure the Raspberry Pi headless 
over WiFi, and implement manual control from a laptop keyboard 
via SSH.

**Deliverable:** Rover drives reliably in all directions from 
a laptop over WiFi.

### Phase 2 — Sensor Integration and Data Logging
Wire and integrate the IMU and ultrasonic sensors, implement 
continuous data logging to CSV, and build Matplotlib 
visualizations of each run.

**Deliverable:** Every run produces a plotted dataset of speed, 
heading, and obstacle distances over time.

### Phase 3 — Autonomous Navigation
Implement obstacle detection logic, sensor fusion, and a 
decision-making algorithm. Log every navigation decision 
with reasoning for post-run analysis.

**Deliverable:** Rover navigates a room autonomously and 
produces a complete mission log.

### Phase 4 — Analysis and Documentation
Analyze mission logs in Python, write engineering reports 
for each test run, produce a full CAD model in Onshape, 
and finalize the GitHub repository.

**Deliverable:** Complete public portfolio project with code, 
data, analysis, and CAD documentation.

---

## Hardware

| Component | Purpose |
|-----------|---------|
| Raspberry Pi 4 (2GB) | Main compute |
| SunFounder Smart Car Kit | Chassis, motors, motor driver |
| MPU-6050 IMU | Acceleration and orientation |
| HC-SR04 Ultrasonic Sensors (x3) | Obstacle detection |
| Raspberry Pi Camera Module v2 | Vision (future expansion) |

---

## Software

- Python 3
- RPi.GPIO
- NumPy
- Matplotlib
- Pandas

---

## Background

I'm an incoming Mechanical Engineering student at Milwaukee 
School of Engineering (MSOE) with a minor in Aerospace 
Engineering. This project was built in preparation for joining 
MSOE's Lunarbotics team and as part of a broader goal of 
working for NASA. My background includes serving as Head of 
Electrical, Head of Programming, and Lead Driver for my 
high school FRC robotics team.

---

*Project started: May 2025*
