# 🌡️ lumigrid-node-sensor: Sense Your Environment! 🌡️

Welcome to the lumigrid-node-sensor repository! 🚀 This is where the code lives for the ESP32-powered Sensor Node, designed to collect environmental data from various sensors. Get ready to monitor your surroundings! 🧐

This node is part of the LumiGrid ecosystem, brought to you by Cube & Reclame Fabriek, with development led by DevSlavDev.

## 📂 What's Inside?

This repository contains the code and resources for the Sensor Node:

* `app/`:  Source code for the ESP32 firmware (C++ with ESP-IDF). This handles sensor communication, data processing, and network transmission. 💻
* `web/`:  Node-specific web UI components for viewing sensor data and configuring the node. 💅
* `config/`:  Default configuration files for the Sensor Node. ⚙️
* `scripts/`:  Scripts for building and deploying the firmware to the ESP32. 🛠️
* `README.md`:  That's me! 👋 Your guide to this repository.

## 🛠️ Project Structure

Here's the repository structure:

lumigrid-node-sensor/
├── app/        💻 (ESP32 Firmware)
├── web/        💅 (Web UI)
├── config/     ⚙️ (Configuration)
├── scripts/    🛠️ (Build/Deploy Scripts)
└── README.md   📖 (You are here!)


## 🔗 Related Repositories

* [LumiGrid (Main Repository)](https://github.com/DevSlavDev/LumiGrid):  Contains shared resources and documentation. 🧠

## ✨ Features

* Collects data from various sensors (BME680, BH1750, Microwave Radar Motion). [cite: 33]
* Pushes sensor data to subscribed nodes via HTTP POST or UART. [cite: 33]
* Uses mDNS for node discovery. [cite: 33]
* Provides a web interface and REST API for status and configuration. [cite: 34]

## 🚀 Getting Started

1.  **Clone this repository:**

    ```bash
    git clone [https://github.com/DevSlavDev/lumigrid-node-sensor.git](https://github.com/DevSlavDev/lumigrid-node-sensor.git)
    cd lumigrid-node-sensor
    ```

2.  **Set up your ESP32 development environment:** You'll need the ESP-IDF framework.

3.  **Explore the code in the `app/` directory.**

4.  **Build and flash the firmware to your ESP32.**

5.  **Connect your sensors to the ESP32.**

6.  **Use the web UI to view sensor data and configure the node!**

## 🤝 Contributing

Contributions are welcome! If you have support for more sensors, improvements to data handling, the web interface, or any other part of the project, please submit a pull request. 💪

## 🐛 Issues

Please report any bugs or issues in this repository.

## 📜 License

\[License information will go here]

## Let's gather some data! 🧐
