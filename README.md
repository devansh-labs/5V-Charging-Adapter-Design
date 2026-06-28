
<h1 align="center">🔌 5V Charging Adapter using Proteus</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Simulation-Proteus-blue" />
  <img src="https://img.shields.io/badge/Input-230V%20AC-orange" />
  <img src="https://img.shields.io/badge/Output-5V%20DC-brightgreen" />
  <img src="https://img.shields.io/badge/License-MIT-green" />
  <img src="https://img.shields.io/badge/Project-Active-success" />
</p>

---

<h3 align="center">Design and simulation of a regulated 5V AC-to-DC power supply using Proteus Design Suite.</h3>

---

<h2>🎯 Objective</h2>

<p>
This project demonstrates the design and simulation of a <b>regulated 5V DC charging adapter</b> by converting <b>230V AC mains</b> into a stable <b>5V DC output</b>.
</p>

<ul>
  <li>AC to DC conversion using a <b>step-down transformer and bridge rectifier</b></li>
  <li>Voltage regulation using the <b>7805 Voltage Regulator IC</b></li>
</ul>

---

<h2>📸 Project Preview</h2>

<h3>🔌 Complete Circuit</h3>
<img src="assets/Project Preview/circuit-diagram.png" width="700"/>

<h3>⚡ Simulation Output</h3>
<img src="assets/Project Preview/simulation-output.png" width="700"/>

<h3>📐 PCB / Circuit Layout</h3>
<img src="assets/Project Preview/pcb-layout.png" width="700"/>

---

<h2>✨ Features</h2>

<ul>
  <li>⚡ 230V AC to regulated 5V DC conversion</li>
  <li>🔄 Full-wave bridge rectifier</li>
  <li>🔋 Ripple filtering using capacitors</li>
  <li>📏 Stable 5V output using 7805 regulator</li>
  <li>💡 LED power indicator</li>
  <li>🖥️ Complete Proteus simulation</li>
  <li>📚 Beginner-friendly circuit design</li>
  <li>🧩 Easily extendable for PCB development</li>
</ul>

---

<h2>🧠 System Architecture</h2>

<h3>🔄 Power Flow</h3>

<pre>
230V AC
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
7805 Voltage Regulator
    │
    ▼
5V DC Output
</pre>

<h3>💡 Why 7805 Regulator?</h3>

<ul>
  <li>Provides stable regulated 5V output</li>
  <li>Simple and reliable linear regulator</li>
  <li>Ideal for educational projects</li>
</ul>

---

<h2>🖼️ Circuit Architecture</h2>

<h3>⚡ AC to DC Power Supply Block Diagram</h3>
<img src="assets/Architecture Diagram/power-supply-block-diagram.png" width="700"/>

---

<h2>🔌 Hardware Components</h2>

<table border="1" cellpadding="8">
<tr><th>Component</th><th>Quantity</th></tr>
<tr><td>Step-Down Transformer</td><td>1</td></tr>
<tr><td>Bridge Rectifier / 4 Diodes</td><td>1</td></tr>
<tr><td>7805 Voltage Regulator</td><td>1</td></tr>
<tr><td>Electrolytic Capacitors</td><td>2</td></tr>
<tr><td>Ceramic Capacitors</td><td>2</td></tr>
<tr><td>LED Indicator</td><td>1</td></tr>
<tr><td>Current Limiting Resistor</td><td>1</td></tr>
<tr><td>Output Connector</td><td>1</td></tr>
<tr><td>AC Voltage Source</td><td>1</td></tr>
</table>

---

<h2>💻 Software Tools</h2>

<ul>
  <li>Proteus Design Suite</li>
  <li>Proteus ISIS</li>
  <li>Proteus ARES (Optional)</li>
</ul>

---

<h2>🛠️ Installation</h2>

<h3>🔧 Setup</h3>

<ol>
  <li>Install Proteus Design Suite.</li>
  <li>Open the project file.</li>
  <li>Run the simulation.</li>
  <li>Observe the regulated 5V DC output.</li>
