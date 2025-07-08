# ⚡ AC-to-DC Converter PCB Project

## 📖 Project Overview

This project demonstrates the design and development of an **AC-to-DC converter circuit** using **KiCad**, a free and open-source EDA tool. The converter takes standard 230 V AC mains input and outputs a regulated DC voltage suitable for powering low-voltage electronic devices.

The goal of this project is to provide a real-world example of the **complete PCB design process** — from schematic creation and component selection to layout, simulation, and generating fabrication-ready Gerber files. The design prioritizes safety and reliability, incorporating components such as:

- **A bridge rectifier** for AC to DC conversion
- **Filter capacitors** to reduce ripple
- **A voltage regulator** (e.g., LM7812) for stable output
- **Protective components** like a fuse, varistor, and bleeder resistor

This project is ideal for electronics beginners and intermediate hobbyists looking to strengthen their understanding of power supply design, PCB layout best practices, and real-world implementation using professional tools.

## 🖼️ PCB Layout Screenshot

![PCB Layout]()

![PCB Schematic]()

## 🔧 Features

- **Input:** 230 V AC mains
- **Output:** Regulated 12 V DC
- **Components:** Bridge rectifier, filter capacitors, voltage regulator (LM7812 or equivalent)
- **Safety:** Fuse, varistor, bleeder resistor
- **Design Tools:** KiCad, LTspice (optional simulation), Gerber viewer


## 🧰 Tools Used

- **PCB Design:** KiCad

-**Simulation:** LTspice (optional), Proteus

-**Testing/Prototyping:** Multimeter, Oscilloscope

-**Programming Language** (if microcontroller involved): C/C++

## 🧪 Testing & Assembly

#### Solder components in order of size: resistors → IC sockets → capacitors → connectors

#### Use a current-limited bench supply for first-time power-up

#### Measure the output voltage using a multimeter or oscilloscope

## 📸 Results
-**Output Voltage:** 12 V DC

#### Ripple: < 100 mV peak-to-peak under moderate load

-**Board Dimensions:** (insert actual dimensions)

## ✏️ Customization Ideas
#### Change output voltage by using LM7805 or LM7815

#### Add screw terminals or DC jacks for convenience

#### Add LED indicator for output voltage presence

#### Optional: Replace with a buck converter module
