## Module 3
## Introduction to ESP32 and Electrical Circuits and Components
 Introduction to ESP32 & Electrical Basics – Quick & Fun Guide!
🧠 What’s the ESP32?
A powerful Wi-Fi & Bluetooth microcontroller – like a mini computer you can program!

Great for IoT, sensors, smart devices, and DIY tech magic. 💡

🔌 Basic Electrical Components
🔋 Capacitor – Stores energy like a mini battery. Charges and discharges.

🔁 Inductor – Resists changes in current. Think of it like inertia for electricity.

💡 Diode – One-way street for current. Only allows flow in one direction.

✨ LED (Light Emitting Diode) – A diode that glows. Used in arrays for TV/laptop screens.

⚙️ Relay – A switch controlled by electricity. Used to control high power with low power.

💎 Crystal Oscillator – Keeps time in circuits (like a clock).

🔥 Fuse – Safety device. Melts (blows) to stop overcurrent and protect circuits.

🔩 Copper & PCB Design

Copper: Main conductor.

Design tip: Check copper thickness & width based on current flow.

🧲 Circuit Behavior Basics
SC (Short Circuit) = 🔥 0 resistance (bad news!).

OC (Open Circuit) = ❌ Infinite resistance (no current flow).

Circuit Geometry: Layout matters – shapes, traces, spacing affect performance.

📐 Important Laws & Concepts
🔁 Superposition – For multiple sources: analyze one at a time, then add effects.

📏 Kirchhoff's Laws:

Current Law (KCL) – What goes in = what comes out.

Voltage Law (KVL) – Sum of voltages in a loop = 0.

🌟 Semiconductors: The Heroes of Modern Tech
Intrinsic – Pure semiconductors (e.g., pure silicon).

Extrinsic – Doped with stuff to change behavior (like N-type or P-type).

📊 PWM – Pulse Width Modulation
Used to mimic analog output (e.g., dimming LEDs).

Cycle: One full on+off wave.

Duty Cycle: % of time the signal is ON (e.g., 50% = half brightness).

🎛️ Potentiometers
Variable resistors. Used to control voltage manually (like volume knobs).

Great for analog inputs.

🍓 Raspberry Pi Pico
Another microcontroller like ESP32, but simpler.

Can also use PWM, read analog values, control LEDs, etc.

Configure using MicroPython or C/C++.

🧪 Analog Write & Duty Cycle (ESP32/Pico)
analogWrite(pin, value) sends PWM signal.

Value = changes brightness or speed (based on duty cycle).