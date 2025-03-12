# Smartwatch-Based Health Monitoring System ⌚💙
This project is a smartwatch-based health monitoring system that tracks heart rate, oxygen saturation (SpO2), body temperature, and GPS location. It uses ESP32, IoT, and Machine Learning (Random Forest) to predict heart attack risks and sends real-time alerts via Twilio SMS API.

## Features 🚀
1. Real-time health monitoring (Heart Rate, SpO2, Temperature, GPS)
2. IoT connectivity with Blynk & ThingSpeak for remote monitoring
3. Machine Learning prediction using Random Forest Regression
4. Twilio SMS alerts for abnormal health conditions
5. Low-power optimization for efficient continuous tracking

## Technologies Used 🛠
- Hardware: ESP32, MAX30102 (Heart Rate & SpO2), DS18B20 (Temperature), GPS module
- Software: Python, C++, Embedded Systems, Blynk, ThingSpeak
- Machine Learning: Random Forest Regression for heart attack prediction
- Cloud & APIs: Twilio API for SMS alerts, Blynk & ThingSpeak for IoT

## Project Setup 🔧
#### Hardware Requirements:
- ESP32
- MAX30102 (Heart Rate & SpO2 Sensor)
- DS18B20 (Temperature Sensor)
- GPS Module
- LCD Display
  
### Software Requirements:
- Arduino IDE
- Python
- Blynk & ThingSpeak accounts
- Twilio API setup
  
## Installation Steps:
### Install required libraries in Arduino IDE:
- Blynk
- TinyGPS++
- DFRobot_MAX30102
- DallasTemperature
- Upload the Arduino code to ESP32.
- Set up Blynk & ThingSpeak for data visualization.
- Configure Twilio API for SMS alerts.
- Run the system and monitor health data remotely!
  
## How It Works? 📊
- ESP32 collects health data from sensors (Heart Rate, SpO2, Temperature, GPS).
- Data is sent wirelessly to Blynk & ThingSpeak cloud for remote monitoring.
- The Random Forest model analyzes the data and predicts heart attack risks.
- If an anomaly is detected, an SMS alert is sent using Twilio API.
## Future Improvements ✨
1. Improve the accuracy of the Machine Learning Model
2. Add Bluetooth Connectivity for offline monitoring
3. Enhance the UI of the Blynk Dashboard
