# MODULE 6
## Communication Protocols & Sensor Report

## 🔌 Introduction
Explored communication protocols (Serial, I2C, SPI) and interfaced Ultrasonic & PIR sensors using Arduino and Raspberry Pi Pico.

## 📡 Communication Protocols

| Protocol | Use | Wires | Speed |
|---------|-----|-------|-------|
| Serial  | Debugging, data logs | TX, RX | Medium |
| I2C     | Multi-device, shared bus | SDA, SCL | Moderate |
| SPI     | Fast, precise devices | MISO, MOSI, SCK, SS | Fast |

## 🔊 Ultrasonic Sensor (HC-SR04)
- Measures distance using sound wave reflection.
- Pins: VCC, GND, TRIG, ECHO
- Formula: `Distance = (Echo Time × Speed of Sound) / 2`

## 👀 PIR Sensor
- Detects motion via infrared (body heat).
- Pins: VCC, GND, OUT
- Output HIGH on motion, LOW otherwise.

## 🤖 Raspberry Pi Pico + PIR
- Used MicroPython with `Pin()` and `value()`.
- PIR worked directly (3.3V logic).
- Implemented motion-based LED control.

## ✅ Key Takeaways
- Learned Serial, I2C, SPI basics.
- Interfaced motion & distance sensors.
- Coded in Arduino IDE and Thonny.
- Understood sensor theory and GPIO usage.
