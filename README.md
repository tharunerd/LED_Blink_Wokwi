﻿# LED_Blink_Wokwi
# LED Blinking on STM32 (Wokwi Simulation)

This project demonstrates a simple LED blinking program on STM32F103C8T6 (Blue Pill) using Wokwi Simulator.

## 🔹 Simulation Link  
🔗 [Run in Wokwi](https://wokwi.com/projects/426569942532515841)

## 🔹 How to Run?
- Click the **Wokwi link** above.
- Click **Start Simulation** to see the LED blink.

## 🔹 Code
```cpp
void setup() { pinMode(13, OUTPUT); }
void loop() { digitalWrite(13, HIGH); delay(500); digitalWrite(13, LOW); delay(500); }
