# Contactless-Digital-Thermometer
Build a contactless thermometer using an infrared temperature sensor (MLX90614) and display the readings on an LCD. It's a great blend of healthcare tech and embedded systems — especially relevant post-COVID.

# 🌡️ Contactless Digital Thermometer using Arduino

This project uses an MLX90614 IR sensor and Arduino to create a non-contact thermometer. The temperature is shown on an I2C LCD screen.

## 🔧 Components Required
- Arduino Uno
- MLX90614 IR Temperature Sensor
- I2C 16x2 LCD Display
- Jumper Wires
- Breadboard

## 🔌 Circuit Diagram

## 💻 Code
The Arduino reads temperature via I2C from the MLX90614 sensor and displays it on the LCD.

## 🧠 Working Logic
- MLX90614 measures object temperature
- Arduino fetches data via I2C
- LCD shows temperature in °C

## 🚀 Extensions
- Add buzzer alert for high fever
- Show ambient temp too
- Integrate with IoT (upload to ThingSpeak)
