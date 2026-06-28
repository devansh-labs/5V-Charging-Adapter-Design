````markdown
# 🔌 5V Charging Adapter using Proteus

<p align="center">

<img src="https://img.shields.io/badge/Software-Proteus-blue?style=for-the-badge">
<img src="https://img.shields.io/badge/Output-5V%20DC-success?style=for-the-badge">
<img src="https://img.shields.io/badge/Input-230V%20AC-orange?style=for-the-badge">
<img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge">

</p>

<p align="center">
<b>Design and simulation of a regulated 5V AC-to-DC power supply using Proteus Design Suite.</b>
</p>

---

# 📖 Overview

This project demonstrates the design and simulation of a **regulated 5V DC charging adapter** by converting **230V AC mains** into a stable **5V DC output**.

The simulation is developed in **Proteus Design Suite** and introduces the fundamental stages of a linear power supply, including:

- ⚡ AC to DC Power Conversion
- 🔄 Full-Wave Bridge Rectification
- 🔋 Capacitor Filtering
- 📏 5V Voltage Regulation using 7805
- 🖥️ Complete Circuit Simulation

This project is ideal for **Electronics Engineering students**, beginners, and anyone learning power electronics.

---

# 🚀 Project Highlights

- ⚡ Converts 230V AC to regulated 5V DC
- 🔄 Full-Wave Bridge Rectifier
- 🔋 Ripple Filtering using Capacitors
- 📏 Stable Output using 7805 Voltage Regulator
- 💡 LED Power Indicator
- 🖥️ Complete Proteus Simulation
- 📚 Beginner-Friendly Design
- 🧩 Easy to Understand Circuit
- 🛠 Ready for PCB Development

---

# 📸 Project Preview

## 🔌 Complete Circuit

<p align="center">
<img src="Screenshots/Complete-Circuit.png" width="900">
</p>

---

## ⚙️ Simulation Output

<p align="center">
<img src="Screenshots/Simulation.png" width="900">
</p>

---

## 📐 Circuit Layout

<p align="center">
<img src="Screenshots/Layout.png" width="900">
</p>

---

# 🏗 Circuit Architecture

```text
      230V AC Input
             │
             ▼
   Step-Down Transformer
             │
             ▼
     Bridge Rectifier
             │
             ▼
     Filter Capacitor
             │
             ▼
      7805 Regulator
             │
             ▼
      5V DC Output
```

---

# ⚙️ Working Principle

### Step 1 — AC Input

The circuit receives **230V AC (50Hz)** from the mains supply.

### Step 2 — Step-Down Transformer

The transformer safely reduces the mains voltage to a lower AC voltage suitable for rectification.

### Step 3 — Bridge Rectifier

A full-wave bridge rectifier converts the AC signal into pulsating DC.

### Step 4 — Filtering

Electrolytic capacitors smooth the rectified voltage by reducing ripple.

### Step 5 — Voltage Regulation

The **7805 Voltage Regulator IC** produces a constant **5V DC** output.

### Step 6 — LED Indicator

The LED lights up, indicating that regulated power is available.

---

# 🔧 Components Used

| Component | Quantity |
|-----------|---------:|
| Step-Down Transformer | 1 |
| Bridge Rectifier / 4 Diodes | 1 |
| 7805 Voltage Regulator | 1 |
| Electrolytic Capacitors | 2 |
| Ceramic Capacitors | 2 |
| LED Indicator | 1 |
| Current Limiting Resistor | 1 |
| Output Connector | 1 |
| AC Voltage Source | 1 |

---

# 📥 Input Specifications

| Parameter | Value |
|-----------|-------|
| Input Voltage | 230V AC |
| Frequency | 50Hz |

---

# 📤 Output Specifications

| Parameter | Value |
|-----------|-------|
| Output Voltage | 5V DC |
| Voltage Regulation | Linear (7805) |

---

# 💻 Software Used

| Software | Purpose |
|----------|---------|
| Proteus Design Suite | Circuit Design & Simulation |

---

# 📂 Repository Structure

```text
5V-Charging-Adapter/
│
├── Proteus_Project/
│   └── 5V-Charging-Adapter.pdsprj
│
├── Circuit_Diagram/
│   └── Circuit.png
│
├── Screenshots/
│   ├── Complete-Circuit.png
│   ├── Simulation.png
│   └── Layout.png
│
├── Documentation/
│   └── Report.pdf
│
├── README.md
└── LICENSE
```

---

# ▶️ Getting Started

## Requirements

- Proteus Design Suite

## Installation

1. Clone this repository.

```bash
git clone https://github.com/devansh-labs/5V-Charging-Adapter.git
```

2. Open the **Proteus_Project** folder.

3. Open the **.pdsprj** file.

4. Run the simulation.

5. Measure the regulated **5V DC** output.

---

# 📚 Applications

- Electronics Laboratory Experiments
- Diploma Engineering Projects
- Power Electronics Learning
- AC to DC Conversion Study
- Bridge Rectifier Demonstration
- Voltage Regulator Experiment
- Educational Simulation

---

# 🛠 Troubleshooting

| Problem | Possible Cause | Solution |
|----------|---------------|----------|
| No Output Voltage | Transformer wiring | Verify transformer connections |
| Low Output Voltage | Rectifier issue | Check diode orientation |
| High Ripple | Small filter capacitor | Increase capacitor value |
| Regulator Heating | Excessive load | Use heat sink or reduce load |
| Simulation Error | Wiring mistake | Verify all connections |

---

# ⚠️ Safety Notice

> **This project is intended for educational and simulation purposes only.**

Working directly with **230V AC mains voltage is dangerous**.

Never build or test this circuit without proper electrical knowledge and safety precautions.

Always verify all connections before applying power.

---

# 🔮 Future Improvements

- PCB Design
- Hardware Prototype
- SMPS-Based 5V Charger
- USB Type-C Output
- Short-Circuit Protection
- Over-Current Protection
- Reverse Polarity Protection
- Thermal Shutdown
- Fast Charging Support
- Higher Efficiency Design

---

# 🎓 Learning Outcomes

After completing this project, you will understand:

- AC to DC Power Conversion
- Step-Down Transformer
- Bridge Rectifier
- Capacitor Filtering
- Voltage Regulation
- Linear Power Supply
- Proteus Simulation
- Basic Power Electronics

---

# 📝 License

This project is licensed under the **MIT License**.

See the **LICENSE** file for more information.

---

# 👨‍💻 Author

**Devansh Upadhyay**

🎓 Diploma in Electronics Engineering

🏫 Government Polytechnic Unnao

💻 GitHub: https://github.com/devansh-labs

---

# ⭐ Support

If you found this project helpful, consider giving it a **⭐ Star** on GitHub.

Your support motivates the development of more open-source electronics and embedded systems projects.

---

<p align="center">

Made with ❤️ by <b>Devansh Upadhyay</b>

</p>
````
