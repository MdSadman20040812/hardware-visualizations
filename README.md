# Hardware Visualizations 🔧

**Interactive schematics & circuit diagrams — analog design for real-world utility conditions.**

![Electronics](https://img.shields.io/badge/Electronics-FF6F00?style=for-the-badge&logo=arduino&logoColor=white)
![Schematics](https://img.shields.io/badge/Schematics-2E7D32?style=for-the-badge&logo=svg&logoColor=white)
![SVG](https://img.shields.io/badge/SVG-FFB13B?style=for-the-badge&logo=svg&logoColor=white)
![BJT](https://img.shields.io/badge/preference-BJT/diode-blueviolet?style=for-the-badge)

---

## Featured

### Diode-OR Automatic Transfer Switch

Highest-voltage-wins power path selection using diode OR-ing, Zener clamps, and Darlington driver. No comparators, no MOSFETs — just robust analog design.

**[→ View Schematic](diode-or-transfer-schematic.html)**

### Load-Shedding Line Fuse Monitor

Discrete-transistor fuse-mounted voltage monitor with Schmitt trigger and latching alert. Designed for Bangladesh utility conditions.

**[→ View Schematic](LoadShedding_Monitor.html)**

---

## Design Principles

| Principle | Why |
|-----------|-----|
| **BJT/diode-first** | Robustness over complexity |
| **Ultra-low standby** | Target < 500 µA quiescent draw |
| **Local problems** | Dhaka/Bangladesh utility conditions |
| **Interactive SVG** | Inspect nodes, values, signal flow in browser |

---

## Structure

```
hardware-visualizations/
├── README.md
├── diode-or-transfer-schematic.html
└── LoadShedding_Monitor.html
```

---

## License

MIT © Md Sadman Bin Masud
