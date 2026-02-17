#  Automated Greenhouse Monitoring and Control System

##  Overview
This project is an IoT-based automated greenhouse system designed to optimize environmental conditions and resource usage. The system automatically monitors temperature, humidity, soil moisture, and light levels to improve plant growth efficiency.

##  Features
- Automated irrigation using Soil Moisture Sensor
- Temperature monitoring using DHT11 sensor
- Automatic activation of heater and cooling fans
- Smart lighting system using LDR sensor
- Real-time monitoring and control using Blynk IoT platform
- Embedded control logic developed using C++ (Arduino) on ESP32

##  Hardware Components
- ESP32
- DHT11 Temperature & Humidity Sensor
- Soil Moisture Sensor
- LDR Sensor
- Relay Module
- Cooling and Heater Fans

##  Technologies Used
- Arduino IDE
- C++ (Arduino)
- Internet of Things (IoT)
- Blynk IoT Platform
- Embedded Systems

##  System Working
The system continuously reads environmental data from sensors. Based on predefined conditions:
- Water pump activates when soil moisture is low
- Cooling fan activates when temperature increases
- Heater fan activates when temperature drops
- Lighting system activates during low-light conditions

##  Future Improvements
- Mobile application integration

##  Author
Buddhima Sandaru
