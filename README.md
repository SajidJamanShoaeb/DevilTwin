DevilTwin – ESP8266 WiFi Security Deauther/Jammer Project








DevilTwin is an ESP8266-based educational WiFi security awareness project.
It is designed to help students, hobbyists, and cybersecurity learners understand how wireless networks work and why proper WiFi security is important.

The project demonstrates WiFi network scanning and signal monitoring through a simple web interface running on the ESP8266.

⚠️ Disclaimer

This project is for educational and cybersecurity awareness purposes only.
Only test on networks you own or have permission to analyze.

Project Features

ESP8266 based wireless research platform

Simple web dashboard interface

Nearby WiFi network scanning

Shows SSID, BSSID, and signal strength

Useful for cybersecurity education

Hardware Requirements

ESP8266 board (NodeMCU / Wemos D1 Mini)

Micro USB cable

Computer (Windows / Linux / macOS)

Software Requirements

Arduino IDE

ESP8266 Board Package

USB driver for ESP8266

Setting Up the ESP8266 Environment
1 Install Arduino IDE

Download and install Arduino IDE.

2 Add ESP8266 Board Manager

Open Arduino IDE and go to:

File → Preferences

Add the following URL:

http://arduino.esp8266.com/stable/package_esp8266com_index.json
3 Install ESP8266 Board

Go to:

Tools → Board → Boards Manager

Search for ESP8266 and install it.

4 Select Board
Tools → Board → NodeMCU 1.0 (ESP-12E Module)
Web Interface

After running the project, a local web dashboard allows you to view nearby wireless networks and signal information.

Example information displayed:

Network Name (SSID)

MAC Address (BSSID)

Signal Strength (dBm)

Screenshots

Add your interface screenshots here.

Example:

![Untitled-1devile](https://github.com/user-attachments/assets/55efcccf-b858-4b90-9762-31edca24276d)

How to Secure Your WiFi Network

Learning about wireless vulnerabilities helps improve security.

Use WPA2 or WPA3 Encryption

Always enable strong encryption on your router.

Use a Strong Password

Example:

MyWiFi_Secure#2026
Disable WPS

WPS can be vulnerable and should be turned off.

Update Router Firmware

Keep your router software updated.

Monitor Connected Devices

Regularly check devices connected to your network.

Educational Purpose

This project helps demonstrate:

Wireless networking basics

IoT device networking

WiFi signal analysis

Cybersecurity awareness

Author

Created by Shoaeb

License

This project is intended for educational use only.
