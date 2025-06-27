# MODULE 7
# 🖥️ ESP32 + OLED (SSD1306) Quick Report

## 🔧 Components
- ESP32 Dev Module  
- 0.96" OLED (I2C, SSD1306)  
- Jumper wires

## 🔌 Wiring

| OLED | ESP32 |
|------|-------|
| VCC  | 3.3V  |
| GND  | GND   |
| SDA  | GPIO 21 |
| SCL  | GPIO 22 |

## ⚙️ Arduino Setup
- Install: **Adafruit SSD1306** & **Adafruit GFX** libraries  
- Board: ESP32 Dev Module  
- Port: COMx (check in Tools)

## 🧪 Sample Code

```cpp
#include <Adafruit_SSD1306.h>
Adafruit_SSD1306 display(128, 64, &Wire, -1);

void setup() {
  display.begin(SSD1306_SWITCHCAPVCC, 0x3C);
  display.clearDisplay();
  display.setCursor(0, 10);
  display.print("Hello ESP32!");
  display.display();
}

void loop() {}
