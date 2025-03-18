# Project Sentinel – Smart Workplace Sensor for High-Risk Professions

## 1. Introduction and Background

### Purpose and Goals

Project Sentinel aims to create an intelligent and proactive safety solution for high-risk workplaces. By utilizing advanced IoT sensors and data analysis, the system will identify and alert users to potential hazards in the work enviroment, in real-time. This reduces the number of accidents and creates a safer work environment.

### Problem Description

Many professions are exposed daily to risks such as hazardous gases, noise, temperature fluctuations, and falls. Current safety measures are often reactive rather than proactive. Project Sentinel addresses this by:

- Detecting workplace hazards in real-time.
- Automatically alerting users and managers to potential threats.
- Analyzing historical data to identify risk patterns and prevent future accidents.

### Target Audience

- Construction and infrastructure sectors
- Industrial and manufacturing sectors
- Firefighters and emergency responders
- Healthcare and emergency medical personnel
- Transportation and logistics sector

## 2. Technology Selection and Architecture

### Technologies

- **Frontend:** React Native for mobile apps (iOS & Android)
- **Backend:** Node.js with Express, PostgreSQL
- **Hardware:** ESP32, LoRaWAN/LTE/WiFi (undecided), accelerometer (LSM6DS3), gas sensor (MQ-2), temperature sensor (DHT11), microphone (SPH0645?), EKG sensor (AD8232)

### System Architecture

- **Frontend**: Mobile application for real-time data, alerts, and historical analysis.
- **Backend**: API for data collection and processing.
- **IoT Devices**: Sensors for gas, temperature, noise, falls, and heart rate.

### API and Database Structure

- **API Endpoints**: Authentication, data collection, alerts, statistics.
- **Database**: PostgreSQL with tables for users, sensor data, incidents.

## 3. Team Structure and Responsibilities

| Role | Team Members | Responsibilities |
|------|--------------|----------------|
| **Frontend** | Hannele, Rebecka | UI/UX, mobile app, API integration |
| **Fullstack** | Simon, Chie, Elin, Milton | Backend, database, API, authentication |
| **System Development** | Eric, Fredrik, Filip, Chengjun | Sensors, data handling, communication |

### Collaboration

- Joint project planning and daily standups.
- Sprint-based development with 2-week iterations.
- Weekly retrospectives and sprint reviews.

## 4. Work Methodology and Tools

- **Agile methodology:** Scrum with sprint planning, standups, retrospectives.
- **Code management:** GitHub (pull requests, code reviews, branches).
- **Communication:** Exclusivley through Discord.
- **Sprint planning:** Github Projects.

## 5. Timeline and Milestones

| Week | Activity | Team Tasks |
|------|----------|------------|
| 10-12 | Brainstorming, team allocation, research, hardware selection | All teams participate in project planning and technology selection |
|| Frontend: Create wireframes and UI design; Backend: Define API structure; IoT: Test and select sensors |
| 12 | Project plan completed & approved | All teams finalize the project plan and present for approval |
| 13-16 | Development of frontend, backend, and IoT components | Frontend: Implement basic UI/UX; Backend: Develop API and database; IoT: Program sensors and data collection |
| 17-19 | Integration and testing | Frontend & Backend: API integration; IoT & Backend: Data communication between sensors and cloud |
| 20-21 | Optimization and finalization | All teams work on performance improvements and bug fixes |
| 22 | Testing and quality assurance | System-wide testing with real-life scenarios |
| 23 | Demo, evaluation, and retrospective | Presentation of the project and team retrospective |

## 6. Risk Analysis and Problem Management

| Risk | Mitigation Strategy |
|------|-----------------|
| Communication issues | Regular standups and sync meetings |
| Technical complexity | Modular development and iterative testing |
| Time constraints | Prioritizing MVP and iterative delivery |

## 7. Deliverables and Documentation

- **Frontend:** Mobile app with alerts and real-time data.
- **Backend:** API for data collection and analysis.
- **IoT:** Sensor network with real-time monitoring.
- **Documentation:** README.md, API-DOCUMENTATION.md, TESTING.md, ARCHITECTURE.md, ACCESSIBILITY.md, CHANGELOG.md, RETROSPECTIV.md.
