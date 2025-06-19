# Electronics2_Project
# ELC2060 Final Electronics Project

This repository contains our final electronics project for the ELC2060 course at the Faculty of Engineering, EECE Department. The project focuses on analog CMOS design principles including current sources, current mirrors, and voltage-controlled oscillators (VCOs).

---

## 👨‍💻 Team Members
| Name                    | Code     |
|-------------------------|----------|
| Mahmoud Hussieny Matar | 9230832  |
| Mahmoud Mohamed Ezzat  | 9230843  |
| Marwa Ibrahim Fathy     | 9230856  |
| Mohamed Hesham Waheed El-Deen | 9230819 |
| Ahmed Ibrahim Sabry     | 9230117  |

---

## 📌 Tasks Summary

### ✅ Task 1: NMOS Current Source Characterization
- Extracted Vth, Vov, Vdsat, gm*ro for different aspect ratios.
- Verified simulation matches the long-channel model.
- Selected suitable NMOS for high-gain amplifiers.

### ✅ Task 2: High-Swing Current Mirror Design
- Cascode-based current mirror with enhanced Rout.
- Verified Iout ≈ 201 µA with <1% error.
- Rout ≈ 725.6 KΩ via small-signal AC analysis.
- Estimated layout area ≈ 0.997 nm².
- Trade-off explored: Reduce Rout to decrease area.

### ✅ Task 3: Voltage-Controlled Oscillator (VCO)
- 6-stage CMOS ring oscillator controlled by Vcont.
- Achieved oscillation at ~20 MHz.
- Capacitor tuning reduced transistor sizing.
- Observed linear relationship between Vcont and frequency.

---

## 🛠️ Tools & Resources
- **Cadence Virtuoso** and **ADE XL** for schematic and simulation
- **Theory References:**
  - Razavi’s *Design of Analog CMOS ICs*
  - Gray & Meyer’s *Analysis and Design of Analog ICs*
  - Tsividis’s *MOS Transistor Modeling*

---

## 📊 Results Highlights
| Metric         | Value              |
|----------------|--------------------|
| VCO Frequency  | 20 MHz             |
| Current Mirror Iout | ≈ 201 µA    |
| Current Mirror Rout | ≈ 725.6 KΩ  |
| Vth from DC    | ~0.2 V             |
| Total Area     | ~0.997 nm²         |

---

## 📎 License
This academic project is submitted as part of the ELC2060 course. Not for commercial use.

---

## 📫 Contact
Feel free to reach out if you'd like to know more about the project or collaborate on analog IC design.
