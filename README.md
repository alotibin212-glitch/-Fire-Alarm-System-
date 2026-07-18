# 🔥 Fire Alarm System

A responsive and efficient safety alert system designed to detect sudden temperature increases. Developed by Eng. Noura Abbad Al-Qathami at Taif University, this project utilizes an NTC thermistor to trigger an audible alarm.

---

## 🔗 Project Resources
Access the full project repository and documentation files via the link below:
[📁 Project Google Drive Folder](https://drive.google.com/drive/folders/1Wpt5xhDLEoc3dOgX3ZSXi-imsbbXtIww)

---

## 📊 System Architecture
The system relies on a simple yet effective analog trigger mechanism:
* Heat Sensing: An NTC thermistor monitors ambient temperature; as heat rises, its resistance drops significantly.
* Switching Logic: A BC548 transistor acts as an electronic switch that activates when the thermistor detects a heat spike.
* Alert Mechanism: Once triggered, the transistor completes the circuit, activating a 5V buzzer to sound a high-decibel warning.
<img width="617" height="302" alt="لقطة شاشة 2026-07-18 144448" src="https://github.com/user-attachments/assets/4a7a593b-11bd-4a33-9009-ffe513762510" />


---

## 🔌 Circuit Specifications
The prototype was constructed on a breadboard using the following components:
* NTC Thermistor: The primary sensor for detecting temperature variations.
* BC548 Transistor: Functions as the switching core of the system.
* 5V Buzzer: Provides the audible alarm output.
* Power Supply: Operates on a 9V battery, regulated with resistors to ensure stability.

<img width="1179" height="470" alt="رررر" src="https://github.com/user-attachments/assets/69187e08-5896-4836-8e96-4def72c03d30" />


---

## 💻 Operating Principle
* Normal State: The thermistor maintains high resistance, keeping the transistor in the "OFF" state.
* Detection State: Upon detecting a heat spike, the thermistor's resistance decreases, allowing current to flow into the transistor's base, thereby switching the buzzer "ON" instantaneously.

---

## 👤 Developer
* Eng. Noura Abbad Al-Qathami - [https://github.com/alotibin212-glitch](https://github.com/alotibin212-glitch)
* Affiliation: Taif University
