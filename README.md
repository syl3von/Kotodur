# 🛡️ Kotodur

> Professional WiFi Analyzer, Network Diagnostics & Security Auditor for Android

![Android](https://img.shields.io/badge/Android-10%2B-brightgreen)
![Kotlin](https://img.shields.io/badge/Kotlin-2.x-purple)
![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-Material%203-blue)
![License](https://img.shields.io/badge/License-MIT-success)

---

## 📖 Overview

SYLEVON CYBER NET SEC ANALYZER (Internal Project Name: **Kotodur**) is an advanced Android application designed to provide comprehensive WiFi diagnostics, network analysis, and defensive security auditing in a modern cyberpunk interface.

Unlike traditional WiFi analyzer apps, SYLEVON combines real-time telemetry, network performance testing, LAN discovery, security assessment, and GPS-based signal surveying into a single application.

The project is built entirely with modern Android development technologies and follows the MVVM architecture pattern.

---

# ✨ Features

## 📡 Dashboard

- Real-time WiFi telemetry
- Signal strength (RSSI)
- SSID
- BSSID
- Frequency
- Bandwidth
- WiFi Standard
- Link Speed
- MAC Address
- Gateway
- DNS
- Local IP
- Network Health Score
- Event Log Console

---

## ⚡ Performance Diagnostics

Measure

- Download Speed
- Upload Speed
- Ping
- Jitter
- Packet Loss

Includes live progress indicators and event logging.

---

## 📶 Nearby WiFi Scanner

Discover nearby access points.

Displays

- SSID
- Hidden Networks
- BSSID
- Vendor
- RSSI
- Signal %
- Frequency
- Channel
- Security
- Distance Estimation

Supports

- Search
- Filters
- Sorting

---

## 📈 Real-Time Signal Graph

Visualize signal strength over time.

Features

- Live updates
- Adjustable refresh rate
- Configurable history window

---

## 🌐 Local Network Scanner

Discover LAN devices.

Automatically identifies

- Router
- Laptop
- Phone
- NAS
- Camera
- Printer
- TV

Shows

- IP
- Hostname
- Vendor
- Device Type

Includes an interactive network topology view.

---

## 🔒 Security Auditor

Security analysis includes

- Encryption evaluation
- Security score
- Configuration recommendations
- TCP Port Scanner
- DNS Latency Tester

Supported ports

- 21
- 22
- 23
- 53
- 80
- 139
- 443
- 445
- 8080

---

## 🚶 Walk Test

Background WiFi surveying.

Records

- GPS
- RSSI
- Timestamp
- Distance
- Stability

Features

- Heatmap
- Session History
- CSV Export

---

## ⚙️ Customization

- Cyberpunk Theme
- Terminal Mode
- Matrix Background
- Signal Unit Selection
- Adjustable Polling Rate

---

# 🛠 Technology Stack

- Kotlin
- Jetpack Compose
- Material 3
- Room Database
- Kotlin Coroutines
- StateFlow
- MVVM
- Repository Pattern
- Android Location Services
- Android WiFi APIs

---

# 📂 Architecture

```
Presentation
│
├── Compose UI
├── ViewModels
│
Domain
│
├── Repository
├── Models
│
Data
│
├── Room
├── WiFi Manager
├── Network Scanner
├── GPS
└── Services
```

---

# 📸 Screenshots

| Dashboard | Scanner | Walk Test | Security |
|-----------|----------|-----------|----------|
| *(Add image)* | *(Add image)* | *(Add image)* | *(Add image)* |

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/syl3von/Kotodur.git
```

Open with Android Studio

Build

Run on Android 10+

---

# 📦 Requirements

- Android Studio
- Android SDK 29+
- Kotlin
- Gradle

---

# 📄 Permissions

The application requests

- ACCESS_WIFI_STATE
- CHANGE_WIFI_STATE
- ACCESS_NETWORK_STATE
- INTERNET
- ACCESS_FINE_LOCATION
- ACCESS_COARSE_LOCATION
- NEARBY_WIFI_DEVICES
- FOREGROUND_SERVICE
- POST_NOTIFICATIONS

---

# ⚠️ Disclaimer

This application is intended for:

- Network diagnostics
- Performance monitoring
- Defensive security auditing
- Educational purposes

Only scan devices and networks that you own or have explicit authorization to test.

The application does **not** perform offensive wireless attacks, password recovery, packet injection, deauthentication, or monitor mode operations.

---

# 🗺 Roadmap

Planned future improvements include

- AI Network Advisor
- CVE Database Integration
- Router Fingerprinting
- DNS Leak Detection
- IPv6 Analyzer
- Continuous Monitoring
- Rogue Device Detection
- Traceroute
- PDF Report Generator
- Network Baseline Comparison
- Automation Rules

---

# 🤝 Contributing

Pull requests are welcome.

For major changes, please open an issue first.

---

# 🛡 Security Policy

Please do not disclose vulnerabilities publicly.

Report security issues privately.

---

# 📜 License

MIT License

---

# 👨‍💻 Developed By

**Sylevon**


---

⭐ If you like this project, consider giving it a star.
