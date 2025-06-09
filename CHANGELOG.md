# Changelog

All notable changes to this repository will be documented here.

### Added
- Integrated support for wearable-friendly sensors:
  - **MPU9250/MPU6500** for motion sensing, step tracking, and fall detection
  - **DHT22** temperature and humidity sensor
  - **MQ2** gas sensor for environmental safety alerts
  - **Battery voltage** and charge level monitoring
  - **Bluetooth heart rate monitor** (Polar H9 via BLE)
- Wireless communication modules:
  - **WiFi** with fallback to **LTE/4G** using `TinyGSM`
  - **Bluetooth Low Energy (BLE)** stack with `NimBLE`
  - **GPS** integration using `TinyGPSPlus`
- Modular **FreeRTOS task architecture** for:
  - Periodic sensor polling
  - Communication queue management
  - Event-driven alerts
- Power-efficient architecture to prolong wearable operation
- Serial debugging with toggled verbosity and task-aware output

### Fixed
- Corrected BLE data clearing issue after multiple Polar H9 reconnections
- Stabilized LTE fallback under weak WiFi conditions

### Improved
- Refined motion detection thresholds for better fall detection accuracy
- Reduced boot time and increased task scheduling stability
- Improved low-battery behavior with proper safe shutdown triggers
