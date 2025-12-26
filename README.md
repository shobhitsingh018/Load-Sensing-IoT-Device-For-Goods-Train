# Load-Sensing IoT Device for Goods Trains 🚂

An automated weight distribution and overloading detection system for freight rail logistics. 

## 🏗️ System Architecture
- **Sensing:** High-precision strain gauges/load cells connected via HX711 amplifiers.
- **Processing:** ESP32/Arduino microcontroller calculating axial load and center of gravity.
- **Connectivity:** Real-time data transmission via MQTT/WiFi for centralized logistics monitoring.

## 📊 Key Features
- **Overload Alerts:** Instant triggers when weight exceeds safety thresholds.
- **Axial Balance:** Monitors left/right and front/back distribution to prevent derailment risks.
- **Low Power:** Optimized deep-sleep cycles for battery-powered industrial deployment.

## 🛠️ Components
- ESP32 Development Board
- HX711 Load Cell Amplifier
- 4x 50kg Load Cells (S-type)
- OLED Display for local telemetry
