# Hardware Visualizations 🔧 — Schematics & Circuit Diagrams

[![Electronics](https://img.shields.io/badge/Electronics-FF6F00?style=for-the-badge&logo=arduino&logoColor=white)](https://en.wikipedia.org/wiki/Electronics)
[![Schematics](https://img.shields.io/badge/Schematics-2E7D32?style=for-the-badge&logo=svg&logoColor=white)](https://en.wikipedia.org/wiki/Schematic)
[![SVG](https://img.shields.io/badge/SVG-FFB13B?style=for-the-badge&logo=svg&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/SVG)

A collection of **embedded systems visualizations**, including interactive schematics, circuit diagrams, and hardware design documentation. All designs are original and implemented with clean SVG + HTML for maximum clarity.

---

## ✨ Featured Projects

| Project | Description | Domain |
| :--- | :--- | :--- |
| **[Diode-OR Automatic Transfer Switch](https://github.com/MdSadman20040812/hardware-visualizations/blob/main/diode-or-transfer-schematic.html)** | Highest-voltage-wins power path selection using diode OR-ing, Zener clamps, and Darlington driver | `Power Electronics` `Analog Design` |
| **[Load-Shedding Line Fuse Monitor](https://github.com/MdSadman20040812/hardware-visualizations/blob/main/LoadShedding_Monitor.html)** | Discrete-transistor fuse-mounted voltage monitor with Schmitt trigger and latching alert | `Bangladesh` `Utility Electronics` |

---

## 🔌 Design Philosophy

- **No comparators, no MOSFETs** where possible — prefer BJT/diode solutions for robustness
- **Ultra-low standby current** — target < 500 µA quiescent draw
- **Local problem focus** — designs target real Dhaka/Bangladesh utility conditions
- **Interactive SVG schematics** — inspect nodes, values, and signal flow directly in browser

---

## 📂 Repository Structure

```
hardware-visualizations/
├── README.md
├── diode-or-transfer-schematic.html
└── LoadShedding_Monitor.html
```

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

<div align="center">
  <sub>Built with rigor. Deployed with evidence. • 2026</sub>
</div>
