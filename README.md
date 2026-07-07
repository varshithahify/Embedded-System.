⚡ Arduino-Based Storm Safety Switch Box for Home Appliance Protection

An intelligent embedded system that automatically protects household appliances from storm-related electrical damage by detecting rain and thunder conditions and disconnecting power before dangerous surges occur.

🌟 Overview

Electrical storms, lightning strikes, and sudden voltage fluctuations can cause severe damage to household appliances. This project introduces a smart Arduino-powered protection system that continuously monitors environmental conditions using rain and sound sensors.
When storm conditions are detected, the system instantly disconnects connected appliances through a relay module, minimizing the risk of electrical damage and improving household safety.

🚀 Key Features

✅ Automatic Storm Detection

✅ Rain Sensor-Based Monitoring

✅ Thunder Detection Using Sound Sensor

✅ Fast Relay-Based Power Cutoff

✅ LED Status Indication

✅ Low-Cost Embedded Solution

✅ Automatic Recovery After Storm Conditions

✅ Compact and Easy-to-Install Design

🎯 Problem Statement

Traditional surge protectors and manual switching methods often fail to provide proactive protection during electrical storms.

This project aims to:

Detect storm conditions before electrical damage occurs

Automatically disconnect appliances

Reduce repair and replacement costs

Improve electrical safety in homes and small businesses

🏗️ System Architecture
             
                                   +----------------+
                                   |  Power Supply  |
                                   +--------+-------+
                                            |
                                            v
                                   +----------------+
                                   |  Arduino UNO   |
                                   +--------+-------+
                                            |
                             +--------------+--------------+
                             |                             |                         
                      +--------------+             +--------------+
                      | Rain Sensor  |             | Sound Sensor |
                      +--------------+             +--------------+
                             |                             |
                             +-------------+---------------+
                                           |
                                           v
                                    +---------------+
                                    | Relay Module  |
                                    +-------+-------+
                                            |
                                            v
                                 +---------------------+
                                 | Home Appliances     |
                                 | (Protected Load)    |
                                 +---------------------+



🛠 Hardware Components

| Component           | Quantity    |
| ------------------- | ----------- |
| Arduino UNO         | 1           |
| Rain Sensor Module  | 1           |
| Sound Sensor Module | 1           |
| SPDT Relay Module   | 1           |
| LEDs                | 2-3         |
| Breadboard          | 1           |
| Jumper Wires        | As Required |
| 9V Battery          | 1           |

💻 Software Requirements

Arduino IDE

Arduino UNO Board Package

C/C++ Programming

⚙️ Working Principle

Normal Condition:

  Rain sensor detects no rainfall
  
  Sound sensor detects no thunder
  
  Relay remains ON
  
  Appliances receive power normally
  
  Storm Condition
  
When:

  Rain is detected OR
  
  Thunder is detected
  
The Arduino:

  Processes sensor data
  
  Activates protection mode
  
  Turns OFF relay
  
  Disconnects appliances
  
  Turns ON protection indicator LED
  
After conditions become safe, power is restored automatically.

📈 Performance

| Parameter                | Value       |
| ------------------------ | ----------- |
| Storm Detection Accuracy | 95%+        |
| Response Time            | < 500 ms    |
| Reconnection Delay       | 5–8 seconds |
| Power Consumption        | 50–80 mA    |
| Project Cost             | < ₹1500     |
Based on prototype testing and validation results.

🔌 Circuit Connections

    Rain Sensor
      VCC  -> 5V
      GND  -> GND
      A0   -> Arduino A0
    Sound Sensor
      VCC  -> 5V
      GND  -> GND
      A0   -> Arduino A1
    Relay Module
      VCC -> 5V
      GND -> GND
      IN  -> D7

📷 Project Demonstration

    System States
    
    🟢 Normal Mode
        Appliances Connected
        Green LED ON
    🔴 Protection Mode
        Storm Detected
        Appliances Disconnected
        Red LED ON
  
🎯 Applications

    Smart Homes
    Residential Buildings
    Rural Areas
    Small Businesses
    Agricultural Equipment Protection
    Remote Monitoring Stations
    IoT Home Automation Systems

🔮 Future Enhancements

    Wi-Fi Integration (ESP8266/ESP32)
    Mobile App Notifications
    GSM Alert System
    Lightning Detection Sensor
    Voltage Surge Monitoring
    Cloud Data Logging
    Smart Home Integration
    AI-Based Storm Prediction

👨‍💻 Team Members

| Name                   | USN        |
| ---------------------- | ---------- |
| Samarth Nagappa Tuppad | 1DB23EC132 |
| Shreya R               | 1DB23EC147 |
| Srujana M V            | 1DB23EC158 |
| V N Varshitha          | 1DB23EC172 |

🎓 Academic Information

  Department: Electronics & Communication Engineering
  
  Institution: Don Bosco Institute of Technology, Bengaluru
  
  University: Visvesvaraya Technological University (VTU), Belagavi
  
  Academic Year: 2025–2026

📜 License

  This project is developed for academic and educational purposes.

