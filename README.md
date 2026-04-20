![Status](https://img.shields.io/badge/Status-Completed-success)
![Field](https://img.shields.io/badge/Field-Digital%20Logic-blue)
![Level](https://img.shields.io/badge/Level-Hardware-orange)
# 🎮 Catch The LED – Digital Logic Game

A two-player competitive game implemented using **Digital Logic Design** without using any microcontrollers.

---

## 🚀 Project Overview

**Catch The LED** is a reflex-based hardware game where players compete to press a button at the exact moment a target LED lights up.

The system is designed using **Finite State Machines (FSM)**, flip-flops, and combinational logic circuits, demonstrating real-world applications of digital electronics.

---

## 🧠 Game Concept

* LEDs move in a **back-and-forth sequence**
* Target LED is **LED 5 (Green)**
* Each player must press their button at the correct timing
* Correct press = +1 score
* First player to reach **3 points wins**

---

## ⚙️ System Architecture

The project is divided into the following modules:

* ⏱ **Clock Generator**
  555 Timer configured in Astable Mode to generate system clock

* 🔁 **LED Sequence Controller (FSM)**
  Controls LED movement using D Flip-Flops

* 🔄 **Direction Control Logic**
  Reverses direction at endpoints (LED 0 & LED 7)

* 🎯 **Player Input Detection**
  Detects valid button press when target LED is active

* 🧮 **Score Counter System**
  Tracks player scores using T Flip-Flops

* 🏆 **Winner Detection Circuit**
  Determines and displays the winner

---

## 🔌 Technologies & Components

* 555 Timer IC
* D Flip-Flops
* T Flip-Flops
* Logic Gates (AND, OR, NOT, XOR)
* 3-to-8 Decoder
* LEDs & Push Buttons
* Resistors & Capacitors

---

## 📊 Key Features

* Fully synchronous digital system
* FSM-based design
* Accurate timing using hardware clock
* Debounced input handling
* Modular and scalable architecture

---

## 🧪 Testing & Results

* Stable LED sequence (forward & reverse)
* Accurate detection of player input
* Reliable score tracking up to 3
* Proper system reset functionality

---

## 🚧 Challenges & Solutions

| Challenge       | Solution                             |
| --------------- | ------------------------------------ |
| Button bouncing | RC Debounce circuit                  |
| Timing mismatch | Clock synchronization                |
| FSM complexity  | Verified using state tables & K-maps |
| Power stability | Decoupling capacitors                |

---

## 🔮 Future Improvements

* Add sound effects 🎵
* Adjustable difficulty (variable clock speed)
* 7-segment display for scores
* Additional game modes
* Microcontroller version (optional upgrade)

---

## 📁 Repository Structure

```
Catch-The-LED/
│
├── README.md
├── docs/
│   └── Report.pdf
├── circuit/
│   ├── circuit.pdf
├── simulation/
│   └── (Proteus)
├── video/
│   └── Run The Project
```

---

## 👨‍💻 Authors

* Omar Ayman Mohamed Saed
(Zagazig University – Faculty of Engineering - Communication and Electronics Department)

---

## ⭐ Contribution

Feel free to fork, improve, or build upon this project.
