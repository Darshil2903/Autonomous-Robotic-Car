<h1 align="center">Autonomous Multi-Control Robotic Car</h1>

<p align="center"><b>An Arduino-based robot car with five control modes, a hand-made circuit board and 3D-printed parts.</b></p>

<p align="center">
  <img alt="Arduino" src="https://img.shields.io/badge/Arduino-C%2FC%2B%2B-00878F?logo=arduino&logoColor=white" />
  <img alt="Fusion 360" src="https://img.shields.io/badge/Autodesk-Fusion_360-F7931E?logo=autodesk&logoColor=white" />
  <img alt="Tinkercad" src="https://img.shields.io/badge/Tinkercad-circuits-1477D1?logo=autodesk&logoColor=white" />
</p>

<p align="center"><i>Built at Queen Elizabeth Secondary School, Surrey, BC.</i></p>

---

## What it does

One car, five ways to drive it:

| Mode | How it works |
|---|---|
| 🛣️ **Line following** | Colour sensing tracks a line on the floor and steers to stay on it |
| 🚧 **Autonomous mode** | An ultrasonic sensor detects obstacles ahead so the car can drive itself |
| 📱 **Bluetooth control** | Driven from a phone over Bluetooth |
| 📺 **IR remote control** | Driven with an ordinary TV remote through an IR receiver |
| 🎮 **Wired controller** | A custom-built wired controller |

## The build

### Circuit design and a hand-made board
- Circuits designed and simulated in **Tinkercad**
- An **Arduino Uno–compatible control board** made from scratch: I fabricated the circuit on copper-clad fibreglass, then placed and soldered every component instead of using an off-the-shelf Arduino
- Debugging real hardware faults: tracing short circuits and open circuits and reworking solder joints

### Mechanical design
- Sensor mounts, brackets and structural parts designed in **Autodesk Fusion 360** and **3D printed**
- Parts shaped to hold the electronics and position each sensor where it needs to be

### Firmware
- Written in **C/C++** with the **Arduino IDE**
- Reads the colour, ultrasonic, IR and Bluetooth inputs and switches between control modes
- Tuned motor response, sensor thresholds and control accuracy for each mode through testing

## What I learned

This project brought together embedded systems, PCB prototyping, robotics and real-world hardware debugging. Getting it working meant checking the circuit, the soldering and the mechanical parts as often as the code.

---

Built by **Darshil Patel** — [LinkedIn](https://www.linkedin.com/in/darshilkumarpatel1) · [GitHub](https://github.com/Darshil2903)
