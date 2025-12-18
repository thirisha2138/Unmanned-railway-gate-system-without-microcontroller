# Unmanned-railway-gate-system-without-microcontroller
This experiment is to create a unmanned railway gate system without using Arduino Uno. The  “unmanned Railway Gate system ” is basically a smart automatic barrier that allows the traffic to  cross the railway track when there is no train and blocks the traffic when a train passes through  tracks.  
# 🚦 Unmanned Railway Gate System

## 📌 Project Overview

The **Unmanned Railway Gate System** is a hardware-based automation project designed to improve safety at railway crossings by eliminating manual gate operation. The system detects the presence of a train using IR sensors and automatically controls the gate mechanism using a 555 timer IC and a servo motor—**without using a microcontroller**.

This project demonstrates fundamental concepts of **sensor-based automation, timing circuits, and electromechanical control**, making it suitable for safety-critical, low-cost deployments.

---

## 🎯 Objectives

* Prevent accidents at unmanned railway crossings
* Reduce human intervention and operational errors
* Ensure accurate and timely gate opening/closing
* Demonstrate automation using discrete electronics

---

## 🧠 System Architecture

**Input:** IR Sensors (Train Detection)
**Processing:** 555 Timer IC (Monostable Mode)
**Actuation:** SG90 Servo Motor & Relay
**Output:** Automatic Gate Control

The system uses two IR sensors placed on either side of the gate to detect the incoming and outgoing train. The sensor output triggers the 555 timer, which generates a timed pulse to control the servo motor for gate movement.

---

## ⚙️ Components Used

* IR Sensors (Train Detection)
* 555 Timer IC (Monostable Configuration)
* SG90 Servo Motor (Gate Actuation)
* 5V Relay Module
* Resistors, Capacitors, Diodes
* Battery Supply
* Breadboard & Connecting Wires

---

## 🔄 Working Principle

1. **Train Approaches:** IR Sensor-1 detects the train and sends a trigger signal.
2. **Signal Processing:** The 555 timer IC, configured in monostable mode, generates a timed output pulse.
3. **Gate Closure:** The servo motor rotates to close the gate.
4. **Train Passes:** IR Sensor-2 detects the train leaving the crossing.
5. **Gate Opening:** A second trigger activates the servo motor to open the gate.

This logic ensures that the gate remains closed only while the train is present.

---

## 🧪 Results

* Successful automatic opening and closing of the railway gate
* Reliable train detection using IR sensors
* Stable servo operation using timer-based control
  
<img width="975" height="755" alt="image" src="https://github.com/user-attachments/assets/5befdc90-8360-471a-a5b3-5f1d9ea51b39" />
<img width="979" height="767" alt="image" src="https://github.com/user-attachments/assets/5dc79e34-4a80-4784-9661-76d51fb0f552" />
<img width="615" height="462" alt="image" src="https://github.com/user-attachments/assets/80de4015-5134-4586-b4d1-5bb68a944476" />
<img width="581" height="618" alt="image" src="https://github.com/user-attachments/assets/b0429445-17c8-4c67-bac6-e2b2cab0b63a" />



---

## 📄 Documentation

* 📘 **Complete Project Report:** Available in the `report/` folder
* 📐 Circuit diagrams and system explanation included

---

## 🎥 Demonstration Video

▶️ [Click here to watch the working demo](https://drive.google.com/file/d/1VOxtOgYU9ZJvvKUGnkhy2SGDRUL5MrmB/view)

---

