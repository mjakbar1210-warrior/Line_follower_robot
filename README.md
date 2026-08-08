# 🤖 Line Follower Robot

A Line Follower Robot is an autonomous robotic vehicle that detects and follows a predefined path using IR sensors.

The robot continuously reads the IR sensor values and controls the motors according to the detected line position.

## 🚀 Features

- Autonomous line following
- IR sensor-based line detection
- Real-time motor control
- Simple and low-cost hardware
- Arduino-based control system
- Can follow straight and curved paths

## 🛠️ Hardware Components

- Arduino UNO
- IR Sensor Module
- L298N Motor Driver
- DC Gear Motors
- Robot Chassis
- Wheels
- Battery
- Jumper Wires
- Breadboard / PCB

## 💻 Software & Technologies

- Arduino IDE
- Embedded C/C++
- Arduino UNO
- IR Sensors
- L298N Motor Driver

## ⚙️ Working Principle

The IR sensors detect the difference between the black line and the surrounding surface.

The Arduino reads the sensor output and determines the direction of the line.

Based on the sensor readings, the Arduino controls the motor driver:

| Sensor Condition        | Robot Movement |
|                         |                |
| Line detected in center | Move Forward   |
| Line detected on left   | Turn Left      |
| Line detected on right  | Turn Right     |
| No line detected        | Stop / Search  |
