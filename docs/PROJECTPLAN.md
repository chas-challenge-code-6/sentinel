# Project Sentinel – Smart Workplace Sensor for High-Risk Professions

## 1. Introduction and Background

### Purpose and Goals

Project Sentinel aims to create an intelligent and proactive safety solution for high-risk workplaces. By utilizing advanced IoT sensors and data analysis, the system will identify and alert users to potential hazards in the work environment in real-time. This reduces the number of accidents and creates a safer work environment.

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
- Transportation and logistics sectors

## 2. Technology Selection and Architecture

### Technologies

- **Frontend:** React Native for mobile apps (iOS & Android), Figma
- **Backend:** Node.js with Express, SQL
- **Hardware:** ESP32, LTE/WiFi, accelerometer, gas sensor, temperature sensor, microphone, EKG sensor.
- **Languages:** C++, Javascript, SQL

### System Architecture

- **Frontend:** Mobile application for real-time data, alerts, and historical analysis.
- **Backend:** API for data collection and processing. SQL and server managment
- **IoT Devices:** Sensors for gas, temperature, noise, falls, and heart rate.

### API and Database Structure

- **API Endpoints:** Authentication, data collection, alerts, statistics.
- **Database:** SQL with tables for users, sensor data, and incidents.

## 3. Team Structure and Responsibilities

| Role | Team Members | Responsibilities |
|------|--------------|------------------|
| **Frontend** | Hannele, Rebecka | UI/UX, mobile app, API integration |
| **Fullstack** | Simon, Chie, Elin, Milton | Backend, database, API, authentication |
| **System Development** | Eric, Fredrik, Filip, Chengjun | Sensors, data handling, communication |

### Collaboration

- Joint project planning and weekly standups on tuesdays.
- Sprint-based development with iteration every friday.
- Weekly retrospectives and sprint reviews.

## 4. Work Methodology and Tools

- **Agile methodology:** Scrumban with sprint planning, standups, and retrospectives.
- **Code management:** GitHub (pull requests, code reviews, branches).
- **Communication:** Exclusively through Discord.
- **Sprint planning:** GitHub Projects.

## 5. Timeline and Milestones

| Week  | Activity                              | Team Tasks                                                                 |
|-------|---------------------------------------|----------------------------------------------------------------------------|
| 10-12 | Brainstorming, team allocation, research, hardware selection | All teams participate in project planning and technology selection. IoT: Test and select sensors. |
| 12    | Project plan completed & approved     | All teams finalize the project plan and present it for approval.           |
| 13-14 | First iteration of application and hardware                                      | Frontend: Create wireframes and UI design; Backend: Define API structure;
| 13-17 | Development of frontend, backend, and IoT components | Frontend: Implement basic UI/UX; Backend: Develop API and database; IoT: Program sensors and data collection. |
| 17-19 | Integration and testing               | Frontend & Backend: API integration; IoT & Backend: Data communication between sensors and cloud. |
| 20-21 | Optimization and finalization         | All teams work on performance improvements and bug fixes.                  |
| 22    | Testing and quality assurance         | System-wide testing with real-life scenarios.                              |
| 23    | Demo, evaluation, and retrospective   | Presentation of the project and team retrospective.                        |

## 6. Risk Analysis and Problem Management

| Risk                | Mitigation Strategy                                                                 |
|---------------------|-------------------------------------------------------------------------------------|
| Communication issues | Regular standups, sync meetings, structured communication. |
| Members failing to deliver  | Team meeting to find possible solutions or lastly contact schoolboard |
| Technical complexity | Modular development, iterative testing, detailed documentation, knowledge sharing sessions, and prototyping of complex components. |
| Time constraints     | Prioritizing MVP and iterative delivery.                                           |

## 7. Deliverables and Documentation

- **Frontend:** Mobile app with alerts and real-time data.
- **Backend:** API for data collection and analysis.
- **Software and hardware developers:** Hardware and software demo progress.
- **IoT:** Sensor network with real-time monitoring.
- **Documentation:** README.md, API-DOCUMENTATION.md, TESTING.md, ARCHITECTURE.md, ACCESSIBILITY.md, CHANGELOG.md, RETROSPECTIVE.md.
