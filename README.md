# 🤖 Robotic Crane Project | Creative Programming & IoT
*A Mini Robotic Arm Demonstration using Arduino & Block-Based Programming*

**so here is the code that i do you can also download pictoblox and code file to try yourself**
<img width="553" height="765" alt="image" src="https://github.com/user-attachments/assets/b6da4b4a-07bb-40fe-a1e3-2181f4cb3f94" />

---

## 🎯 Project Overview

This project was developed as part of my **Creative Digital Design & Logic (CDDL)** course in the 2nd semester of BE Computer Engineering. It's a hands-on exploration of **block-based programming**, **IoT devices**, and **creative engineering** - combining Arduino hardware with intuitive visual programming to create a functional robotic crane.

> **Course Philosophy**: Non-credit, pure learning experience focused on building practical, creative solutions using modern programming paradigms and IoT technologies.

---

## ✨ Features

🎮 **Joystick Control** - Intuitive 2D movement control
🦾 **Dual Servo Motion** - Smooth 90° up/down and left/right movement  
🎯 **Task Performance** - Designed for precise positioning and simple tasks
🧩 **Block-Based Logic** - Visual programming using PictoBlox
⚡ **Portable Power** - 5V battery operation
🔧 **Modular Design** - Easy to modify and extend

---

## 🛠️ Hardware Components

| Component | Quantity | Purpose |
|-----------|----------|---------|
| **Arduino Uno** | 1x | Main microcontroller |
| **Servo Motors** | 2x | Arm movement (vertical & horizontal) |
| **Mini Joystick Module** | 1x | User input control |
| **5V Battery** | 1x | Portable power supply |

---

## 🎬 Project Demo

[Watch Demo](https://www.playbook.com/s/computer-systems-engineeing/HMoaREBPy6L1mzWnEouCkgfx)
*Click above to see the robotic crane in action!*

---

## 🔌 Circuit Diagram

The circuit design enables seamless communication between the joystick input and servo motor outputs through the Arduino Uno:

![Circuit Diagram](https://github.com/user-attachments/assets/9d241cef-2564-4369-966c-ab92e2bd72d7)

```
    [5V Battery] ──→ [Arduino Uno] ──→ [Servo Motors (2x)]
                           │
                           └──→ [Mini Joystick Module]
```

*Detailed circuit diagram included in project files*

---

## 💻 Programming Approach

### Block-Based Logic with PictoBlox
- **Visual Programming**: Drag-and-drop interface for logic creation
- **Real-time Control**: Immediate response to joystick inputs
- **Servo Coordination**: Synchronized movement patterns
- **Processing Integration**: Animation and visualization capabilities

### Key Programming Concepts Used:
- Sensor input processing
- Motor control algorithms  
- Coordinate mapping (joystick → servo angles)
- Real-time feedback loops

---

## 🚀 How It Works

1. **Input Detection**: Joystick module captures 2D movement commands
2. **Signal Processing**: Arduino processes analog inputs from joystick
3. **Angle Calculation**: Converts joystick position to servo angles (0-90°)
4. **Motor Control**: Servo motors execute precise movements
5. **Task Execution**: Robotic arm performs positioning and simple manipulation tasks

---

## 🎓 Learning Outcomes

This project enhanced understanding of:
- **IoT Device Integration** - Connecting sensors and actuators
- **Visual Programming** - Block-based logic development
- **Hardware-Software Interface** - Arduino programming
- **Control Systems** - Input-output mapping and feedback
- **Creative Engineering** - Problem-solving through hands-on building

---

## 🔧 Setup & Installation

### Requirements
- PictoBlox Software
- Arduino IDE (for advanced modifications)
- USB cable for Arduino programming
- Basic electronics tools

### Quick Start
1. **Connect Hardware** following the circuit diagram
2. **Load PictoBlox Project** - Import the block-based program
3. **Upload to Arduino** - Flash the generated code
4. **Power On** - Connect 5V battery
5. **Control** - Use joystick to operate the crane

---

## 🌟 Project Highlights

> "*This project embodies the spirit of creative engineering - transforming theoretical concepts into tangible, interactive solutions that bridge the gap between digital logic and physical reality.*"

- **Hands-on Learning**: Direct application of programming concepts
- **Creative Problem Solving**: Innovative use of available components  
- **Practical Engineering**: Real-world implementation challenges
- **Fun Factor**: Engaging, interactive learning experience

---

## 🎯 Future Enhancements

- [ ] **Additional Degrees of Freedom** - More servo motors for complex movements
- [ ] **Sensor Integration** - Distance sensors for autonomous operation
- [ ] **Wireless Control** - ESP32/ESP8266 for remote operation
- [ ] **Computer Vision** - Object detection and tracking
- [ ] **Mobile App Interface** - Smartphone control integration

---

## 📚 Course Context: CDDL

**Creative Digital Design & Logic** represents a modern approach to engineering education:
- **Non-Credit Course**: Focus on learning over grades
- **Creative Programming**: Emphasis on innovative solutions
- **Processing Animations**: Visual programming and design
- **IoT Integration**: Modern hardware platforms
- **Hands-on Making**: Physical implementation of digital concepts

---

## 🤝 Connect & Collaborate

This project represents the intersection of creativity, technology, and practical engineering. Feel free to:
- Fork and extend the project
- Share your own implementations
- Suggest improvements and new features
- Connect for collaboration opportunities

---

## 📄 License

This project is part of academic coursework and is shared for educational purposes. Feel free to use, modify, and learn from it!

---

<div align="center">

**Built with ❤️ during 2nd Semester BE Computer Engineering**

*Combining creativity, technology, and hands-on learning*

[![GitHub](https://img.shields.io/badge/Follow-GitHub-181717?style=social&logo=github)](https://github.com/abm1119)
[![LinkedIn](https://img.shields.io/badge/Connect-LinkedIn-0077B5?style=social&logo=linkedin)](https://www.linkedin.com/in/abdul-basit-memon-614961166/)

</div>
