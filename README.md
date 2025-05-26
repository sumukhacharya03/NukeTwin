# NukeTwin

A Real-Time interactive 3D Digital Twin simulation of an advanced Nuclear Reactor using Three.js

---

<img width="959" alt="image" src="https://github.com/user-attachments/assets/1f540c67-03de-4a61-9bf7-ca13d835b36e" />


## Overview

NukeTwin is a browser-based simulation that visualizes the operational behavior of a nuclear reactor. It includes real-time stats, safety systems, control panels, and emergency shutdown features. Built entirely using WebGL via Three.js, it’s a perfect demonstration of visual engineering and digital twin technology.

---

## Technologies Used

- **Three.js** – 3D rendering engine
- **HTML5 / CSS3** – User interface styling and layout
- **JavaScript (ES6)** – Core simulation and interaction logic
- **dat.GUI / TWEEN.js** – Interface and smooth transitions (used optionally)

---

## How It Works

- The 3D reactor environment is rendered with detailed components like core, turbine, control rods, and safety systems.
- Sliders and buttons simulate control rod insertion, coolant flow, emergency scram, and diagnostics.
- Real-time values such as core temperature, pressure, power output, and neutron flux are dynamically updated.
- Alerts and reactor state display conditions like critical warnings and operational status.
- User interactions influence physical variables in the simulation (like inserting rods to reduce power output).

---

## Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Edge)
- No installations or server needed (runs fully client-side)

### Installation
Clone the repository or download the files:
```bash
git clone https://github.com/yourusername/NukeTwin.git
cd NukeTwin
```

Run the Project:
```bash
open index.html
# or just double-click the file

```
