# Arduino-Win-Performance-Monitor
Project to print instant performance data of your Windows system to the SSD1306 screen with Arduino

# 📊 Arduino Windows Performance Monitor

A real-time PC hardware monitoring solution that streams Windows system metrics (CPU, RAM, GPU usage & temperatures) to an external Arduino-driven display via Serial communication.

![Arduino](https://img.shields.io/badge/Board-Arduino-00979D?style=flat&logo=arduino&logoColor=white)
![C# / .NET](https://img.shields.io/badge/Desktop_App-C%23%20%2F%20.NET-512BD4?style=flat&logo=dotnet&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)

---

## ✨ Features
- **Real-Time Telemetry:** CPU load, RAM usage, GPU temperature, and fan speeds updated dynamically.
- **Low Overhead:** Lightweight background service for Windows with minimal CPU footprint.
- **Robust Serial Protocol:** Non-blocking serial packet parsing on the microcontroller to prevent display flicker.
- **Auto-Connect:** Automatic COM port detection and reconnection on connection loss.

---

## 🛠️ Hardware & Software Requirements

### Hardware
* **Microcontroller:** Arduino Uno 
* **Display:** 0.96" OLED (SSD1306),
* **USB Cable:** Standard USB Data Cable (A-to-B)

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

You are free to use, modify, distribute, and sublicense this software for personal or commercial projects, as long as the original copyright notice is retained.

