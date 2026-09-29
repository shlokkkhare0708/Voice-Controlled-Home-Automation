Voice Controlled Home Automation using ESP8266 and Sinric Pro

 Overview

This project implements a Voice Controlled Home Automation System using ESP8266 NodeMCU and Sinric Pro. The system allows users to control home appliances through voice commands using Amazon Alexa or Google Assistant from anywhere with an internet connection.

 Features

* Control appliances using voice commands.
* Remote access through the internet.
* Supports multiple devices.
* Real-time device status updates.
* Easy to configure and expand.

 Components Used

* ESP8266 NodeMCU
* Relay Module
* Bulb/Appliance
* Jumper Wires
* Power Supply
* Wi-Fi Network
* Sinric Pro Account

 Working Principle

The ESP8266 connects to a Wi-Fi network and communicates with the Sinric Pro cloud platform. When a user gives a voice command through Alexa or Google Assistant, the command is sent to Sinric Pro, which forwards it to the ESP8266. The ESP8266 then switches the corresponding relay ON or OFF, controlling the connected appliance.

 Circuit Diagram

<img width="920" height="697" alt="image" src="https://github.com/user-attachments/assets/c43caa84-ac20-416c-a77b-b7a55f9227eb" />

 Software Requirements

* Arduino IDE
* ESP8266 Board Package
* Sinric Pro Library
* ArduinoJson Library

Installation

1. Install Arduino IDE.
2. Install ESP8266 board package.
3. Install required libraries.
4. Update Wi-Fi credentials and Sinric Pro keys in the code.
5. Upload the code to ESP8266.
6. Connect the hardware as per the circuit diagram.

Usage

1. Power on the ESP8266.
2. Connect it to Wi-Fi.
3. Open Alexa or Google Assistant.
4. Discover devices.
5. Use commands such as:

   * "Alexa, turn on the light."
   * "Alexa, turn off the fan."

 Applications

* Smart Homes
* Energy Management
* Remote Appliance Control
* IoT-Based Automation Systems

Future Enhancements

* Mobile App Integration
* Energy Monitoring
* Sensor-Based Automation
* Scheduling and Timers


