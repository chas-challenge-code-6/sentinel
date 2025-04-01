### API

# Project Sentinel – API Documentation

## Overview
This API allows communication between IoT sensor devices (e.g., ESP32) and the backend system. It enables real-time data collection, alert handling, and data access for frontend applications.

---

## Base URL
```
https://yourdomain.com/api
```

---

## Endpoints

### 1. Submit Sensor Data
**POST** `/data`

Receives a JSON payload from an ESP32 sensor unit.

#### Request Body
```json
{
  "device_id": "ESP32-001",
  "timestamp": "2025-04-01T12:34:56Z",
  "sensors": {
    "gas": {"co2": 400, "co": 15},
    "temperature": 22.5,
    "humidity": 45,
    "acceleration": {"x": 0.2, "y": -0.1, "z": 9.8},
    "heart_rate": 75,
    "noise_level": 80,
    "battery": 85
  }
}
```

#### Response
```json
{
  "status": "success",
  "message": "Data saved successfully"
}
```

---

### 2. Get Latest Sensor Data
**GET** `/data/latest`

Returns the latest sensor data from each device.

#### Response
```json
[
  {
    "device_id": "ESP32-001",
    "timestamp": "2025-04-01T12:34:56Z",
    "temperature": 22.5,
    "humidity": 45,
    "co2": 400,
    "co": 15,
    "heart_rate": 75,
    "noise_level": 80
  }
]
```

---

### 3. Get Device History
**GET** `/data/:device_id`

Query parameters:
- `from`: ISO timestamp (optional)
- `to`: ISO timestamp (optional)

Example:
```
/data/ESP32-001?from=2025-04-01T00:00:00Z&to=2025-04-01T23:59:59Z
```

#### Response
```json
[
  {
    "timestamp": "2025-04-01T12:34:56Z",
    "temperature": 22.5,
    "humidity": 45,
    "co2": 400,
    "co": 15,
    "heart_rate": 75,
    "noise_level": 80
  },
  ...
]
```

---

### 4. Get Alerts
**GET** `/alerts`

Returns a list of recent critical alerts (e.g. gas spike, fall detected).

#### Response
```json
[
  {
    "device_id": "ESP32-001",
    "type": "gas",
    "value": 1000,
    "message": "High CO2 level detected",
    "timestamp": "2025-04-01T13:45:22Z"
  }
]
```

---

## Status Codes
- `200 OK`: Request was successful
- `400 Bad Request`: Missing or malformed data
- `500 Internal Server Error`: Server-side failure

---

## Future Improvements
- JWT-based authentication
- WebSocket or MQTT support for real-time updates
- Role-based access for users/admins

---

## Contact
For questions, contact the backend team via Discord or GitHub issues.

---

_Last updated: 2025-04-01_

