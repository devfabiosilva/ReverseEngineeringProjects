# Reverse Engineering – LG 42PQ30R (Plasma TV)

This project documents the complete reverse engineering process of the LG 42PQ30R plasma TV, with a special focus on the Z-SUS and Y-SUS boards. It includes circuit analysis, measurements, and common fault diagnostics.

---

## 📷 Photos and Schematics

- [ ] General photos of the Y-SUS board  
- [ ] General photos of the Z-SUS board  
- [ ] Close-ups of critical components (IGBTs, transformers, optocouplers)  
- [ ] Pin and trace markings  
- [ ] Notes on resin removal and circuit access  

---

## 🧩 Board Mapping

### Y-SUS
- Power rails (VSC, VY, GND)  
- Switching stages  
- IGBTs used  
- Logic/control section (drivers and oscillators)  
- Notes on aging, heat, or anomalies  

### Z-SUS
- Power rails (VS, GND)  
- Switching stages  
- Sustain and discharge control  
- Protection circuitry  
- Analysis of SCR protection (VY/VSC detection)  

---

## 🛠 Modifications and Tests

- [ ] Resin removal  
- [ ] Replacement of degraded transistors  
- [ ] Tests with isolated circuits  
- [ ] Reverse conduction for switch behavior analysis  
- [ ] Measurements with and without load  

---

## 📊 Analysis and Oscillograms

- Overshoots measured (e.g., 19 MHz without load)  
- Gate control waveform behavior  
- Noise propagation across the board  
- Comparisons before and after component replacement  

---

## 🧪 Next Steps

- [ ] Final board installation in the TV  
- [ ] Image and system stability tests  
- [ ] Signal capture with oscilloscope after assembly  
- [ ] Logging of anomalies (if any)  

---

## 📝 Conclusion

(Reserved for final project wrap-up notes and observations)

---

## 📁 Repository Structure

```bash
TV_PLASMA/
├── Y-SUS/
│   ├── photos/
│   └── schematics/
├── Z-SUS/
│   ├── photos/
│   └── schematics/
├── README.md
└── oscillograms/

