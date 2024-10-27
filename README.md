## IoT Temperature & Humidity Monitoring
This project is an IoT-enabled system designed to monitor room temperature and humidity levels using an ESP32 microcontroller and a DHT22 sensor. It connects to the MQTT broker HiveMQ Cloud to relay sensor data in real-time. The primary functionalities include:

Hardware: ESP32, DHT22 sensor, onboard LED.

Software: MQTT protocol, HiveMQ Cloud as the MQTT broker.

Features:

Measures and reports room temperature and humidity levels.

Sends data via MQTT to HiveMQ, where it can be visualized or analyzed.

LED indicators show Wi-Fi connection status.

Customizable message callback and publishing functions for dynamic data handling.
