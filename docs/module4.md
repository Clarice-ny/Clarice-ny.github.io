# MODULE 4
# What I Learned: Introduction to Raspberry Pi Pico and Basic Programming
## 🔌 1. Getting Started with Raspberry Pi Pico
I learned how to connect the Raspberry Pi Pico to my computer using a USB cable. I discovered that the Pico is a compact and powerful microcontroller that can be programmed using both C++ and MicroPython. It comes with an onboard LED connected to GPIO 25, which is perfect for basic experiments.

## 💡 2. The Blink Test
I ran the Blink test, which is a basic program that turns the LED on and off repeatedly. This simple test helped me understand:

How to control digital output pins

How timing works in microcontroller programming using delays

## 🐍 3. Learning MicroPython
I used MicroPython, a lightweight version of Python for microcontrollers. I learned how to:
Install Thonny IDE, a beginner-friendly editor
Flash MicroPython firmware onto the Pico
Write and upload Python scripts directly to the board
Use commands like Pin(), value(), and sleep() to blink the LED

==Example:

python
Copy code
from machine import Pin
from time import sleep

led = Pin(25, Pin.OUT)

while True:
    led.toggle()
    sleep(1)==
## 💻 4. Introduction to C++ for Microcontrollers
I also explored C++ programming using the Arduino IDE. This involved:
Installing the Raspberry Pi Pico board package in Arduino IDE
Writing a C++ sketch to blink the LED

Understanding how digitalWrite() and delay() functions work

==Example:

cpp
Copy code
void setup() {
  pinMode(25, OUTPUT);
}

void loop() {
  digitalWrite(25, HIGH);
  delay(1000);
  digitalWrite(25, LOW);
  delay(1000);
}==                          
## 🔄 5. Comparing MicroPython and C++
MicroPython is easier and quicker to write for simple tasks.
C++ offers more control and is more efficient for complex applications.
Both languages are useful, and choosing one depends on the project and comfort level.

## 📈 Conclusion
Through this hands-on exercise, I gained practical experience in:
Working with microcontrollers (Raspberry Pi Pico)
Using two popular programming languages for embedded systems
Running and modifying the Blink test to understand digital I/O

Setting up and using Thonny Editor and Arduino IDE

This foundational knowledge prepares me for more advanced hardware interaction, sensor integration, and real-world embedded system projects.

## Progress Gallery
![image1](image4.png)
![image2](image5.png)
![image3](image3.png)