# 🚗 Gesture Controlled Car using ESP32 & MPU6050

## 📌 Project Overview

This project is a wireless Gesture Controlled Car built using an ESP32 microcontroller, MPU6050 accelerometer and gyroscope sensor, L298N motor driver, and BO motors.

The car is controlled by hand movements. A transmitter unit mounted on a glove reads hand gestures using the MPU6050 sensor and sends commands wirelessly via ESP32 Bluetooth/Wi-Fi communication. The receiver ESP32 mounted on the car processes these commands and controls the motors accordingly.

This project demonstrates the application of IoT, embedded systems, wireless communication, and motion sensing technology.

---

## 🎯 Features

* Hand Gesture Based Control
* Wireless Communication using ESP32
* Forward Movement
* Backward Movement
* Left Turn
* Right Turn
* Stop Function
* Real-Time Response
* Low Cost and Easy to Build

---

## 🛠 Components Used

| Component               | Quantity    |
| ----------------------- | ----------- |
| ESP32 Development Board | 2           |
| MPU6050 Sensor          | 1           |
| L298N Motor Driver      | 1           |
| BO Motors               | 4           |
| Wheels                  | 4           |
| Chassis                 | 1           |
| Battery Pack            | 1           |
| Jumper Wires            | As Required |

---

## ⚙️ Working Principle

### Transmitter Side

1. MPU6050 detects hand tilt and motion.
2. ESP32 reads accelerometer values.
3. Hand gestures are converted into movement commands.
4. Commands are transmitted wirelessly.

### Receiver Side

1. ESP32 receives commands.
2. Commands are interpreted.
3. L298N motor driver controls BO motors.
4. Car moves according to hand gestures.

---

## 🎮 Gesture Controls

| Hand Gesture     | Car Action    |
| ---------------- | ------------- |
| Tilt Forward     | Move Forward  |
| Tilt Backward    | Move Backward |
| Tilt Left        | Turn Left     |
| Tilt Right       | Turn Right    |
| Neutral Position | Stop          |

---

## 🔌 Circuit Connections

### MPU6050 to ESP32

| MPU6050 | ESP32  |
| ------- | ------ |
| VCC     | 3.3V   |
| GND     | GND    |
| SDA     | GPIO21 |
| SCL     | GPIO22 |

### L298N to ESP32

| L298N | ESP32  |
| ----- | ------ |
| IN1   | GPIO25 |
| IN2   | GPIO26 |
| IN3   | GPIO27 |
| IN4   | GPIO14 |

---

## 💻 Software Used

* Arduino IDE
* ESP32 Board Package
* MPU6050 Library
* Wire Library

---

## 🚀 Installation

1. Install Arduino IDE.
2. Install ESP32 Board Package.
3. Install MPU6050 Library.
4. Connect ESP32.
5. Upload transmitter code.
6. Upload receiver code.
7. Power the car.
8. Test hand gestures.

---

## 📊 Applications

* Robotics
* Military Surveillance
* Smart Vehicle Control
* Assistive Technology
* Industrial Automation
* IoT-Based Systems

---

## 🔮 Future Enhancements

* Obstacle Avoidance
* Camera Integration
* Mobile App Control
* Voice Commands
* GPS Navigation
* AI-Based Gesture Recognition

---

## 📷 Project Images

Uploading soon...

---

## 🎥 Demo Video

Uploading soon...

---

## 👨‍💻 Author

**Ankur Rastogi**

Engineering Student | IoT & Computer Science

GitHub: https://github.com/ankurr034

---

## ⭐ If you found this project useful, please give it a star on GitHub!
