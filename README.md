# Nlens-Assistive-Vision-System
🧠 Overview

Nlens is an assistive system designed to help visually impaired individuals navigate safely using real-time obstacle detection and intuitive feedback mechanisms.

# ⚙️ Key Features
Ultrasonic-based obstacle detection
Distance-based feedback system
Visual alerts (Red & Green LEDs)
Vibration feedback system
Buzzer alert for danger detection
Real-time monitoring dashboard

# 🚦 Working Principle
The system classifies distance into three zones:

>100 cm (Safe Zone): Green LED ON
50–100 cm (Warning Zone): Red LED + intermittent vibration
<50 cm (Danger Zone): Red LED + continuous vibration + buzzer

The buzzer is only activated in the danger zone to reduce noise and improve usability.

# 🧊 3D Design
The system features a compact wearable structure designed for:

Efficient component placement
User comfort
Portability

(See /design/ folder)

# 🔌 Circuit Design

The ultrasonic sensor is interfaced with the ESP8266, which processes distance and controls the output components.

(See /circuit/ folder)

# 📊 Monitoring Dashboard

Nlens includes a web-based dashboard for:

Real-time sensor data monitoring
System visualization
Debugging and analysis

(See /code/dashboard/ folder)

# 💻 Code
MicroPython code for ESP8266
Web dashboard implementation

(See /code/ folder)

# 🎥 Demo

A demonstration of the system in operation is available:

👉 [https://www.youtube.com/shorts/XXIS4dwjgeo]

# 🚀 Development Roadmap

# Version 1 (Current)
Ultrasonic obstacle detection
LED, vibration, and buzzer feedback
Dashboard monitoring

# Version 2
Camera-based object recognition
Audio feedback via earpiece
Solar-powered rechargeable system

# Version 3
Brain-Computer Interface (BCI) integration

# 👤 Author

Abdul Rahman Olabidemi Hammed (Smartdon)
Mechatronics Engineering, Bayero University Kano
