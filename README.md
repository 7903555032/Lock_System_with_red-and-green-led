# Lock_System_with_red-and-green-led

# 🔐 Smart Lock System with Keypad & Blynk Integration

This project is a smart door lock system using an ESP8266 microcontroller that combines **physical keypad access** with **remote control via Blynk IoT platform**. It allows secure access through a 4-digit password and gives users the ability to unlock the door remotely, monitor the lock status, and control indicator LEDs from their smartphone.

---

## 🚀 Features

- 🔢 **4x3 Keypad Access** – Enter a 4-digit password to unlock the door
- 📱 **Blynk IoT Integration** – Control and monitor the system from anywhere
- 🔓 **Remote Door Unlock** – One-tap unlock via smartphone (opens for 5 seconds)
- 🚨 **Wrong Password Indicator** – Red LED flashes on incorrect password
- ✅ **Correct Password Indicator** – Green LED lights up on correct password
- 💡 **LED Controls** – Turn red and green LEDs on/off manually via app switches
- 📡 **Wi-Fi Controlled via Hotspot** – Easily connect using your phone hotspot

---

## 🧰 Hardware Used

- ESP8266 NodeMCU
- 4x3 Matrix Keypad
- SG90 Servo Motor
- Red and Green LEDs
- Jumper Wires
- Breadboard (optional)

---

## 🔌 Pin Configuration

| Component     | ESP8266 Pin |
|---------------|-------------|
| Servo Motor   | D8          |
| Green LED     | D0          |
| Red LED       | D3          |
| Keypad Rows   | D5, D6, D7, D4 |
| Keypad Cols   | D1, D2, D9   |

---

## 🛠️ Installation & Setup

1. **Clone the Repo:**
   ```bash

