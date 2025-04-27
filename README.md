# ✨ LumiGrid - Sensor Node ✨

---

## 💡 What is this Node?

The Sensor Node is the eyes and ears of your LumiGrid environment! 📊👂 Built on the ESP32, its job is to collect data from various environmental sensors and share that information with other interested nodes in the system.

Developed with passion by **DevSlavDev** 👨‍💻 in collaboration with **Cube & Reclame Fabriek** 🏢.

---

## 🚀 Key Features

* **Environmental Sensing:** Collects data from integrated sensors.
    * **Initial Sensors:** BME680 (Temp, Humidity, Pressure, Gas), BH1750 (Light), Microwave Radar (Motion). 🌡️💧 압 🌱💡🚶
* **Data Pushing:** Actively pushes collected sensor data to other LumiGrid nodes that indicate they need it. ➡️ nodes
    * Uses mDNS to discover nodes and HTTP POST to send data.
* **Wired Mode:** Can also output sensor data directly via UART. 🔌
* **Power Efficient:** Designed with onboard power regulation. 🔋
* **Control Mode:** Primarily operates as an Independent node for data collection and pushing. 🚶
* **REST API & Web UI (Status/Config):** View sensor data and configure the node. 🌐

---

## 🧠 Technology Stack

* **Hardware:** ESP32-WROOM + Sensor Breakouts 🤖
* **Firmware:** ESP-IDF (C++)
* **Communication:** WiFi, HTTP/REST, mDNS, UART.
* **Sensors:** I2C, SPI, or digital/analog sensor interfaces.

---

## 🚧 Work In Progress (WIP)! 🚧

This node is currently under active development planning. 🌱 Implementation will focus on reliable sensor data acquisition, efficient data pushing logic, and integrating the mDNS discovery and HTTP communication.

This node is planned as the first ESP32 node to be developed after the Raspberry Pi phase! 💪

---

## 🤝 Contributions

Currently, contributions are not being actively accepted for this specific node. We are focusing on building the core system structure.

**HOWEVER!** We are building this with future collaboration in mind! 🎉 Once the main code is complete and stable, we plan to open up contributions. Keep an eye on the main LumiGrid repository for updates! 👀

---

## 🔗 Stay Tuned!

Follow the main LumiGrid repository for updates on our progress! 😊

---

Made with ❤️ by DevSlavDev for Cube & Reclame Fabriek
