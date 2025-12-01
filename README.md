# IoT Sensor Monitoring System

A full IoT pipeline using ESP32 + MQTT + Python backend + Grafana dashboard.

## Hardware
- ESP32
- DHT22 sensor
- USB cable
- WiFi network

## Software Stack
- MQTT (Mosquitto)
- Python subscriber
- Grafana (dashboard)
- InfluxDB or SQLite (storage)

## Steps to Run

### 1. Install Mosquitto
### 2. Run backend subscriber
### 3. Flash ESP32 firmware
Use Arduino IDE → Upload `esp32_sensor.ino`

### 4. Create dashboard
Import data into Grafana and create graphs for temperature + humidity.

## Extensions
- Add alerts (email/SMS)
- Add multiple sensors
- Add cloud dashboard