![Description](images/Full%20Assembly.png)

# 🎮 Raspberry Pi Pico Arcade Stick PCB  

This repository contains the design files for a custom **Raspberry Pi Pico breakout PCB**, specifically designed for arcade sticks. The board simplifies wiring and connections by breaking out the Pico’s GPIO pins while using standardized elements like **screw terminals** and a **20-pin connector**, making it easy to integrate into arcade controller builds.  

## 📌 General Info  
🔹 **Based on [GP2040-CE](https://github.com/OpenStickCommunity/GP2040-CE)**  
🔹 **Common Brook form factor**  
🔹 **Breaks out all Pins for the most common uses:**  
   - 🎮 **Punch Buttons** 1-4  
   - 🎮 **Kick Buttons** 1-4  
   - 🎮 **Directional Inputs** (Up, Down, Left, Right)  
   - 🎮 **Start & Select**  
   - 🎮 **Buttons for modern console support:** Home, Touchpad, L3, R3  
   - 🎮 **Switchable Input Modes:** D-Pad, Left-Stick, Right-Stick  
   - 🌈 **Support for Addressable RGB LEDs**  
   - 🔌 **USB-Passthrough Authentication Support** – [FAQ: Console Compatibility](https://gp2040-ce.info/faq/faq-console-compatibility/)  
   - 📟 **Pins for OLED Display**  

🔹 **Compatible for both Leverless and Traditional Arcade Stick builds**  

## Assembly  
The PCB can be fully hand soldered, but soldering the SMD components might be easier by using a hotplate.

## Components  
- **Raspberry Pi Pico (Version 1)**  
- **3x6x2.5MM Momentary Tact SMD** (Amount: 1)  
- **USB Type B Jack Port** (Amount: 1) *(This can be omitted. The USB-Connector of the Pico can be used directly instead)*  
- **USB Type A Port** *(Used for USB-Passthrough dongles)*  
- **22Ohm resistors, package type 0603** (Amount: 2)  
- **4.7K Ohm resistors, package type 1206** (Amount: 2)  
- **MF-PSMF050X-2 SMD Fuse, package type 0805** (Amount: 1) – [More](https://www.mouser.de/ProductDetail/Bourns/MF-PSMF050X-2?qs=89sKJMJLNwxOThYF3e0Dgg%3D%3D)  
- **KF350 3.5mm pitch 3Pin screwterminal** (Amount: 7)  
- **KF350 3.5mm pitch 2Pin screwterminal** (Amount: 1)  
- **JST PH 2.0mm 2pin straight male header** (Amount: 3)  
- **JST PH 2.0mm 3pin straight male header** (Amount: 1)  
- **JST PH 2.0mm 4pin straight male header** (Amount: 3)  
- **JST XH 2.54mm 3pin straight male header** (Amount: 1)  
- **2x10 2.54mm pitch straight male header** (Amount: 1)  
- **1x5 2.54mm pitch straight male header** (Amount: 2)
