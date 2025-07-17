# Reverse Engineering – LG 42PQ30R (Plasma TV)

This project documents the reverse engineering process in Z board and Y board of the LG 42PQ30R plasma TV. It includes circuit analysis, measurements, and common fault diagnostics.

# _Details:_

## Z-Board:

**Model:**

LGE PDP 081223

BOARD: 42G2_Z

PART NO: EAX57633801

REV.: M

LOC NO: 3XXX

<p align="center">
 <img src="images/Z-board-top.jpg" alt="ZBOARD" width="80%"/>
</p>

### Z-Board Top (detailed)

<p align="center">
 <img src="images/Z-top-detail.jpg" alt="ZBOARD-detail" width="80%"/>
</p>

## Y-Board:

**Model:**

LGE PDP 090209

BOARD: 42G2_YSUS

PART NO: EAX57633701

REV.: N

LOC NO: 2XXX

<p align="center">
 <img src="images/Y-board-top.jpg" alt="YBOARD" width="80%"/>
</p>

---

## 📷 Photos and Schematics

- General photos of the Y-SUS board [top](images/Y-board-top.jpg) [bottom](images/Y-board-bottom.jpg)
- General photos of the Z-SUS board [top](images/Z-board-top.jpg) [bottom](images/Z-board-bottom.jpg)
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

