# Accident-Detection-and-Alert-System
Developed a cutting-edge Accident Detection and Alert System using a Nano microcontroller, GPS module, and SIM module to enhance vehicle safety and emergency response. This system provides real-time collision detection and immediate alerts to improve response times and ensure driver and passenger safety

## Overview
This project implements an **Accident Detection and Alert System** using an Arduino Nano microcontroller, a GPS module, and a GSM module. The system detects collisions based on acceleration changes and sends real-time SMS alerts with the vehicle's GPS location to emergency contacts.

## Hardware Required
- Arduino Nano
- GPS Module (e.g., NEO-6M)
- GSM Module (e.g., SIM900)
- Accelerometer (e.g., ADXL345)
- Jumper wires and power supply

## Libraries Required
- TinyGPS++
- Adafruit_ADXL345_U

## Code Explanation
- **setup()**: Initializes communication with the GPS and GSM modules and sets up the accelerometer.
- **loop()**: Continuously reads accelerometer data to detect collisions and sends SMS alerts if an accident is detected.
- **sendAlert()**: Sends an SMS alert with the current GPS coordinates.

## Installation
1. Install the Arduino IDE from [Arduino's website](https://www.arduino.cc/en/software).
2. Install the required libraries using the Library Manager in the Arduino IDE.
3. Connect the hardware components as per the wiring diagram.
4. Upload the code to the Arduino Nano.
