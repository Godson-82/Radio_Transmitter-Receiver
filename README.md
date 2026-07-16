# 📡 Arduino Nano Long-Range Radio Transmitter & Receiver

A low-cost, long-range **6-channel wireless transmitter and receiver** built using **Arduino Nano** and **nRF24L01+ PA+LNA** modules. This project was developed as an affordable alternative to expensive RC radio systems while delivering reliable long-range communication.

> 🚀 **Tested Range:** Up to **1 Kilometer** (under suitable conditions)  
> 💰 **Total Project Cost:** Under **₹700**  
> 🔓 **Platform:** Open Source  
> 🛠️ **Microcontroller:** Arduino Nano  

---

# 📖 Overview

This project consists of a custom-built transmitter and receiver that communicate wirelessly using the **nRF24L01+ PA+LNA** RF modules. The system supports **6 independent control channels**, making it suitable for robotics, RC vehicles, drones, automation systems, and various wireless control applications.

The primary goal of this project was to design a reliable, long-range radio communication system using affordable and easily available components without compromising performance.

---

# ✨ Features

- 📡 Long-range wireless communication
- 🎮 6 independent control channels
- 🚀 Tested communication range of up to **1 km**
- 💰 Complete hardware cost under **₹700**
- 🔋 Portable and battery-powered
- 🔧 Compact and beginner-friendly design
- 📚 Open-source Arduino code
- ⚡ Easily customizable and expandable

---

# 🛠 Components Used

- Arduino Nano (Transmitter)
- Arduino Nano (Receiver)
- 2 × nRF24L01+ PA+LNA Modules
- 2 × NRF Adapter Boards
- Dual-axis Joystick Modules
- Potentiometer
- Toggle Switch
- Capacitor (100–470 µF)
- Li-Po Battery
- Connecting Wires
- Prototype PCB / Breadboard

---

# 📂 Repository Structure

```
Arduino-Nano-Radio-Transmitter-Receiver/

├── Source Code/
│   ├── Transmitter/
│   └── Receiver/
│
├── Images/
│   ├── transmitter.jpg
│   └── receiver.jpg
│
└── README.md
```

---

# ⚙️ How It Works

1. The joysticks, switches, and potentiometers generate control signals.
2. Arduino Nano reads all channel values.
3. Data is transmitted wirelessly using the nRF24L01+ PA+LNA module.
4. The receiver Arduino Nano receives and decodes the transmitted data.
5. Each output channel can be connected to servos, motor drivers, ESCs, relays, or any compatible device.

---

# 📷 Physical Project

## 📡 Transmitter

> Add an image of the completed transmitter here.

```
Images/transmitter.jpg
```

---

## 📡 Receiver

> Add an image of the completed receiver here.

```
Images/receiver.jpg
```

---

# 🚀 Real-Life Applications

This project can be used in a wide variety of real-world applications, including:

- 🚗 RC Cars
- 🚤 RC Boats
- 🚁 DIY Drones
- 🤖 Robotic Vehicles
- 🏭 Industrial Wireless Control
- 🏡 Home Automation
- 🌾 Agricultural Robots
- 💧 Smart Irrigation Systems
- 📡 Remote Monitoring Systems
- 🎓 Educational Projects
- 🌐 IoT Prototypes

---

# ⚠️ Challenges Faced During Development

Developing this project involved overcoming several technical challenges:

- Achieving stable communication over long distances.
- Power instability of the nRF24L01+ PA+LNA module.
- Eliminating signal loss caused by voltage fluctuations.
- Selecting suitable capacitors for stable power delivery.
- Optimizing RF settings for maximum range and reliability.
- Ensuring consistent communication between the transmitter and receiver.
- Reducing electrical noise from battery-powered hardware.
- Managing six independent control channels efficiently.
- Testing communication performance in different environments.

These challenges significantly improved the stability and reliability of the final system.

---

# 📊 Project Specifications

| Feature | Details |
|----------|---------|
| Microcontroller | Arduino Nano |
| RF Module | nRF24L01+ PA+LNA |
| Channels | 6 |
| Tested Range | Up to 1 Kilometer |
| Total Cost | Under ₹700 |
| Programming Language | Arduino (C/C++) |
| Platform | Arduino IDE |

---

# 🔮 Future Improvements

- OLED Display
- Battery Voltage Monitoring
- Failsafe Mode
- Telemetry Support
- More than 6 Channels
- Custom PCB Design
- Rechargeable Battery Management
- Improved Antenna System
- Better Enclosure Design

---

# 🤝 Contributions

Contributions, suggestions, and improvements are welcome.

1. Fork the repository.
2. Create a new branch.
3. Commit your changes.
4. Submit a Pull Request.

---

# 📜 License

This project is licensed under the **MIT License**.

---

# ⭐ Support

If you found this project useful, please consider giving this repository a ⭐ on GitHub. It motivates further development and helps others discover the project.

## 👨‍💻 Connect with Me

- 💼 **LinkedIn:** https://www.linkedin.com/in/utsab-chowdhury/
- 🐙 **GitHub:** https://github.com/Godson-82