</ol>

---

<h2>🏗️ Setup Steps</h2>

<ol>
  <li>Open Proteus Design Suite.</li>
  <li>Create a new project.</li>
  <li>Add an AC Voltage Source (230V AC).</li>
  <li>Place a Step-Down Transformer.</li>
  <li>Configure the transformer output voltage.</li>
  <li>Add four diodes to form a bridge rectifier (or use a Bridge Rectifier component).</li>
  <li>Connect the transformer secondary to the bridge rectifier.</li>
  <li>Add a large electrolytic capacitor for ripple filtering.</li>
  <li>Place a 7805 Voltage Regulator IC.</li>
  <li>Connect the rectifier output to the regulator input.</li>
  <li>Add input and output bypass capacitors.</li>
  <li>Connect an LED with a current limiting resistor.</li>
  <li>Connect the LED to the regulated output.</li>
  <li>Add a DC Voltmeter.</li>
  <li>Add an Oscilloscope (optional).</li>
  <li>Verify all wiring connections.</li>
  <li>Run the simulation.</li>
  <li>Measure the regulated 5V output.</li>
  <li>Observe the ripple before and after filtering.</li>
  <li>Test the circuit under different loads.</li>
</ol>

---

<h2>🎮 Usage</h2>

<ul>
  <li>⚡ Study AC to DC conversion</li>
  <li>🔋 Learn voltage regulation</li>
  <li>🖥️ Perform Proteus simulation</li>
</ul>

---

<h2>⚡ Working Principle</h2>

<ul>
  <li>230V AC enters the transformer</li>
  <li>Transformer steps down the voltage</li>
  <li>Bridge rectifier converts AC into pulsating DC</li>
  <li>Capacitors reduce ripple voltage</li>
  <li>7805 regulates the output to a stable 5V DC</li>
  <li>LED indicates regulated power availability</li>
</ul>

---

<h2>🛠 Troubleshooting</h2>

<table border="1" cellpadding="8">
<tr><th>Problem</th><th>Solution</th></tr>
<tr><td>No Output</td><td>Verify transformer wiring</td></tr>
<tr><td>Low Voltage</td><td>Check bridge rectifier polarity</td></tr>
<tr><td>High Ripple</td><td>Increase filter capacitor value</td></tr>
<tr><td>Regulator Heating</td><td>Use a heat sink</td></tr>
<tr><td>Simulation Error</td><td>Verify all circuit connections</td></tr>
</table>

---

<h2>🔮 Future Improvements</h2>

<ul>
  <li>PCB Design</li>
  <li>Hardware Prototype</li>
  <li>SMPS-Based Power Supply</li>
  <li>USB Type-C Output</li>
  <li>Short Circuit Protection</li>
  <li>Over Current Protection</li>
  <li>Reverse Polarity Protection</li>
  <li>Thermal Shutdown</li>
  <li>Fast Charging Support</li>
  <li>Higher Efficiency Design</li>
</ul>

---

<h2>⚠️ Safety</h2>

<ul>
  <li>Check voltage before powering the circuit</li>
  <li>Avoid short circuits</li>
  <li>Work carefully with 230V AC mains</li>
</ul>

---

<h2>📊 Learning Outcomes</h2>

<ul>
  <li>AC to DC Power Conversion</li>
  <li>Transformer Operation</li>
  <li>Bridge Rectifiers</li>
  <li>Ripple Filtering</li>
  <li>Voltage Regulation</li>
  <li>Linear Power Supplies</li>
  <li>Proteus Simulation</li>
  <li>Basic Power Electronics</li>
</ul>

---

<h2>🏁 Conclusion</h2>

<p>
This project demonstrates the complete design and simulation of a <b>regulated 5V AC-to-DC charging adapter</b> using <b>Proteus Design Suite</b>. It provides a solid foundation for understanding power supply design, voltage regulation, and electronic circuit simulation.
</p>

---

<h2>⭐ Support</h2>

<p>If you like this project, give it a ⭐ on GitHub.</p>
```
