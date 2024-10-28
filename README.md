# ESP32 Wi-Fi Network Scanner and Client Device Display

## Description
This project is a simple web server hosted on an ESP32 microcontroller, designed to display nearby Wi-Fi networks and connected devices. The server operates as an Access Point (AP) that can be connected to via any Wi-Fi-enabled device. Through a user-friendly web interface, users can view:

1. A list of available Wi-Fi networks within range of the ESP32 along with signal strength (RSSI).
2. A list of connected devices to the ESP32 AP, displaying each device's MAC address.

The user interface is designed in a dark theme with neon colors for enhanced visibility and aesthetics.

![ESP32 Wi-Fi Project](https://cdn.discordapp.com/attachments/1296222763530584106/1300572636954365992/image.png?ex=67215428&is=672002a8&hm=9c886f3e1c6ad11490cf11a02ea84a367041e39402f4821460dccb4a9ba973dc&)

## Features
- Displays a list of nearby Wi-Fi networks with their SSIDs and RSSI.
- Lists MAC addresses of devices connected to the ESP32 AP.
- Stylish, responsive design using CSS Grid layout.
- Blinking LED indicator for server activity.

## Hardware Requirements
- **ESP32 Development Board**: Any ESP32-based board should work.
- **LED**: Connected to GPIO pin for indicating server status.
- **Jumper Wires**: For connections if using an external LED.

## Software Requirements
- **PlatformIO**: A popular IDE extension for developing ESP32 projects.
- **Arduino IDE**: Ensure you have the ESP32 board library installed in Arduino.

## Getting Started
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
