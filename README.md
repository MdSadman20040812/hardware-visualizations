# Hardware Visualizations 🔧

**Interactive schematics & circuit diagrams — analog design for real-world utility conditions.**

![Electronics](https://img.shields.io/badge/Electronics-FF6F00?style=for-the-badge&logo=arduino&logoColor=white)
![Schematics](https://img.shields.io/badge/Schematics-2E7D32?style=for-the-badge&logo=svg&logoColor=white)
![SVG](https://img.shields.io/badge/SVG-FFB13B?style=for-the-badge&logo=svg&logoColor=white)
![BJT](https://img.shields.io/badge/Preference-BJT/diode-blueviolet?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

---

## 🖼️ Featured: Diode-OR Automatic Transfer Switch

```
        Solar (+) ──►|──┬──► Load (+)
        [D1]        │  │
                     │  ├── Zener Clamp ── GND
        Grid (+) ──►|──┤
        [D2]           │
                        └── Darlington Driver ── Load Control
        Battery (+) ─►|─┘
        [D3]

        Highest-voltage source wins automatically
```

**Interactive features:** Inspect nodes, hover for voltage values, trace signal flow.

**[→ View Schematic](diode-or-transfer-schematic.html)**

---

## 🖼️ Featured: Load-Shedding Line Fuse Monitor

```
        Line ──┬── R1 (100K) ──┬── BJT Base
              │                │
              └── Fuse ────────┴── BJT Collector ── LED + Buzzer
              (when intact)         (latching alert)

        Schmitt trigger:  hysteresis prevents chatter
        Latch:  stays triggered until manually reset
        Standby: < 500 µA quiescent draw
```

Designed for **Bangladesh utility conditions** — load-shedding makes fuse monitoring critical.

**[→ View Schematic](LoadShedding_Monitor.html)**

---

## 🎨 Design Principles

| Principle | Why |
|-----------|-----|
| **BJT/diode-first** | Robustness over complexity |
| **Ultra-low standby** | Target < 500 µA quiescent draw |
| **Local problems** | Dhaka/Bangladesh utility conditions |
| **Interactive SVG** | Inspect nodes, values, signal flow in browser |

---

## 🚀 Quick Start

```bash
# Just open in a browser
start diode-or-transfer-schematic.html     # Windows
start LoadShedding_Monitor.html
```

---

## 📁 Project Structure

```
hardware-visualizations/
├── README.md
├── diode-or-transfer-schematic.html    # Diode-OR automatic transfer switch
│   ├── Interactive SVG schematic
│   ├── Hover tooltips for values
│   └── Signal flow animation
├── LoadShedding_Monitor.html           # Fuse monitor with latching alert
│   ├── Discrete-transistor design
│   ├── Schmitt trigger visualization
   └── Interactive node inspection
└── README.md
```

---

## 📄 License

MIT © Md Sadman Bin Masud
