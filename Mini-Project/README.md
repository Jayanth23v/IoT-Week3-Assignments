Cloud-Based Weather Monitoring System Using ESP32

Project Overview

This mini project focuses on developing an IoT-based weather monitoring system using an ESP32 microcontroller and a DHT22 temperature and humidity sensor.

The system collects real-time temperature and humidity readings and sends the sensor data to the ThingSpeak cloud platform through Wi-Fi connectivity. The collected data is displayed on a cloud dashboard, allowing users to monitor environmental conditions remotely.

Objectives

- Measure temperature and humidity using the DHT22 sensor.
- Interface the DHT22 sensor with the ESP32.
- Establish Wi-Fi connectivity using ESP32.
- Transmit sensor readings to the ThingSpeak cloud platform.
- Visualize sensor data using cloud-based graphs.
- Enable remote monitoring of environmental conditions.

Hardware Components

- ESP32 Development Board
- DHT22 Temperature and Humidity Sensor

Software and Technologies

- Wokwi Simulator
- Arduino C++
- ThingSpeak Cloud Platform
- Wi-Fi Communication
- HTTP Protocol

Working Principle

1. The DHT22 sensor measures temperature and humidity.
2. The ESP32 reads the sensor values through GPIO 16.
3. The ESP32 connects to Wi-Fi.
4. Sensor readings are transmitted to ThingSpeak using HTTP requests.
5. ThingSpeak stores the readings in the configured cloud channel.
6. Temperature and humidity values are displayed through separate dashboard graphs.
7. Users can monitor the readings remotely through the ThingSpeak dashboard.

ThingSpeak Channel Configuration

- Field 1: Temperature (°C)
- Field 2: Humidity (%)

Project Results

Successfully developed and simulated a cloud-based weather monitoring system using ESP32 and DHT22. Temperature and humidity readings were transmitted to the ThingSpeak cloud platform and visualized through the dashboard for remote monitoring.

Future Enhancements

- Add additional environmental sensors.
- Develop a mobile application for monitoring.
- Implement alerts when temperature or humidity exceeds predefined limits.
- Store and analyze historical sensor readings.

Conclusion

The project demonstrates the integration of IoT sensors, wireless communication and cloud computing for real-time environmental monitoring.

Project Domain: Internet of Things (IoT)
Platform: Skill Nexus – Week 3 Mini Project
