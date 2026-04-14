# IoT Food Freshness Monitoring System

This project is an ESP32-based system that monitors fruit freshness using sensors like temperature, humidity, CO2, and ethylene gas.

## Features
- Real-time monitoring using Firebase
- ML-based prediction for spoilage detection
- Automated cooling using Peltier module
- Dashboard for tracking environmental data

## Tech Stack
- ESP32
- Firebase
- Python (Flask API)
- Sensors (DHT11, MQ135, MH-Z19B)

## Outcome
- Successfully extended banana shelf life by 2–3 days

## Status
Work in progress / Prototype stage

## Architecture
- ESP32 collects sensor data (temperature, humidity, CO2, ethylene)
- Data sent to Firebase in real-time
- Flask API processes data and predicts spoilage
- Dashboard displays insights to user
- Peltier module controls temperature automatically

## Key Learnings
- Built an end-to-end IoT system (hardware + cloud + backend)
- Worked with real-time data streaming using Firebase
- Implemented ML-based prediction for practical use-case
- Integrated automation with sensor-based decision making

## Future Improvements
- Improve prediction accuracy with more data
- Add mobile app for better accessibility
- Optimize power consumption of ESP32
