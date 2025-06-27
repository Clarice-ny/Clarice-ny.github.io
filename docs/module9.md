## MODULE 9
# 📷 ESP32-CAM Programming Report

## 🎯 Objective
To set up and program the ESP32-CAM module using the Arduino IDE and test its camera functionality.

---

## 🧰 Components
- ESP32-CAM module (AI-Thinker)  
- FTDI USB-to-Serial adapter (3.3V)  
- Jumper wires  
- Arduino IDE  

---

## 🔌 Wiring for Programming

| ESP32-CAM | FTDI Adapter |
|-----------|--------------|
| GND       | GND          |
| 5V        | VCC (5V)     |
| U0R       | TX           |
| U0T       | RX           |
| GPIO 0    | GND (for flashing) |

> Note: GPIO 0 must be connected to GND during upload and disconnected afterward to run.

---

## ⚙️ Arduino IDE Setup
- Board: "AI Thinker ESP32-CAM"  
- Upload Speed: 115200  
- Library: `ESP32` board package installed via Boards Manager  
- Example Sketch: `Camera > CameraWebServer`  

---

## 🔍 Test & Results
- Serial monitor showed IP address on successful boot  
- Live video stream was accessible via browser on same network  
- Module responded to commands (capture, flash, resolution change)

---

## 🧠 Key Learnings
- How to connect and program ESP32-CAM via FTDI  
- Understanding GPIO 0 boot mode  
- Successfully accessed and streamed live camera feed over Wi-Fi  
- Ready for applications like surveillance, object detection, or IoT vision

